Encircle Language Spec Plans
============================

Static Notation | Language Design | Plan
----------------------------------------

### Postponed

The concept of Static could be worked out.

There seem to be competing ideas about static in this project: expressing an original language's intent with the word 'static' (e.g. C#) and, on the other hand, a more generalized concept of static, that anything about a class that remains unchangeable during or after instantiation, is static. (Including method definitions, static variables.) What happens when you use dashed lines to express anything 'static'? This while dashed lines conceptually also stand for 'class'. Do the concepts of static and class merge naturally, or how would that look in practice? This is fruit for thought for updating the descriptions of Static and Classes. 'Static' might not even get a separate description.

Note that the Static article may be buried in the Classes folder in the Encircle Language Spec.

"Static Broader View Idea.md" may elaborate, though those ideas might be out of scope for now.

#### 2020-06-18 Postponed Static Notation

I also tend to go into when circles are displayed dashed. There I imply that symbols are dashed if they are used as a class, and if they are not, they are not. So members of classes would be drawn with a solid border. This seems to be, because the rule was: dashed borders was optional, if used, then it would imply the symbol is a class, or used as a class. But in other places in the docs, I already introduce variations on usages of dashed borders. Not describing it as a hard rule may help, a lot possibly. But the splinter in my brain is: I might have specific plans for the dashed borders. It might imply something is static. But I have not worked that out yet. And as I think about it, I think it might not work. If something's object aspect is not static, but something's class aspect is, a dashed border would not disambiguate. I like the idea of being able to configure each aspect of each symbol or member as static or not. I like the idea of expressing a symbol's being static as it being drawn with a dashed line. But as I think of it, it may not work unambiguously. I remember times where if I explore the idea, I might come up with a solution, for something initially seeming full of road blocks and perceived impossibilities. It's like a puzzle that I formulated myself. It is something I like about doing software. I think my idea about expressing the concept of static by having a symbol drawn in dashed borders, was when the *object* aspect would be static. Not the class aspect or the value aspect. Maybe that is a base of a notation. 

I think that for now, it might be a better idea not to express such notational choices where I use notational choices, because it seems not the subject at hand, and discussed elsewhere already and might obscure the main point.