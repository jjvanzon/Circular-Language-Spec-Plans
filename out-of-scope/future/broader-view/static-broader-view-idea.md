Circular Language Spec Plans | Broader View
===========================================

Static | Broader View | Idea
----------------------------

*2020-04*

Static may be a concept part of the Circular Language Spec, but the idea below incorporates concepts, that I want to put out of scope and save for documentation about a broader perspective or something.

-----

Projects / Static,  
2008-09-21

Commands and procedures have now become data, and are just as changeable as data, unless you put some access control on it.

This has as an effect that each object of a class has its own copy of the commands and procedures. In other programming languages all the objects shared the commands and procedure code, so they did not need to have their own copy, because an object had its own data but not its own code. In Circular, code is data, so in Circular we might call the code, data that is shared by all objects of a class.

Such data sharing should be addressed in a the future in a separate project, because if you don’t, then data storage in Circular might be less efficient than in other systems.

JJ