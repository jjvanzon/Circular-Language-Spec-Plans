Encircle Language Spec
======================

Strategy (Out of Scope)
-----------------------

__Contents__

- [Introduction](#introduction)
- [Higher Goal](#higher-goal)
- [Scope](#scope)
- [Implementation Strategy](#implementation-strategy)
    - [How Much Designing Before You Implement](#how-much-designing-before-you-implement)
    - [Principles & Aspects](#principles--aspects)

### Introduction

This document describes strategy and goals of the project *Encircle Language Spec*, but then topics that were deemed *out of scope*.

At first it was content moved from the document *Encircle Language Spec Strategy*.

*Out of Scope* might not mean *deprecated*, but more like *not part of the spec* or *not for now*. They might be construct drafts, or topics about a broader perspective on things.

### Higher Goal

One of my worries, is that I have not learned enough constructs, that exist in the world, to really make a unified language for all digital objects. The language was supposed to give a different view onto any digital data: folders, scheduled tasks, object oriented code, the web, databases or any complicated referential structure. It is supposed to combine all of it into a single landscape in a single language, and serve as an entry-point for all other types of digital expression, such as opening data in the app it is intended for, displaying that view on top of the diagram, that is a map of everything going on inside the computer.

Here are some of the hopes for Encircle:

- ~ Gain instant insight into complex referential structures, hopefully to a degree that no other way of diagramming can.
- ~ *Anything* digital might be translated to such a diagram, because most things digital may just be referential structures.
- ~ Making it easier to program software.
- ~ Making *programming* the same as *using* a computer.
- ~ Offering an instant user interface for anything digital and traditionally invisible.
- ~ The invisibility of digital connections, that software developers and ICT infrastructure engineers only imagine in their head, might now be visualized on screen.

What might prove that the diagram language fails:

- ~ That the diagram expression does not simplify the view on complex referential structures, but that it will still look like an unoverviewable bunch of wiring.
- ~ Do take comfort in the fact, that if this goal is not reached, the language might still have other uses.

There were more hopes for the language, but the goals above might be some highlights.

### Scope

There may be specific reasons why something might be *out of scope*. Those might be organized into the following categories:

- Construct Drafts
- Broader View

Those categories might still be found as sub-folders of the *Encircle Language Spec* documentation, though not really considered part of the spec.

These might be the more specific reasons things may be out of scope:

- Construct Drafts:
    - Lesser worked out
    - Deprecated
    - Optional
    - Side-ways topics
    - Previous versions
    - Implementations
    - Text code
    - Standard libraries
- Broader View:
    - Philosophy
    - Dreams about the future
    - Integrating systems

### Implementation Strategy

Implementing Encircle Language in software is deemed out of scope.

- ~ Programming: Essential Libraries: Math, Integrate  
    (2020-01: Programming things is not really a goal right now.)
- ~ Programming: Program a version (part done)

This was a point at which, it seemed a good plan to program some software. While not all pieces of the language were designed yet, some experimental things had been programmed. One fear was: making something, that would later be thrown away, would the language change completely. But the base of the language was not expected to change drastically. Another fear was to lose time programming, that was better spent on the language design. The hope was, that a working version would tell where the big problems are would indicate solutions to problems initially not possible to get your head around.

#### How Much Designing Before You Implement

You might want to see a concept running, in a conceptual implementation, to be able to see where the design fails. That is kind of a flaw in designing everything first. You might not be able work out everything in theory first. The design may be imperfect, until it is proven by a conceptual version.  Working out too much in theory can lead to results inefficiently, compared to working out the idea roughly, and then building a conceptual version.  
Human beings may much more easily identify flaws in running system, than they can before anything has even been made.

An experimental new version of Encircle could be created at one point, that supports all the principles in its minimal form, just to see how it will look in action. The left-over problems may become apparent quickly then. And an experimental implementation may also *prove* the concepts. It probably gives you a clearer picture of the language, which may help to complete other topics.

But when the next conceptual implementation will be created is unclear. That would be the project *Program Base Code*.

Sometimes it can be demotivating, that making the design takes so much time and seems to render so little result. But it may be relevant, that the ideas could be picked up by others. More arguably it may be relevant, that it becomes the *final* design of the base, not an *intermediate* one again, in which important things have been left out, that I know I am going to have to do over again. I left that idea behind, when I decided it did not need to be perfect.

#### Principles & Aspects

Earlier, the principles that need to be present in the base code, were separated from the *aspects*, that might be programmed using the base code itself. But from a functional point of view it might not matter how much can be left out of the base code. How as much as possible may be left out of the base code, could be pondered about as the product may be further developed. The subjects might be grouped by functionality. The functionality, that needs to be present in the base code, might spread out all over the functional needs. From a functional point of view it might not really matter whether something is implemented as a plugged-in aspect or as an intrinsic language principle.