Circle Language Spec Plan, Static Spec Idea
===========================================
*JJ van Zon, The Netherlands, 2020-04*

The concept of Static could be worked out.

There seem to be competing ideas about static in this project: expressing an original language's intent with the word 'static' (e.g. C#) and, on the other hand, a more generalized concept of static, that anything about a class that remains unchangeable during or after instantiation, is static. (Including method definitions, static variables.) What happens when you use dashed lines to express anything 'static'? This while dashed lines conceptually also stand for 'class'. Do the concepts of static and class merge naturally, or how would that look in practice? This is fruit for thought for updating the descriptions of Static and Classes. 'Static' might not even get a separate description.

Note that the Static article may be burried in the Classes folder in the Circle Language Spec.


Projects / Static,
2008-09-21

Commands and procedures have now become data, and are just as changeable as data, unless you put some access control on it.

This has as an effect that each object of a class has its own copy of the commands and procedures. In other programming languages all the objects shared the commands and procedure code, so they did not need to have their own copy, because an object had its own data but not its own code. In the new computer language, code is data, so in the new computer language we would call the code, data that is shared by all objects of a class.

Such data sharing should be adressed in a the future in a separate project, because if you don’t, then data storage in the new computer language will be less efficient than in other systems.

JJ
