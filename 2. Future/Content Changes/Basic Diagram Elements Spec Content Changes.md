Encircle Language Spec Plans
============================

Basic Diagram Elements Spec | Content Changes
---------------------------------------------

### Postponed

#### 2020-06-01 Postponed Content Changes for Basic Diagram Elements

- [ ] ~ 'Connecting Command Symbols' stories may be a bit long?
- [ ] ~ Maybe there are so many rules in there, because of the idea that this would become the base for a patent? Patenting is sort of off the table now.
- [ ] ~ Some things might be implementation details, movable to the Encircle Construct Draft part?
- [ ] ~ Certain rules might change and simplify, but that might not be for now.
- [ ] ~ Outtakes:
    - [ ] ~ Lines do have a direction, going from one symbol to the next, which will be explained later.
    - [ ] ~ The access marks are sort of embedded into the language as it is right now. But these are all just a collection ideas, all just suggestions. A changed approach might not make things fall apart.
    - [ ] ~ A line never gets a name. They are always called, for instance: ‘the object line of symbol B’.
    - [ ] ~ Any object symbol might symbolize an object, a class or an interface. 
        > ![](images/2019-08%20Circle%20Language%20Spec%20Revamp%20Notes.009.png)
        > ![](images/2019-08%20Circle%20Language%20Spec%20Revamp%20Notes.010.png)
        > ![](images/2019-08%20Circle%20Language%20Spec%20Revamp%20Notes.011.png)
        > ![](images/2019-08%20Circle%20Language%20Spec%20Revamp%20Notes.012.png)
        
        Each object might serve as another object’s class, sort of functioning as its prototype. Any object might also provide the interface for another object, which may give another object the same exterior, while it might be different on the inside.
- [ ] ~ Add a picture around 'Object Structure Solid, Class Structure Dashed', to demonstrate how things would look?
- [ ] ~ Privacy issues in the paper scans?
- [ ] ~ 'Object Symbols Drawn with Different Lines' starts with some information that may have been repeated more than once already before? Is there additional value to that, or might it just be removed or something?
- [ ] ~ What might be a little odd, is that I spring the terms object, class and interface upon the reader in one of the first parts where I show the circle and triangle, but an arguably clear definition of these terms (though optional: these should be common IT terms) only later appears. Maybe it is an idea to move that clear definition more upwards. I tend to repeat the definitions, which may have some value. It might have the appearance that they are important, because of all that repetition, but it may make less sense that I do not just have one of those repetitions straight away where they are introduced.
- [ ] ~ Question: What might be the purpose or scope of this Basic Diagram Elements article? Is it supposed to be a comprehensive overview of pretty much all the elements? Or the basic ones, to maybe get a good impression of this language formally? Because I think maybe I am missing some notation details. If made more complete, would it be almost a full summary of like all of it? I might be missing event notation, comments, system interface, I do not cover all the black boxing access marks, I also do not see assignment notation, etc. But maybe that is not the point: to be complete. But maybe a few key ones are missing, is my own personal feeling. Events, commends and a few access marks. Those maybe. Comment notation is not even described anywhere. Hmm. In that light it seems a bit arbitrary that I do show that line merge and symbol merge notation, which might possibly be deprecated at some point.
- [ ] ~ Should I introduce a reference to parent notation in the Basic Diagram Elements chapter?

![](images/2019-08%20Circle%20Language%20Spec%20Revamp%20Notes.013.png)

(minus the wiggly line)

- [ ] ~ Extra rules for line drawing / access marks:
    - [ ] ~ Drawing more diagrams on paper I remember why I invented the rule 'access mark not needed when connection from diamond to square is implied' and the other rule too: 'call lines can be solid'. They might make the language less 'pure', but they do forgive a 'mistake' you might make forgetting the access mark and that the line might be dashed between a diamond and a square: you almost always mean that when you draw a diamond and a square. I may reintroduce those 'rules', but then also express the doubt about them honestly. "Not a hard rule", "might make the language less pure", "might be forgiven if you use it that way", "could be used as a dialect that way", "might keep it purer and use dashed lines and access marks".
- [ ] ~ The part about how symbols can relate:
    - [ ] ~Adding 'child' association
        - [ ] ~ For instance if an object __O__'s class __C__ defines a member __A__, and member __A__ has a certain class, this may mean that member __A__ in object __O__ has that class too, even when no line indicates that. The class's definition might define the configuration of the members of the object, without repeating that information in the object.
    - [ ] ~ Adding 'name' association: 
        - [ ] ~ If just text code might be inserted into the diagram, perhaps without specifying any shape or lines e.g. "A < B", the association might go by name. Perhaps similar like in text code. Perhaps with disambiguation rules like in text code (e.g. command overloads).
    - [ ] ~ Adding 'shape' association:
        - [ ] ~ Perhaps a bit questionable. Without specifying class or interface or anything, objects might 'accidentally' have similar shape. It might visually make objects look similar. This may be a certain unwritten relation betwee those two objects.
        - [ ] ~ Perhaps an association like that might lead to something along the idea of "Automatic Object Formation" that seems to be hiding the "Broader View" section perhaps without much of a description.
        - [ ] ~ Perhaps disambiguation of commands based on parameter types might be an example of this.

### Done

#### 2020-06-01 Done Content Changes for Basic Diagram Elements

- [x] Maybe replace the word 'module' by 'module'. I seem to keep running into it.
- [x] In the access marks sections, maybe add a picture of how it would look if it is connected to a symbol. That might not be that clear. You might not see the context there. You might just see a sort of kite like drawing.
- [x] Some content changes:
    - [x] Is it nice to present the reasons for the shapes, or is it just superfluous text?
    - [x] I do not know. The back story may show creativity, which might be nice. It may inspire the imagination of others. But more reasoning may be overwhelming so I am torn between arguments here. More text might not necessarily be bad. I like describing how I came to these choices, sort of artistic choices.
    - [x] It might give it feeling. More humanization.
    - [x] I think the dashed square with the big red cross through it, might be a bit harshly expressed. Maybe the *curl* with the solid square might also be left out. There might not be much reason to emphasize things so much.
    - [x] I still have doubts about explaining the reason behind the shapes. It may just obscure things. It may be text for 'Encircle Broader View' instead.
- [x] Maybe the object reference notation (the eye to another symbol) deserves specific mentioning. It is there under' Lines Pointing Outwards', but there is no specific highlighting of this notational issue. I feel it was sort of the aha moment that started my ideas about this possible notation flowing, so maybe nice to articulate. (There seem to be 2 interpretations of object reference. The eye notation may have one symbol be the object and the other be an object reference. But in another interpretation all the symbols are mere object references, and the lines just indicate correspondence of the aspect, that both symbols point to the same object.)
- [x] 2x almost the same picture under 'Access Symbol Placement'.