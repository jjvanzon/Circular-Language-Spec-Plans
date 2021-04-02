Encircle Language Spec Plans
============================

Fully OO? (Is It?) | Language Design
------------------------------------

### 2020-05-12 Postponed Fully OO?

- [ ] ~ Topics that the spec might be extended with, to make it more 'fully OO':
- [ ] ~ Here and there I mention that the diagram notation could 'fully describe' an OO system. But I do not mention that it stops at arithmetic, comparative, logical operators and such. You might display that as an object graph. An idea was that 'Math' would be an external module that describes all the basic operators, but another idea was for expressions like that could be just included as bits of text code inside the diagram. Maybe not be too strict about this towards myself.
- [ ] ~ Also when I look at Encircle Construct Drafts, I see topics one might expect in a language spec, that are not addressed. I guess it does not have to have everything any other language spec might have...
- [ ] ~ The "Summaries of Other Languages" lists constructs, that I might have deemed 'obvious' how to express them in Encircle, but that might not be the case: enums, structs, union types, other sorts of types, all sorts of operators, all the modifiers. If it turns out explainable under one umbrella, maybe one article would suffice. Maybe called "Imported Constructs" but perhaps that name would demote these constructs too much?
- [ ] ~ I have some notations in mind for 'operators' which may cover a portion of the constructs in the "Sumarries of Other Languages":
    - [ ] Drawing out operators and operands as function calls with the command and paramater notation of Encircle.
    - [ ] Writing down the expression as text (for instance "X < Y" inside a diamond maybe.
    - [ ] Using a commands and parameters notation of Encircle, also try to write the expression almost as text "X < Y" but then the X and Y operands perhaps replaced by a shape (circle or 'cookie' shape) with the name in or near the shapes, or perhaps no names at all, just circle's that redirect to the wanted value.
    - [ ] Perhaps try to make an attempt to an exhaustive table, even when that might mean repeating the same sort of notation multiple times. It might clarify where there might be doubt.
- [ ] Some C or C++ keywords I might not have a specific replacement for. Is there a kind of catch all solution for that?
    - [ ] For instance ones I do not know the meaning of.
    - [ ] One example might be distinction between C# `out` parameters and `return` values might not have a distict diagram notation.
    - [ ] May also be an option if an application may decide not to implement certain graphical notations, but still may want to display the information in the diagram.
    - [ ] Perhaps just notate the keyword / modifiers from C or C++ (or another language) near the associated shape (along with the name of the shape).
    - [ ] Perhaps some keywords might be notated in 'Condition' notation ('Condition' notation may not have been worked out yet).
    - [ ] The option to simply leave out those details from the diagram might do for some applications.