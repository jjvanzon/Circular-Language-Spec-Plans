Encircle Language Spec | Inheritance Spec | 2010-05 | Strategy & Steps
======================================================================


Purpose of this Document
------------------------

This document is not meant as reading material. It is a list of steps undertaken in the project, later serving as a reference for how the project was executed.


Strategy
--------

- Improvise
- Use same strategy as the previous project and see if it works.
- Also consider saving the hardest topics for later.
- The inheritance documentation does something with object resolution topics.
First it was thought that object resolution might also be finished up in this project, but this idea was let go of.
- The next project will be about working towards an implementation phase as soon as possible.


Steps
-----

- [x] Short Brainstorm
- [x] Read over strategy from previous project
- [x] Compose topic list
    - [x] Start making a topic list off the top of your head
    - [x] Extend topic list going through the short existing texts about inheritance
    - [x] Look at object resolution concepts for Overriding, Shadowing, etcetera
    - [x] Extend topic list going through the long existing texts about inheritance.
    - [x] Look at Black Boxing for Exclusion topics
    - [x] Brainstorm about unclarities
    - [x] Finish up topic list
    - [x] Read over ‘writing efficiently’
    - [x] Finish up topic list
- [x] Start writing already
    - [x] Main Concepts
    - [x] Work out the List concept:  
        - [x] \> In the System Objects chapter  
        - [x] A list’s control over aspects of its items & adressing the list as a normal object should go through its system interface, because that is the internal working of the list (the system object).
    - [x] Specialization:
        - [x] Altering the Member Set
        - [x] Detouring Members
        - [x] Altering Command Implementations
    - [x] Miscellaneous Situations
    - [x] Make Notation for ‘Required’
        - [x] \> In the Parameters chapter.
    - [x] Enforcing & Preventing Specialization
    - [ ] ... Deeper Specialization
    - [x] Change approach:
        - [x] Remove intrinsic overriding notation
        - [x] Add data replacement versus specialization
- [x] More work:
    - [x] Reorient in the plan
    - [x] Read the articles
    - [x] Read the brainstorms
    - [x] Make evident changes, that are mentioned in brainstorm text
    - [x] Add missing stuff to articles, such as missing pictures
        - [x] \> Split up the Specialization article already
        - [x] \> Changed the Interface section of Enforcing & Preventing Specialization
            - [x] \> I also have an idea for specifying rules that apply to all sub-objects. Maybe that can be derived from the list concept.
    - [x] Set up open issue list
    - [x] Add one Miscellaneous Inheritance Situation:
        - [x] One object inheriting multiply from the same class.
    - [x] Propose solutions for open issues & adapt articles to them
        - [x] Deeper Specialization Structure
        - [x] Deeper Member Addition
    - [x] Deeper Specialization is now finished
    - [x] ~ Other open issues are postponed
    - [x] ~ Write Misc Deeper Specialization Situations
        - [x] ~ Deeper Additional Members in an Object - List - Object – Object situation
    - [x] Change System Inheritance:
        > It used to be normal object and class inheritance, but now it is changed so that you can specialize any deeper object, so that you can specialize as deep into the hierarchy as you want.
    - [x] Something to consider though, is that when a much deeper object is specialized, all the levels that lead to the deeper object will also get a specialized version.
        - [x] \> Add deeper member addition example with a triangle in each layer in it
            - [x] In Misc Deeper Specialization Situations
                - [x] \> Removed this article degrading it to an idea
            - [x] And in Deeper Specialization, Deeper Member Addition.
            - [x] And in System Inheritance
                - [x] \> Left a remark in it about specializing each layer, and referred to the Deeper Specialization article.
        - [x] Postpone the other deeper specialization situations
- [x] Wrap up:
    - [x] Change reference to Deeper Specialization in System Inheritance to a reference to Even Deeper Member Addition.
    - [x] Split up into more articles
        - [x] \> I create a lot more articles this way
        - [x] \> I split up the following:
            - [x] Main Concepts
            - [x] Altering the Member Set
            - [x] Altering Command Implementations
        - [x] \> but I did not split up the following ones:
            - [x] Enforcing & Preventing Specialization
            - [x] Deeper Specialization
    - [x] Cross out
        - [x] Ideas document in chapter
        - [x] Ideas in this project documentation
    - [x] Consider Creator 0.9 concepts
        - [x] \> They mostly have to do with generic user interfaces. I will not cover that here.
    - [x] ~ Read over
        - [x] ~ Only did half of that because I want to move on.
    - [x] And finish up project
        - [x] Tidy up software development plan documents
        - [x] Isolate version a version
        - [x] Make entry in project list tidy
        - [x] Update article in parent folder