# android-development-guide
Notes , helpful documentation and blog links and possibly cheatsheets


## Right now on hyperskill learning path

1. [Inner classes in java](https://docs.oracle.com/javase/tutorial/java/javaOO/nested.html)
Inner classes can be declared private,static , protected , public anything we wish.
Why Inner classes or nested classes? Because : 
* maintain readability
* some functionality that is used only on one place.
* shadowing and encapsulation


2. [Packages in java](https://www.geeksforgeeks.org/packages-in-java/)

3. [using packages in java -- oracle docs](https://docs.oracle.com/javase/tutorial/java/package/usepkgs.html)

Apparent Hierarchies of Packages

At first, packages appear to be hierarchical, but they are not. For example, the Java API includes a java.awt package, a java.awt.color package, a java.awt.font package, and many others that begin with java.awt. However, the java.awt.color package, the java.awt.font package, and other java.awt.xxxx packages are not included in the java.awt package. The prefix java.awt (the Java Abstract Window Toolkit) is used for a number of related packages to make the relationship evident, but not to show inclusion.

Importing java.awt.* imports all of the types in the java.awt package, but it does not import java.awt.color, java.awt.font, or any other java.awt.xxxx packages. If you plan to use the classes and other types in java.awt.color as well as those in java.awt, you must import both packages with all their files:

        import java.awt.*;
        import java.awt.color.*;
        
        
        
4. [Constructor in java](https://www.javaworld.com/article/2076204/understanding-constructors.html)
5. [Java: Use of private constructors](https://beginnersbook.com/2013/12/java-private-constructor-example/)

      For Singleton class: Those class which only allows one instance to be created at a time. Examples can be 
      A superhero ability which can only be instantiated once orbs are collected. 
      
6. [Exceptions in java](https://docs.oracle.com/javase/tutorial/essential/exceptions/index.html)

7.[Hyperskill exception heirarchy](https://hyperskill.org/learn/step/3570)
8.[upcasting and downcasting in java](https://www.edureka.co/blog/upcasting-and-downcasting-in-java/)
     
     Question. When do you get classCastException in java?
9. [stack overflow upcasting and downcasting question](https://stackoverflow.com/questions/23414090/what-is-the-difference-between-up-casting-and-down-casting-with-respect-to-class)

When you upcast you are allowing superclass object instance to have subclass instance reference. Your superclass is pointing to same reference as your subclass instance but with a restriction. Superclass methods will be overrided by subclass methods. and only superclass specific items are accessible. 

When you downcast you are allowing subclass to have superclass instance. The danger lies here because your superclass object may not be referencing same object type as your subclass. Say if your superclass is fruit and holding apple right now. You can safely downcast but when superclass is holding a banana then it will throw a  classCastException which is unchecked exepction. i.e compiler wont care about it. but during runtime it might get invoked.

10. [Byte streams in java](https://www.geeksforgeeks.org/serialization-in-java/)

        


