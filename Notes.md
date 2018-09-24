# Java
Java is an object-oriented programming language and a platform developed by Sun Microsystes (eaten by Oracle). It uses the WORA priciple (Write Once, Run Anywhere), meaning any java application can be excuted on any platform with a JVM (Java Virtual Machine). It's a flexible and popular language for many years, allowing developers to write large client-server web applications, desktop and mobile applications, and frameworks and libraries. 

## Features
**Platform independence**: The compiler converts source code to bytecode, then the JVM executes that bytecode. While each opperating system has their own JVM implementation, so every JVM can execute bytecode regardless of origin of said bytecode.

**Clear, verbose syntax**: Java has C-like syntax like C++ and C#, many syntax alements of the language are readable ad widely used in programming. The Java API (Application Programming Interface) is also written using verbose, descriptive naming conventions making it simple to parse large code bases.

**Multi-paradigm**: WHile Java is Object-oriented, it supports multiple paradigms such as imperative, generic, concurrent, and functional.

**Garbage collection**: The JVM performs automatic memory deallocation of unused objects at runtime. Programs are written without the need of complex memory management.

**Multithreading**: Java supports multithreading at both languange and the standard library levels. It allows concurrent and parallel execution of several parts of a Java program.

**Object-Oriented Programming**: Although Java accomodates several paradigms, OOP is the foundation for most applications. In OOP, a program is organized into objects encapsulating related fields (representing its *state*) and methods (usually to control that state or perform related functions). When defining objects, Java reserves the keyword *class* (not to be confused with the *.class* file extension) which serves as their blueprint. An object in Java represents an instance in memory of a class, and also every class implicitly inherits from the *Object* superclass which provides useful convenience methods such as *equals()* and *toString()*.  Class defines what the object will be in memory (variables, methods, etc.) Java popularized several 'Pillars' of OOP design theory. While the numbers vary between OOP languages, Java focuses on four:

*Abstraction* - By simplifying objects to a set of useful features, we hide irrelevant details, reduce complexity, and increase efficiency. Abstraction is important at all levels of software and computer engineering, but essential to designing useful objects. Comlicated real-world objects are reduced to simple representation.

*Encapsulation* - Objects should group together related variables and functions, and be in complete control over them. So the state of an object should only change, if ever, through the object itself. Also known as data hiding, because the object has sole responsilbilty for its fields, and no outside object or function should interfere.

*Inheritance* - Code reuse is an important principle of programming (DRY - Don't Repeat Yourself), and new classes can reuse code from existing ones. This establishes a superclass-subclass (or parent-child) relationship where the derived classes inherit (and sometimes change) fields and methods from its parent.

*Polymorphism* - With inheritance, an object of a derived class can be referenced as instances of its parent class. This provides flexibility when invoking inherited methods with varying implementations in derived classes.
