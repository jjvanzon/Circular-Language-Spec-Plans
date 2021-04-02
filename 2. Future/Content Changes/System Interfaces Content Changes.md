Encircle Language Spec Plans
============================

System Interfaces | Content Changes
-----------------------------------

The System Interfaces article group may need extensions in the future. It could be revisited to make complete the set of system aspects and system commands and cross out remaining ideas and topics.

Somewhere written down is the idea that Getters & Setters should be a sub-topic inside System Objects, but I am not sure why. It seems that is already covered by the content? Maybe just to compare it to getters and setters and how those look in Encircle Language, just in case there was any doubt.

### Getters & Setters Brainstorm

The system objects chapter might be looked over to see what the ideas about getters and setters were. The idea seemed that system commands were the replacement for getters and setters. This seems logical, because the system commands are the getters and setters, only they seem to always have the default implementation. If you want to define your own getter and setter code, you might define an override or implement the override event or implement the pre- or post-extension events. If you really want it to look like getters and setters, you might want the property, the object, to have system commands in them, inside of which you see the alternative implementation. That seems the solution.

To get a getter and setter experience, that is neater than overriding or implementing specialization events, you might want next to the normal representation of the object, to see part of the system representation in which the getter and setter system commands are visible, which have a custom implementation.

That seems to solve the problem.

### Postponed

#### 2020-05-18 Postponed Content Changes for System Objects Chapter

##### More Difficult Perhaps

- [ ] ~ Perhaps rename the System Objects chapter to System Interface. 
    - [ ] ~ It seems more indicative of something more prominently visible. I tend to refer these issue as 'system interface' issues.
    - [ ] ~ It seems to sort of get out of hand quickly when I do that rename. Instead of reformulating, I start thinking about changing the whole build up of things, which may be too much for now.
    - [ ] ~ The story, how it flows, does not seem to make sense when the title is 'System Interface'.
    - [ ] ~ I might want to revert this for now.
    - [ ] ~ If the title of the chapter might change from System Objects to System Interface, it might make sense to introduce that system interface is first, instead of leading with a story about System Objects and then introducing the System Interface sometimes.
    - [ ] ~ Something like: "The system interface is like opening up the internal workings of a symbol. < Something about what would be in the system interface. > Wondering what could be exposed through the system interface and how a symbol may work internally, seemed to lead to a systematic overview of things you might do with the language. The story almost seems like a design of a run-time: an implementation of the language, rather than
- [x] Maybe it can be solve easily, by introducing it as though it would run as a run-time,
- [ ] ~ but the idea of controlling system aspect is wider in use and can represent constructs from other languages too.
- [x] Or something. Maybe just put it into context. Or multiple contexts: 
- [ ] ~ can be a run-time, can be representation of system commands already part of the language. In a run-time the idea was that an object lives as sort of reflective data, so a reflection-first environment, where reflection data is not accessed through an API, but more like a readily available, language-intrinsic secondary representation of an object. Having full fledged self-reflective object live in a run-time
- [x] might not be the most optimal performance-wise, though quite
- [ ] ~ flexible perhaps.
- [x] An idea is to have the system interface be there if you need it, and optimized away if not needed or just be a view on it, not necessarily a non-optimal way of object representation in runtime. I am going too far with this now, I think. Too many edge-cases. Lots of ideas come to mind.
- [ ] ~ System Objects seem to lead to Assignment, Connectors and Connections, but one is sort of the internals, while the other is just basics of notation, so not sure to keep them intermixed like that.
- [ ] ~ I just keep thinking the chapter could be split into a neutral view on system aspects, leading to connections, connectors and assignment, and separating out the specific implementation, which I do not find uninteresting, but... it does not seem to be 'the language', it seems 'the runtime', which can expose itself through the system interface. It may even be demoted to Construct Drafts. It might be more than a draft, but... maybe for that reason put it in Broader View.
- [ ] ~ (Also about Pointers): The distinction between system interfaces for references and for objects might also be derived from the impression that in the object reference notation it may be implied what is the object and what is the reference. I feel uneasy that I seem to change opinion of what makes a symbol a reference. It is a story of subtleties that might lurk under the hood, that could be the subject of the Pointers chapter and may be better pretending the problem does not exist. I have multiple interpretations I sort of equally like, that might not even be in each other's way. It may just create an odd rule set of when something is a reference and when something is an object. If I keep comparing it with 'text code' I seem to find answers. How it works in text code, I feel there is often a parallel to be found in this diagram notation. If it is a reference or an object may also be 'weird' in C#, so Encircle might be excused for it too.
- [ ] ~ Elaborations on reasons might be moved to Encircle Broader View.

##### Less Difficult Perhaps

- [ ] ~ System Objects article: Maybe show a few examples of how objects might be distinguished from references? Not all, just a few. There is one more clearly denoted in the Assignment article: it attempts to state explicitly how references might be displayed and how objects might be.
- [ ] ~ Move Clone and Data aspects to elsewhere?
    - [ ] ~ The clone aspect might be a bit more alien. Perhaps move it out of the main story.
- [ ] ~ "The System Objects" section:
    - [ ] ~ The definition of *Symbol* also seems to try and make it black and white not to confuse possibly overlapping terminology. I guess it might be my search for black and white definitions and avoiding ambiguity, that lead me to want to keep everything separated from each other.
- [ ] ~ The __List__ aspect is also presented as something specific, while I might make it a generic aspect of an object, but that idea is sort of part of the separate language design issue "list concept more generic".
- [ ] ~ Name aspect notations might not be covered in all the articles and that might be nice.
- [ ] ~ I also like where you can open the system interface and it just shows a dashed circle to indicate the class. I like that for the item class of a list.
- [ ] ~ Alternative Clone notation as like a value assignment with a depth, might be something to put somewhere.

#### 2020-07-21 Postponed Content Changes for System Command Call Notations Article

- [ ] ~ Get Reference-Bound Class <= New <=
    - [ ] ~ Maybe this edge case might be left out. It seems to introduce something new, not the main point of the article. Keep it somewhere? Move it? To where?
- [ ] ~ I am weirded out a bit, that I used assignments for the value commands but just connections for the object commands.
    - [ ] ~ Value commands' arguments seem to need assignment notation to be an assignment compared to value correspondence, but object commands' arguments do not seem need an assignment notation because they are a connection. Yet I do indicate that e.g. Set Object would be called. There seems to be an asymmetry there that does not resonate well with me. Why would the connection to a parameter result in a system command call in one case (in case of object commands), but the connection to a parameter would not result in a system command call in the other case (in case of value commands). Did I at one point want to solve that by making value connections with direction be value assignments? Or is it something special with consulting parameters? I do not know, but I would like it to feel like it makes sense and is consistent. I was already in doubt whether a system command was actually the result of the connection to the parameter on the right. Maybe they are not? Then quite something seems to fall apart about the overview. I don't know. I'd like to solve it and make it clean.
    - [ ] ~ Connecting inward could mean an implicit get command call.
    - [ ] ~ Connecting values inward would that mean an implicit get command as well?
    - [ ] ~ Would inward connections imply assignment?
    - [ ] ~ I would imply a get.
    - [ ] ~ My thinking error might be, assuming a hard rule that get and set goes together into an assignment and that would be the only application of getters and setters. I think I may at one point have forgotten that there is also a Get for *member access* possible e.g. Object.MemberA.MemberB might triggers 2 or 3 getters, while not necessarily causing any setters to go off. Those might be the only 2 cases that cause getters other than explicit calling. It may seem that every time I assume a set of options is complete, I may be mistaken. If I assume the set is incomplete and relax the story so that it might not be a problem, could often be the solution for conveying these ideas. But once aware of a different case, it seems to gain importance in my mind and I would like to be a bit more specific about it. 'A bit' might not only be polite talking here. A bit would do perhaps, just being honest (to myself) that I might not have it all worked out could be enough. It may not make this idea any more or less relevant.

### Done

#### 2020-07-22 Done Prioritization for System Objects Chapter

- [x] Reflection:
    - [x] It seems trying to put content out of scope and a more clear-cut version in place, especially that second part, put quite a storm in my brain. Something I agreed was too much for me right now. It may have been collision of circumstances, that I wanted to take putting content out of scope a step further by replacing it with a different variation too, and secondly also the chapter might be one of the harder ones. In that process I seem to have forgotten what my focus was: tone change. My thoughts are still circling around topics now, that I had earlier chosen to leave untouched for now. I think to move focus to where I want, I might need to actively imprint in my mind to postpone topics and remind myself that postponing them is OK.
    - [x] What sort of went strictly according to plan was: I did replace the implicit notations with explicit ones.
    - [x] What went sort of wrong might be: Doubts about the systematics and their completeness and correctness seemed to have driven me into a brainstorm of unresolved details. I find there is not much wrong with that, if persistence leads to a well polished end-result, but some might also call it 'losing oneself in the details'. The effort that would come with that persistence is not estimated to be within my capacities right now. I sort of have to be gentle with myself.

- [x] Steps:
    - [x] Might re-evaluate if the content changes might be picked up or might be postponed.
    - [x] Doing tasks after prioritizing content changes.
    - [x] Steer focus back to tone change.

- [x] Strategy:
    - [x] Maybe postponing even more could perhaps make the transition back to the main focus quicker (and easier).
    - [x] Moving the whole chapter way further down might also exaggerate the situation, so not be tempted to stay fixated on this topic.

#### 2020-05-18 Done Content Changes for System Objects Chapter

- [x] Maybe rename "Object Get" to "Get Object".
    - [x] There may be some naming purism that might have slipped in, which might be sort of subjective. Would "Get Object" not read more easily instead of "Object Get"? Ease in conveying the idea might be a good argument to write it that way. Fortunately no choice is set in stone anymore, which seems a bit of relief, meaning: even if you would name it Object Get later for some reason, stating it differently now, would not stand the main idea in the way. I may not have been entirely conscious of that when I wrote it. I was looking for rules to hold on to in a perhaps complicated task. I get it. But the idea can relax now.
    - [x] Might do for whole chapter.
    - [x] But skipping the images?
    - [x] ~~Might not include the Encircle Construct Draft version?~~
    - [x] Done for System Objects article.
    - [x] Done for Assignment article.
    - [x] Done for System Command Call Notations article
    - [x] Might do for Connectors & Connections article.
    - [x] Might do for System Objects Misc Issues article.
    - [x] ~~Might be no occurrences in the List Concept article.~~
    - [x] ~~Might not do for the System Objects Ideas article.~~
- [x] Move the System Objects chapter further down in the chapters?
    - [x] Brainstorm:
    - [x] I seem to be in doubt about how parameters work now.
    - [x] So I have the feeling I am missing some basics. It may be better to describe them first.
    - [x] I seem to be regularly in doubt about when which system command is called and under which circumstances. Not only does the chapter not seem to describe all those things in detail, but also it seems too early for that in the story. And also the basics of the language do not seem to depend on this.
    - [x] I would like to see this through to an acceptable text for now (2020-07-22), and feel comfortable parking the content changes for later.
    - [x] I may be saying this, because I deep dived into this topic, but this seems one of the more difficult topics.
    - [x] It went from sort of a fun way to notate object oriented concepts into diagrams, to an abstract, difficult, precise, specialistic view, the specifics of which seem to be missing something and of which the correctness seems difficult to verify for me right now.
    - [x] And probably because of this insecurity, it is just difficult for me.
    - [x] I went beyond scope of changing the tone of the text, because I really wanted some of the notation constructs put out of scope, that I have second thoughts about.

#### 2020-07-21 Done Content Changes for System Command Call Notations Article

- [x] Assignment direction might be reversed in the section "Explicit Get & Set Argument Notation". > Checked both Encircle Language Spec and Encircle Construct Drafts.
- [x] Add a sentence? The "Explicit Get & Set" section goes into notations of the New and Add commands as well, even though the title of the section may not say it. Change the title? Or excuse it in the content?

#### 2020-07-21 Done Content Changes for System Command Call Notations Article

- [x] Making structural overviews with explicit notations rather than implicit ones:
- [x] I seem to have just finished "System Interface Calls with Arguments" section: 
- [x] I think what I did next is draw pictures for the "Explicit Get & Set" section.
- [x] I might have scanned the pictures. Or have them just on paper. I could check.
- [x] I seem to not have scanned them yet.
- [x] Might cut and paste images from the paper scans into the "Explicit Get & Set" section.
- [x] I might go to a next step, which might be adding the next section, based on the original text, but then changed to the currently preferred notation.
- [x] I seem to be missing the original pictures in the original notation of Explicit Get & Set (with Arguments). Did I remove them, or did they never exist? I think I accidentally removed them and did not keep them in Encircle Construct Drafts. I might look in the source control history trying to get them back for sort of archival purposes.
- [x] Found part of it in a previous version of... going back in history on the main doc, might lead to the actual original instead of an already altered one.
- [x] It seems there was no systematic overview of any system interface call with explicit arguments in the version before. So I sort of went on a ghost hunt.
- [x] Might there be things I want to polish up about the Encircle Construct Drafts version up until the "Explicit Argument Notation"?
- [x] There are some 'orange' markings left for extensions with more content, but I might not are much about that currently, because I chose to focus on Encircle Language Spec and leave Encircle Construct Drafts in a bit of a 'drafty' state if I must.
- [x] Clone in the "Explicit Get & Set" section seems to be missing its depth arguments.
- [x] Explicitly drawn out assignment command:
    - [x] Made scaffolding to be finished up.
    - [x] The next appropriate section to do seems to be the one where I extrapolate the assignment notation step by step towards explicit display of what goes on inside it. I sort of promised myself to not go as far as to artificially prove that the explicit notation is no good. I would like to go from assignment notation to explicit argument notation inside an execution 'diamond' of the assignment call. But no further.
    - [x] An explicitly drawn out assignment command might be interesting, but then maybe not go as far as to make it as rich as possible in an attempt to exaggerate that it is impractical, but instead maybe the most simple notation of the explicit notations, to be honest about what is being done.
    - [x] Maybe not many steps are needed. I think: a) an (object) assignment b) an explicit get and set call c) an explicit get and set call inside an assignment execution.
    - [x] The Get Object and Set Object calls displayed in System Interface Call with Argument notation sort of miss the parent around the object reference used in the argument. I do not know yet how I feel about it. It seems OK notation, perhaps even bad to put a parent around it, because it might suggest an extra access call, but I did sort of promise to use the 'has a parent' notation when something is might be a reference-bound aspect... It's just that it seems to look odd when comparing notations. Not sure yet.
- [x] I may want to read over the article "Connectors & Connections" and see how the implicit notations relate to it. A quick scan lead me to this reasoning: Some connect*ors* seem just an indication of what a connect*ion* looks like. It is introduced as an alternative of displaying a system command in the system interface, and also some connectors seem to derive from the implicit notations, which might be OK with explicit system interface notation instead.
- [x] I might want to steer back to evaluating what consistent, explicit alternatives might be for practically used situations for which an implicit notation is introduced. 
- [x] I think I want to move the whole article to Construct Drafts, then build up an alternative article containing only the notations left that I might want to introduce as part of this language spec.

#### 2020-05-18 Done Content Changes for System Command Call Notations Article

- [x] I actually feel uneasy about the notations introduced there at all. I want to try and avoid exaggeration, but this seems like a opening a flood gate to ambiguity. But that is not the question at hand.
- [x] My main concern currently is whether basically any of the implicit notations other than the assignment notation are something I would enjoy keeping.
- [x] My main 'objection': I do not feel that this would be an objection anymore: "Then remains the question whether to show the other members of the system interface as well, or only to show the members of the system interface, that are actually called." Either option seems ok to me, and I think it could be practically managed when to display which.
- [x] The 'end result' would make system command calls look quite like assignment notation.
- [x] My objection to the notation now might be to not introduce implicit slightly ambiguous notation for something not used very often (never?) that already seems to have an alternative notation, that is not ambiguous, consistent and adequate.
- [x] The notation is indeed nicely consistent with the assignment notation. Even better now, I guess, consistent with the flipped use of access marks to indicate direction?
- [x] I seemed to build in less wiggle room before in my writing. The text says: "Most of the notations above will never be used." Ok, so I did say 'most' which is not a definite. Some of them would be used.
- [x] The text does seem to neatly lay out the use cases, where this implicit notation might be used.
- [x] I might want to draw those use cases out with system interface notation. Then evaluate whether I am content with system interface notation and could do without the introduced implicit notations.
- [x] Options are a bit dizzying for me now.
- [x] I have some doubt, but I think I do not have to have that doubt. I scanned over the topics. I think moving this construct out will be OK. After I drew the 'alternative' notation in the system interface.
- [x] Drawing explicit notations for many implicit notations mentioned.
- [x] The New, Add and Remove commands might be explicitly called unlike Get, Set and Use commands, which can be implied by assignment notation, so I might evaluate if those could use an implicit notation, or look good enough to me using system interface notation.
- [x] Flattening the aspect triangles to a flat list of commands might make system interface notation a bit more practical. > Say in the article that you go for that design choice and show flexibility of choices in this language.

#### 2020-07-01 Done Content Changes for System Objects Chapter

- [x] The chapter starts as if it is a run-time.
- [x] "if Encircle would function more like a stand-alone language, rather than mostly a diagram notation"
- [x] The Related Items and Related Lists collections inside the System Interface might be handy for reflective/aspect oriented/relational model logic. But in essence you might only need one collection of 'sub-objects' (that term might questionable). Possibly, certain characteristics that a sub-object might have could turn it into a Related Item, Related List or perhaps even an Attribute. And commands, etc. There may be one 'bag' of sub-items, while you may query for ones with certain characteristics. A set of those queries could be: Commands, Items, Lists or Attributes. But at least 2 times now I guess I changed my mind about the subdivision of those 'queries'. It looks like the .NET Type type with its members like Properties, Methods, etc.? That parallel feels nice. These might even be framework extensions. I wonder how to present this. Presenting alternatives. Leaving in this design choice or changing it? It should maybe be one of the use cases of the system interfaces. I think those might deserve mentioning. That this reflective data might be used for software design based on a relational model if you just see it as Related Lists and Related Items, that might be nice. But due to the detailed construct subdivisions that commands might cause, the view on the relational design might be lost if you do not put some sort of filter over it, that excludes maybe anything going on inside a command. These are just options. I would like to explore them. I am not sure if this would make the text unnecessarily long. Let's just see.
- [x] I think I like the way the specific approach might shed light on flexibilities, because it could mean openness to alternative ideas, at the same time expressing that other variations are also possible too. Even though things in System Objects might seem specific implementation issues, I tend to want to keep all of that in there, because it seems a nice demonstration of how things might be (on a deeper level?)
- [x] In the System Object article, there seems prominence of the 1 and n multiplicity concepts, that might only be interesting once you start talking about relationships or reflection or aspect oriented programming.
- [x] Rename?
    - [x] "Reference-Class Get" to "Reference-Bound Class Get"
    - [x] "Object-Class Get" to "Object-Bound Class Get"
    - [x] The reason is that the terminology seems to get dizzying and confusing. For instance sort of clashing visually with terms like "Class Redirection" and "Class Reference" (already sort of ambiguous).
- [x] I frequently have the opinion that some texts may have design choices not necessarily relevant to the notation design, that are presented as hard rules, while I could perhaps think of a few alternatives from the top of my head. Just admitting it is not set in stone might help. / (Perhaps leaving base code design / the design of a run time out of the story somehow, might help? I am not sure.) The example that is given might help, because it might give pointers towards various things you might use a system interface for, ideas that might otherwise not be considered, and perhaps relevant to the purpose in mind with system interfaces. Something that could be considered, though, is to then not try to design a perfect base code in writing, but to make some things simpler on purpose, since this seems for demonstration purposes, rather than to formulate a fixed set of rules anymore.
- [x] Clone (2) seems a practical variation on the value aspect, because the case where there is a parent object, whose child objects are values or reference and those elements together might need a copy ('MemberwiseClone'). The value aspect might only copy a parent object's value, which it might not even have, just through its sub-objects/child value objects. But the depth parameter might be a bit creative. I think expressing this use case (maybe a bit more concisely than above), might help appreciate that the idea is proposed.
- [x] The Execute aspect might be more generically applicable. In the section "Execute Aspect in the System Interface" I might say any object in Encircle might become executable, instead of fixating on an object's definitely being a command or not.
- [x] "The System Objects" section:
    - [x] I find terminology introduced dubious and ambiguous. For instance: related item would be a pointer, related object would be an undecorated object pointer: what would the difference be? The Related Item makes the connection with its parent. But how does the term Related Item even mean that? I just seemed to have picked some words and assign meaning to it. I think maybe the meaning of the terms could be kept pure. I might not need to abuse the term 'Related Item' in order to define that a parent object manages the relationships with its related objects. Item and object are almost synonymous, but as I translate that to terms related item and related object, all of a sudden they change meaning? Nah, not a great plan perhaps. I just wonder then: How am I supposed to present it then? They do seem clearly distinct concepts, just not clearly distinct terminology. This might be an age old problem in computer programming: finding good names. Basically the concept of 'wrapping a pointer' may need a name. Maybe Related Item wraps a Reference or is that abusing terminology again? Maybe not if you do not try to define a term but just say the concept the parent manages the connection to the related item, and that a Related Item might wrap a reference to the related object.
    - [x] Could I just pick a term and then say: these are all basically synonyms?
    - [x] That items in the related lists collection should be circles, well, maybe they might be nonagons instead. But I might keep it how it is now: circles. It might fall under the language design issue of "List concept more generic".
- [x] Remove the section "Overview of System Commands for the Class Aspect"?
- [x] ~~If value assignment is in assignment notation, then the notation for value connection with an access mark might be open for use for something else. If I make it the same as the basics of other parts of the language, this could mean something like a pointer to a value? Not sure if this is a useful concept.~~
- [x] Are connector notations consistent with the assignment / reference direction changes? It would be nice if it were. Then 'everything is the same'. > I think it is now.

#### 2020-06-26 Done Brainstorm Next Step

Up next might be the System Objects chapter. That one is rather large: 67 pages. I wonder if I am up for it. Maybe I would want to skip it and do another one first? Commands is larger 79 pages. Hmmm... and its content seems if-and-or-but'y. Parameters is 18 pages, some of which is material I think I want to change the idea of. At one point I would like to go from one topic to the next more sequentially. I think maybe just accept that there's quite some content. I think I am just going to start with the first article of the System Objects chapter.

I had checklists for changing the wording. I seem to also wander off that topic to try and fix content. Usually because then I might have less words to reformulate. Scoping might put things at a side line, which helps get through the stuff to do.
