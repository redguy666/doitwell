# "DoItWell" interface

Many of you dream about making things easier. We present you final achievment in IT world: the "DoItWell" interface.
It is as simple as it can be, but yet powerfull.

```
inferface DoItWell {

  Object doItWell(String whatToDo);

}
```

As you can see you simply pass what you need to be done, and backend implementation takes care of everything. And it is done well!
Its applications are limitless. From simple 'Hello world' application:

```
DoItWell doItWell = DoItWellFactory.getDoItWellInstance();

Object result = doItWell.doItWell( "'Hello world' application" );
```

or often provided as example simple blog application:
```
Object result = doItWell.doItWell( "Simple blog application" );
```

to sophisticated fullstack solutions:
```
Object result = doItWell.doItWell( "Facebook-like social networking" );
```

It just works!

As for now the interface is well described and we have first protein based backend implementation.
It is not so fast, but we think that in near future we can use current implementation to generate next-level versions
and implementations in in most known programming languages.
