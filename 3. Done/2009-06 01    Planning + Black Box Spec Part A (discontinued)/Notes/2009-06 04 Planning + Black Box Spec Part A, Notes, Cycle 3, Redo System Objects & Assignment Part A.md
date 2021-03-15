Circle Language Spec Plan | Planning + Black Box Spec Part A | 2009-06 | Cycle 3: Redo System Objects & Assignment A
====================================================================================================================


Purpose of This Document
------------------------

This document is a checklist for software development-related work, for a good approach and to not forget anything. It is not to be read over literally. Later it serves as a reference for looking up how exactly something was done.


Reflection
----------

This phase is where it went wrong. Work spiraled out of control.


Rough Plan
----------

Black boxing has a lot to do with assignment and system aspects. The black boxing notations need to match with the assignment notation and the system objects notation, so you have to make the notation in the Assignment articles and in the System Objects articles ok.

- Update Assignment Articles
    - Get the notation straight
- Update System Objects Articles
    - Get the notation straight

Also, parts out of the Black Boxing documentation need to be moved to the Assignment and System Objects articles, where they belong.

In the end, the Assignment articles were integrated into the System Objects article group, because it was easier to explain those together.


Approach
--------

I introduce things in wrongly composed chunks in the System Objects documentation.

- What I am missing is immediate overview of System Objects (e.g. Related Item, List Item), immediate overview of System Aspects, and then the definition of a system command.
- It starts out with a very difficult story
- Way too many details seem to be mentioned.
- Perhaps you should first explain the System Objects
- And only then their system aspects
- And perhaps even separately the system commands
-----
- Base it more on a story about System Aspects.

This should be the new order:

- All the system objects in general and how they relate to each other
- All the system aspects in general
- The system commands in general and per aspect
- The system interface in general
- All the system objects with the system interface notation  
  \> Without system commands in it?
- System commands in the system interface notation


Steps
-----

### Additions

- [x] Object-Bound and Reference-Bound

    - [x] Moet naar daar verplaatst worden.
    - [x] ~~En de rest aanpassen aan onderscheid Object-Bound en Reference-Bound~~
        - [x] \> ~~Hoefde niet. Alleen Value is object-bound in het bestaande materiaal.~~

- [x] System command call notation:

    - [x] Calls without argument / counterpart
    - [x] Calls with an argument / counterpart  
          (zonder counterpart is het eigenlijk niet compleet.)  
          (laat het argument niet expliciet zien in de call:  
          het argument is aan de andere kant van de lijn)
    - [x] Explicit Get with implicit Set

- [x] Assignment

    - [x] Integrate assignment into it.
        - [x] Split up into multiple articles.
    -----
    - [x] ~ Assignment:
        - [x] Assignment notatie moet iets vereenvoudigd  
              \> Hele ding in een bepaald line type, inclusief direction mark en assignment call symbool
            - [x] Reference assignment hoeft niet per se een pijl,  
                  tenzij het een assignment is van een reference op hetzelfde niveau.  
                  maar in alle andere gevallen is de source van de assignment inward.  
                  \> Eigenlijk wil ik dat wel, omdat het een heel speciaal effect heeft, pointer assignment.

- [x] Access connector notation:

    - [x] Then the system command connectors (get, set and use do not show a command symbol)
    -----
    - [x] Represents a potential call
    - [x] Which also makes it represent the system command definition, that can be called upon
    - [x] System Commands zou op zich al access connectors kunnen behandelen, maar dan zonder Private en Friend, dus zonder black boxing.
    - [x] Access connectors zijn ook potentiele calls naar system commands die moeten ieder lijken op het resultaat of anders op de call.

- [x] The explicit notations:

    - [x] Philosophy: the explicit, non-simplified system command call notation should be worked out last with a clarification for why it gets a more basic notation.
    - [x] 1) System Command Call with Argument / Explicit Get, Implicit Set
        - [x] > Add the cross-aspect things
    - [x] 2) Explicit Get, Set and Use (both counterparts explicit)
    - [x] 3) Explicit display of Get and Set arguments
    - [x] One article:
        - [x] 4) Completely explicit display: showing the system interface and the exactly correct line types.
        - [x] 5) Explicit display of assignment
            - [x] (the name of the assignment command is for instance 'o='. Completely explicit display also means displaying that name.)
        - [x] Maybe integrate the last two in the same article, because they look so similar.
            - [x] In the article put in a comparison to the substituted notation of assignment.

- [x] Connections    
      \> (a new addition)
    - [x] You would also want Connections to have an article in the system objects article group.

### Reorganizations

- [x] Topic list:
    - [x] System Objects
        - [x] The Object
        - [x] The Reference
        - [x] Related Object
        - [x] Related Item
        - [x] Related List
        - [x] Item
        - [x] Related List Item
        - [x] Symbol
        - [x] Related Items & Related Lists Collections
    - [x] System Aspects
        - [x] Reference
        - [x] Object
        - [x] Class
        - [x] Value
        - [x] Clone
        - [x] Name
        - [x] Existence
        - [x] Data
        - [x] Execute
        - [x] List
        - [x] Interface
    - [x] System Commands
        - [x] For Reference Aspect
        - [x] For Object Aspect
        - [x] For Class Aspect
        - [x] The Extra Commands, Overloads & Delegation
        - [x] For Value Aspect
        - [x] For Clone Aspect
        - [x] For Name Aspect
        - [x] For Data Aspect
        - [x] For Execute Aspect
        - [x] For Existence Aspect
        - [x] For Add & Remove Aspect
    - [x] System Interfaces
        - [x] General System Interface Notation
        - [x] For Object
        - [x] For Related Item
        - [x] For Related List
        - [x] For Related List Item
        - [x] Rules:
            - [x] Small plan:
                - [x] Try to summarize the rules
                - [x] Add stuff you forgot to mention
                - [x] Read over existing material to see where the rules are mentioned
                    - [x] And isolate the rules in separate articles, instead of repeating them.
                - [x] Forgot to mention:
                    - [x] I forgot to mention the optional Class argument in the System Commands for the Existence Aspect.
                    - [x] And perhaps also the arguments in the Add command in the System Commands for the List Aspect.
                - [x] Rules repeated:
                    - [x] Use-Commands Get Another Aspect
                    - [x] Aspect-In-A-Triangle design choice
                - [x] "24. System Interfaces of Objects & References"
                    - [x] Final choice:
                        - [x] Reference system interface by default, within which the Related Object is visible, with its system interface showing.
                        - [x] Practical other option:
                            - [x] ~~Display both object-related aspects and reference-related aspects in the same system interface.~~
                            - \> A symbol can have multiple system objects, so multiple system interfaces.
                            - \> For instance: one symbol can have an OBJECT system object and a related item system object.
                    - [x] ~~Impractical options:~~
                        - [x] ~~Show Object system interface in imaginary reference.~~  
                        ~~Show Reference system interface everywhere else.~~  
                        ~~But that will make it hard to for instance get a Value through a reference.~~
                        - [x] ~~Always show Object system interface, and through it its related items.~~  
                        ~~But then you can not directly work with related items,~~  
                        ~~you would have to go through the system interface of its parent object.~~
                            - \> ~~Oh, and the object system object will have a related lists and related items collections.~~
                - [x] Preliminariness
                    - [x] How the system interface looks is totally dependent on how the code base is implemented. If you make different design choices about the code base, organizing members differently, the system interface will also look different, because the system interface is an exact representation of the public members of the system object.
                    - Not covered:
                        - [x] ~~Show aspect as property~~
                - [x] Detail:
                    - [x] Use more lidwoorden in titles for commands for aspects

    - [x] Read over

    - [x] After you put the existing newer topics:

        - [x] Assignments
        - [x] Connectors & Connections
        - [x] System Command Calls
        - [x] Explicit Notations
        -----
        - (not necessarily in that order)
        - (you can simplify them)

\> At this point you have a fairly well finished up chapter,
except for a lot of cross-out material.

### Cross-Out + Additions

- [x] Cross out old articles

- [x] Remaining topics:

    - [x] System interface command call
    - [x] ~ System Command Extension
        - [x] ~ Preliminarily Finished
    - [x] ~ Parameters For Objects
        - [x] > Leave this way
    - [x] Ancestry Terms
    - [x] ~~Transform Method To Object (cross out)~~
        - [x] \> Content redistributed

- [x] Cross out Ideas (+/- 60 pages)
    - [x] \> I was worried about a lot of extra aspects, to control other system object members, and a lot of extra Get purposes, but there are not that many left. Just a couple.

### Work Discontinued

There were other cross-outs, but they are postponed.  
At this point work had spiraled out of control.  
This project is wrapped up and a replanning is done after which the work continues as a new project.