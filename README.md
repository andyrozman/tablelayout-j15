
# TableLayout - An Alternative to GridBagLayout


TableLayout is a totally free layout manager designed to make creating user interfaces fast and easy.
It can do anything GridBagLayout can do and much, much more. Yet it is remarkably simple and easy to use.

This is fork from original site (https://java.net/projects/tablelayout/).


Why new fork
------------

I created this fork because of two reasons:

1. Existing maven artifact is from 2005, while last version from sources is from 2009
2. I need artifact compiled with Java 1.5 (old Mac support)


Artifact info
--------------

If you need this artifact you can build it yourself, for now it will not be deployed publically (at least not from me)

```xml
<dependency>
    <groupId>info.clearthought</groupId>
    <artifactId>tablelayout-j15</artifactId>
    <version>4.2.1</version>
</dependency>
```

Packaging
---------

I have packed whole project into one artifact. So we have tablelayout core, builders and extensions in same artifact,
all test and example classes are also here (under src/test/java).

Builders and extensions are now in its own (java) package:

info.clearthought.layout.ComponentArranger -> info.clearthought.layout.builders.ComponentArranger

info.clearthought.layout.TableLayoutPersistenceDelegate -> info.clearthought.layout.extensions.TableLayoutPersistenceDelegate


Owner
-----

Owners of this software are still: Daniel E. Barbalace and Juergen Schwibs (extensions). I just packaged it new, so
that all people that need it can use it without much problems (Maven 3.x and Java 1.5).


Version info
--------------

4.2 - Original version (at least that is info I found in files)
4.2.1 - New packaging



Since there was very old maven artifact there, I decided to create

