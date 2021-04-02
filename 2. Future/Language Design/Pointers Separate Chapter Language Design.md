Encircle Language Spec Plans
============================

Pointers | Separate Chapter | Language Design
---------------------------------------------

*Over-awareness of pointers?*

### Postponed

#### 2020-05-27 Postponed Pointers Chapter

- [ ] ~ Maybe pointer-to-pointer situations might all be moved away from each chapter and into a separate chapter. It seems a specific issue and many things seem to be able to live without it.

#### 2020-06-11 Postponed Over-Awareness of Pointers

- [ ] ~ Some texts may also make a bit of an issue out of something almost always being related to a *parent* *object*. It may have gone a bit far incorporating that concept in pictures, usage of terminology. In pictures by displaying a parent object, where it might not add much and it might be an idea to remove it for clarity. In terminology, awareness of ref-ness might have slipped in by calling things related items and related lists more often than perhaps required. The terms 'object' or 'item' and 'list' might do in cases and that may make the text easier to absorb.
- [ ] ~ Redirection ('ref-ness'?) might be part of the Pointers topic.

### Done

#### 2020-06-26 Done Scoping System Objects Article: Move Pointer-to-Pointer Issues

- [x] Reference aspect does seem used only for pointer-to-pointer situations? And without the context of pointer-to-pointer situations, the concept of the reference aspect might also be hard to place.
- [x] More prominently might be the pointer (to pointer) issues, which I promised myself I would move to the separate Pointers chapter. I think most of that is a bit scattered around the System Commands and System Interfaces sections.
- [x] It seems iffy to me, that all point-to-pointer issues should be moved. The distinction between the Reference aspect and the Object aspect might be desired for a certain completeness. (Evaluating this, I am currently looking specifically at an image under the section "The Full System Interface for Related Item"). Perhaps pointer-to-pointer *details* might be moved.
- [x] That there are references and that there are objects, might be key to understanding a bit about this particular object oriented take on things. But as it starts getting a bit hard on your head with pointer-to-pointer edge-cases, maybe I can extract those topics and move those.
- [x] It is becoming harder for me now, because it is iffy. I can notice it inside myself.
- [x] Here I start scratching my head about whether these are details I might leave out of the main story: under "The Extra Commands & Overloads":
    - [x] __Set Object__ => __Set Object to Other Related Item__
    - [x] __Set Object__ => __Set Object to Other Related List Item__
    - [x] __Object Get__ => __Get Object which is Another Related Item__
    - [x] __Object Get__ => __Get Object which is Another Related List Item__
- [x] I see now that the section is named "The Extra Commands & Overloads". So it seems isolated, and perhaps separately movable to the Pointers chapter?
- [x] "Get Class which is a Reference" might have overloads that are perhaps pointer to pointer situations?
- [x] "Set Class to Reference" might also be a pointer-to-pointer situation.