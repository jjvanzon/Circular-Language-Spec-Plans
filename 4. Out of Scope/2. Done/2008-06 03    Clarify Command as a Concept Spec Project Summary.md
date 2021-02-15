Circle Language Spec Plan | Clarify Command as a Concept Spec | 2008-06 | Project Summary
=========================================================================================


Goal
----

Clarify everything unclear about:

- Automatic execution order
- Parameters, input, output, throughput 
- The implementation of commands as a concept

And their diagram expression.

To which extent this can solve concurrency issues was also looked at but not fully worked out.


Super-Project
-------------

This project used to be the beginning of the project ‘Command As A Concept’, which proved to be too large, so it was split up into multiple projects.


Date & Time
-----------

June 23, 2008 – July 13, 2008  
3 weeks  
52 ¼ hours of work


Products
--------

A document was produced: *Command As A Concept Brainstorm Texts*  
It is put in the documentation as the *Commands*  article group version *2008-07-13 XX .*  
It is approximately __32__ pages of brainstorm texts trying to clarify commands as a concept.


Project Steps
-------------

- Go through all ideas you can find
- Organize brainstorm items
- Reformulate brainstorm texts, determining how things will be
    - In, out, thru, down
        - Reconsider
        - Integrate old text into new text
        - Reformulate the introduction
        - Reformulate the Parameter Passing Type Details
        - Make the parameter passing specific sections a more complete description, taking over texts from he introduction.
        - Reformulate the Issues sections
    - Automatic Execution Order
        - Reformulate
        - Cross out remaining brainstorms
        - Regroup information
    - Postpone concurrency resolution
        - Make it a future project
    - System interface
    - Remaining topics
- Read over some material:
    - Read over the execution control articles
        - \> Was not that influential anymore.
    - Read over brainstorm texts.
- Revise the list of articles
- Version the brainstorm texts, before cutting it up.
- Change order of documentation:
    - More into the order in which you might like to read it.
    - You might have the tendency to jump around the documentation, if something in the flow is off. So a change of the order might help there.
    - Drop Diagram and Text expression right next to conceptual explanation
    - Mix Coding Principles and Concepts
        - I often change my mind about implementing something as a 'principle' or as a 'concept'. (The difference between concept and principle is 'made up' just to label things: a principle would be an intrinsic part of the language, a concept could be programmed out using the language itself.)
        - It seems less ideal to have some assignment topics on one end of the documentation, and other assignment topics at the other end of the documentation.
    - Add ‘Implementation’ section to each concept.
    - Change the documentation titles
        - (articles have moved to another documentation section)
    - Group together Concept and Diagram versions.
        - Per concept
        - For groups of concepts
    - Try to make the file names nice again.
    - Better numbering of articles.
    - ~X Summary of what the small base of the code will consist of / which coding 'concepts' are 'principles'.
    - Flat & Structure Interchange seem spread around the documentation too.
        - But a summary was put in Fundamental Principles
    - It may be useful to have some extra diagram expression topics:
        - Basic diagram elements
        - Diagrams as a concept
        - Automatic containment (is also a diagram expression topic.)