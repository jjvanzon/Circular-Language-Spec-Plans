Encircle Language Spec Revamp Notes 2019-08
===========================================

Contents
--------

- [Project Outline](#project-outline)
    - [Introduction](#introduction)
    - [Goals](#goals)
    - [Steps](#steps)
    - [Language Design / Content Changes](#language-design--content-changes)
    - [Scope](#scope)
    - [Strategy](#strategy)
    - [Information](#information)
- [TODO](#todo)
    - [Rough Content Reorganization](#rough-content-reorganization)
    - [Scoping](#scoping)
    - [Tone Change | in General](#tone-change--in-general)
    - [Planning | in General](#planning--in-general)
- [Postponed](#postponed-2)
    - [Commands | Tone Change](#commands--tone-change)
    - [System Objects | Tone Change](#system-objects--tone-change)
    - [Planning Docs | Tone Change](#planning-docs--tone-change)
- [Done](#done-7)
    - [Search Tools](#search-tools)
    - [Planning Docs | Content Changes](#planning-docs--content-changes)
    - [Classes | Tone Change](#classes--tone-change)
    - [Assignment | Tone Change](#assignment--tone-change)


Project Outline
---------------

### Introduction

*Encircle* is an unfinished programming language.

I spent quite a portion of my 20's spare time thinking about this idea of how to visually express the internals of computers and programming languages.

*Encircle Language Spec* tries to describe it.

### Strategy

- When changing a topic's *tone*, perhaps consider *content changes* too.

### Steps

- [x] Reorientation
    - [x] Reading Planning Docs sequentially.
- [x] Scoping
    - [x] Splitting "Software System" / "Encircle Language"
    - [x] Splitting "Encircle Docs" / "Circle 3 Programming" (splitting documentation goals from programming goals.)
        - [x] Ideas.doc too
    - [x] Splitting 'in scope' / 'out of scope' for Encircle Language topics.
    - [x] Splitting up 'phases in life' in planning docs.
    - [x] Removed studying goals.
    - [ ] ... Splitting up "Language Spec" / "Broader View" / "Construct Drafts"
        - [x] Encircle-Language-Spec repository
        - [ ] ~ Encircle-Language-Spec-Plans repository
- [x] Rough content reorganization
    - [ ] __Reorganizing Planning Docs__
    - [x] Reorganizing "Encircle Docs" roughly
    - [x] Reorganizing "Spec" roughly
    - [x] Reorganizing "Broader View" roughly
    - [x] Reorganizing "Construct Drafts" roughly
    - [x] Moving topics out of "Spec"
- [ ] .. Milder tone
    - [ ] .. Less resolute language, more wiggle room
    - [ ] .. (Perhaps search for definites such as 'have to', 'must', 'will', 'should', 'very'.)
    - [ ] .. (Maybe I am being too strict towards myself, about having to rewrite everything in a milder tone.)
- [ ] ~ Including hour sheet
    - [ ] ~ (Extracting from hour sheet about multiple projects)
- [ ] ~ Improving Planning Docs:
    - [ ] ~ Splitting "Encircle Language Spec Revamp Notes" into a document per topic.
- [ ] ~ Improving Encircle Language Spec:
    - [x] Reduce the number of articles, grouping topics together.
    - [x] Turn separate Concept / Diagram / Text Code articles into one.
    - [ ] .. Loose ideas (regroup or clear out)
    - [ ] ~ Start reading / writing / reformulating.
    - [ ] ~ Generally go through content reformulating things?
    - [ ] ~ Reorganizing articles
    - [ ] ~ Language design issues
    - [ ] ~ Correcting for new insight / decisions

### Language Design / Content Changes

- [ ] Writing style:
    - [ ] More pictures
    - [ ] More open, less resolute language
    - [ ] Use common IT terms
    - [ ] Write unfinished articles
    - [ ] Is it a *notation* or is it a *run-time*?
        - [ ] (Texts might insist that Encircle is a run-time, while the notation might be the main point of things.)
    - [ ] Over-awareness of pointers?

### Information

- Tools:
    - Thesaurus: <https://www.thesaurus.com/>
    - Google Translate: <https://translate.google.com/>


TODO
----

### Rough Content Reorganization

#### TODO

##### 2021-03-30 TODO Rough Content Reorganization

- [ ] .. Merging together goals of Revamp project with Main Project.
    - [ ] Encircle Language Spec Strategy
        - [x] Reformulating Main Project "Goals" sections.
        - [x] Reformulating Main Project "Theme Picking" section.
        - [x] Reformulating Main Project "Productive Writing" section.
        - [x] Perhaps do not describe goals *once had* but *never reached*.
        - [x] Perhaps better describe what *happened* and goals *now*.
        - [x] *Time planning* issues may not be appropriate anymore.
        - [x] I cannot do *efficient* anymore.
        - [ ] Perhaps read over again later.
    - [ ] .. Encircle Language Spec Products List
        - [ ] .. Might build up a new list.
        - [ ] And go over old list items and cross them out.
    - [ ] Encircle Language Spec Steps & Time Planning
- [ ] __Separating sub-project docs for more general things__
    - [ ] From Encircle Language Spec Revamp Notes into more specific docs.
    - [ ] like Tone Change, Source Control Migration, etc.

#### Postponed

##### 2021-03-23 Postponed Rough Content Reorganization

- [ ] Planning docs: Removing (totally) out-of-scope topics to Archive.
- [ ] Contents sections in documents?
- [ ] ~ Moves to "Implementations"
- [ ] All pointer topics to Pointers.
- [ ] All Text Code topics to single place.
- [ ] Replacing the name: "new computer language" with "Encircle programming language" or "Encircle".
- [ ] Switching "Parameters" approach between "Spec" and "Construct Drafts" replacing the "Commands & Classes Loosely Coupled" approach with the "Input Output" approach.
- [ ] ~ Splitting up Black Box Construct Drafts (they seem disparate topics)
- [ ] ->.. Replacing "Concept" with "Aspect"
    - [ ] I have difficulty with this. 
    - [ ] Only part of the occurrences seem replaceable.
    - [ ] "Concept" had such a nice ring to it.
    - [ ] Maybe some other way to be selective?
    - [ ] Certain files perhaps?
- [ ] ~ Reorganizing "Fundamental Principles"
    - [ ] ~ One doc for Exchangeability?
    - [ ] ~ One doc for Extensibility?

##### 2020-05-14 Postponed Encircle Broader View / Construct Drafts Neater Folders

- Making folder sub-division neater of "Framework" (inside Software-System-Docs), now that the topics have found a new place. 

#### Done

##### 2021-03-23 Done Rough Content Reorganization

- [x] Updating headings to reflect new folder organization.
- [x] Moved images (after the folder organization changes).
- [x] Spreading content of "Implementation Attempt 2002": Some to "Text Code", some to "Optimization".
- [x] Moves from "Construct Drafts" to "Broader View":
    - [x] "Commands & Classes Loosely Coupled"
    - [x] "Multiple Language Layers"
    - [x] "Object Storage"
- [x] ~~Spreading "Old Or Boring" topics over the documents. > Cannot find it anymore.~~
- [x] Correcting links from Plans repo's Readme to Spec repo.
- [x] Planning docs: Splitting up Revamp project into topics.
    - [x] Some work might be Done project, bot others might be half Done, half TODO, which might make it a Current project. Perhaps Moving Done, TODO and Postponed together under a topic might create overview to see the distiction, before spreading things over multiple documents.

##### 2021-03-14 Done Rough Content Reorganization

- [x] Moves from "Spec" to "Construct Drafts":
    - [x] "Previous Versions"
    - [x] "Summaries of Other Languages"
- [x] Make folder subdivision neater, now that the topics have found a new place. 
    - [x] "Encircle Language Spec"
    - [x] "Encircle Constructs Drafts"
    - [x] "Encircle Broader View"
- [x] Spec contents page (with links)
    - [x] Removing links to folders (confusing).
- [x] 'Webby paths' / 'pretty URL's' (shallow paths, lower-case, dashes, no spaces)
- [x] Moving System Objects more to the top again.
- [x] Calling "Ideas" "Loose Ideas".
- [x] Adding things like:
    - [x] `[ Deprecated documentation ]`
    - [x] `[ Preliminary documentation ]`
    - [x] `[ Out of scope ]`
- [x] index pages:
    - [x] Creating / updating.
    - [x] One in each folder.
    - [x] Also might move sub-folder descriptions from more general index pages to more specific ones.
    - [x] (Relative) links in all index pages
- [x] Removing "Version History" documents from Archive?
- [x] Replacing "Globality" with "Module"
- [x] "From Spec" sub-folders in "Construct Drafts" and "Broader View"
- [x] Split "Fundamental Principles Overview" over "Exchangeability", "Extensibility" and "Achievability".
- [x] Merging together "Flat and Structured Interchange" documents.

##### 2020-05-24 Done Merge More Articles

- [x] More articles from the first chapters might be merged together.
- [x] Structure changes:
    - [x] Making back ground black?
    - [x] Changing main headers?
    - [x] ~~Removing the footers?~~
    - [x] ~~Removing 'see also' references?~~
    - [x] Convert to docx.
    - [x] Merging or redistributing articles?
- [x] Chapters
    - [x] Objects
    - [x] Classes
    - [x] Relationships
    - [x] System Objects
    - [x] Commands

##### 2020-05-27 Done Merging More Commands Articles Together

- [x] Redirection and recursion seem to have some overlap conceptually.
- [x] Maybe "05. Comparison to CPU-Like Calls belongs in 04. Creation Behavior Of Commands."
- [x] "01. Commands Main Concepts > Larger" > Keep separate
- [x] "02. Start & Stop > Larger" > Keep separate
- [x] "03. Parent Controls Its Sub-Executions" > Medium sized > Misc-ish
- [x] "04. Creation Behavior Of Commands" > Larger
- [x] "05. Comparison to CPU-Like Calls" > Medium sized > Might group into Creation Behavior Of Commands
- [x] "06. Command Redirection" > Medium sized
- [x] "07. Recursion" > Medium sized / smallish > Might group into Command Redirection.
- [x] "08. Command Referrers" > Smaller > Misc-ish
- [x] "09. Commands Example Diagrams" > Larger > Keep separate
- [x] "10. Commands Ideas" > Larger > Keep separate
- [x] "11. This (unfinished)" > Smaller > Misc-ish

##### 2020-05-26 Done Merging More System Objects Articles Together

- [x] Last time it seems I only merged together a few large groups of articles into their main topic.
- [x] Right now I feel maybe the first 5 could be merged into one.
- [x] Along with some main topics, I feel there are loose topics. Maybe those loose topics could be grouped together with something.
- [x] I think Connectors and Connections is something I might want to combine into one article.
- [x] Assignment I would like to keep separate for now.
- [x] System Command Call Notations too. It's kind of large and honestly a bit questionable, so I would like to keep that separate.
- [x] I am thinking the remaining 4 relatively small articles, might be combined into a System Objects Misc article.
- [x] "01. System Objects" > Larger > Keep separate
- [x] "02. Assignment" > Medium sized > Keep separate
- [x] "03. System Command Call Notations" > Larger > Keep separate
- [x] "04. Connectors" > Smaller > Combined into Connectors & Connections.
- [x] "05. Connections" > Medium sized > Combined into Connectors & Connections.
- [x] "06. System Command Calls by User" > Small > Put into single article System Objects Misc Issues.
- [x] "07. Objects Floating Around" > Small > Put into single article System Objects Misc Issues.
- [x] "08. System Command Extension" > Small > Put into single article System Objects Misc Issues.
- [x] "09. Parameters For Objects" > Medium sized > Put into single article System Objects Misc Issues.
- [x] "10. List Concept" > Medium sized > Keep separate
- [x] "11. System Objects Ideas" > Larger > Keep separate

##### 2020-05-25 Done Merging More Relationships Articles Together

I feel merging the articles together is not something I necessarily want to do right now. I am not sure why those two things are connected to each other in my view.

I guess I feel I might want to polish up the way I explain things, before I put effort into merging the articles together at all? Are the articles not particularly small, like some of the articles I merged together before?

Some articles are smallish or sort of medium sized. I think I could just make it one article. That may make it more manageable the way I would like. I do not see my not entirely agreeing with the concept anymore as standing in the way of that.

Still want to change the fonts.

##### 2020-05-16 Done Formatting and Article Merging and Distributing

- [x] ~~Maybe put Type Control out of scope? > Deemed less important to consider right now.~~
- [x] So, what's next?
- [x] I think nothing to reorganize anymore about the file structure of Encircle Language Spec.
- [x] Maybe start with the texts?
- [x] ~~Option: Convert to docx. > Too many docs.~~
- [x] Option: If there are still Text Code topics, they might be moved to Encircle Construct Drafts.
- [x] Structure changes:
    - [x] Making back ground black?
    - [x] Changing main headers?
    - [x] Removing the footers?
    - [x] Removing 'see also' references?
    - [x] Convert to docx.
    - [x] Merging or redistributing articles?
    - [x] Putting each conceptual and diagram explanation together in an article.
- [x] Chapters:
    - [x] Encircle Language Spec Overview
    - [x] Basic Diagram Elements
    - [x] Objects
    - [x] Classes
    - [x] Relationships
    - [x] System Objects
    - [x] Commands
    - [x] Parameters
    - [x] Module
    - [x] Execution Control
    - [x] Black Boxing
    - [x] Interfaces
    - [x] Events
    - [x] Inheritance
    - [x] > The next are 26 documents total. I might do formatting for all of them in one go. None of the folders seem to have large sets of articles anymore.
    - [x] Type Control
    - [x] Object Resolution
    - [x] Conditions
    - [x] Object Order
    - [x] Uncategorized
    - [x] Other Diagram Topics
    - [x] Summaries of Other Languages
    - [x] Previous Versions

##### 2020-05-24 Done Merging and Redistributing Remaining Articles

Maybe going into detail about this is not part of the editing phase I am putting these articles through.
This is what the Encircle Language Spec Overview calls the 'unfinished' part. So for that reason it seems less straight forward.
It is also harder to subdivide, because it is multiple different issues, unlike previous tasks I did, which were just about 1 main topic.
The question I have for myself is how much is worth doing with regards to these topics.
Some things I'd like to do.
But I might want to be selective about it.

- [x] ~~"Type Safety, Genericity, Explicit"~~
    - [x] Already 1 article. The topic seems to deserve its own spot.
- [x] ~~"21. Object Resolution"~~
    - [x] Seems all of the articles might be put in one article, because I estimate these are not big issues separately.
    - [x] A lot of the text is preliminary.
    - [x] I do see this as being appropriate as a separate chapter, I think.
    - [x] I do not see much of a reason to put effort into this right now.
    - [x] It's kind of messy and when putting it into one article now, I may lose the overview that the split up into articles gives me now.
- [x] ~~Conditions~~
    - [x] These 3 articles could become 1.
    - [x] It seems that if content is still messy, the split up into multiple articles might have value, because it seems to create overview.
    - [x] Just added some comment on other content about Conditions to find elsewhere.
- [x] "23. Object Order"
    - [x] Is one article.
    - [x] But not a big one.
    - [x] Makes me wonder if some topics are handy as a separate chapter or better grouped into another main topic.
    - [x] Eventually might move to the Objects chapter, but will keep it in its own folder for now.
- [x] "This"
    - [x] I think I already had a place in mind for that, to move this article to a different main topic. I think tso Commands, but I think I put that down in the planning doc Encircle Language Spec Product List.
    - [x] Encircle Language Spec Product List says that it should belong in the Commands chapter.
- [x] "Redirection"
    - [x] Encircle Language Spec Product List does not seem to assign a specific existing Chapter to it. It says 'ref-ness'? Maybe that pointer to pointer situations might all be put in a separate chapter, this might also belong there?
    - [x] It talks about 'target symbols'.
    - [x] There are several target symbol topics in e.g. the chapters Objects, Classes and Interfaces.
    - [x] Maybe that can all go to a chapter about ref-ness, or whatever generic term I might find for it.
    - [x] If it is just about target symbols, maybe the topics are already covered by the previous content.
    - [x] It does seem to be about redirecting e.g. the object aspect and then about tracing to the final target object/class/interface after following the redirections.
    - [x] I do like the idea of a Pointers chapter or something.
    - [x] This content does seem to be covered elsewhere.
    - [x] Perhaps I should just make a folder 'Pointers' and put it there, and a readme just to make a point, that it could just become a separate chapter.
- [x] "30. Misc Diagram Topics"
    - [x] I think this is appropriate as a separate chapter.
    - [x] "1. Diagram Expression Introduction" > Larger
    - [x] "2. About Programming In General" > Larger
    - [x] "3. Diagram Metrics" > Larger or will be.
    - [x] "4. Coloring" > Smaller
    - [x] "6.0. Example Diagrams Introduction" > Small
        - [x] Maybe move to the folder 6.1. Example Diagrams? Maybe call it Readme?
- [x] "7. Summaries of Other Languages"
    - [x] Larger
- [x] "32. Previous Versions"
    - [x] This folder structure seems off when there is essentially only one version, as one document in it.
    - [x] (There used to be multiple versions in one folder. Those were put out of scope of the Encircle Language Spec.)

##### 2020-05-23 Done Merging Inheritance Articles Together

Most of them are quite small.
Grouping together main concepts into one article might make sense.
Specialization is mostly small articles, but quite a few of them. But maybe combine those into one article.
The articles that follow do not seem to be many or they are already larger ones I might not want to group together.

```
- 01. Inheritance Introduction > Smaller
- 02. Inheritance Main Concepts > Smaller
- 03.        Class Inheritance > Smaller
- 04.        Object Inheritance > Smaller
- 05.        List Inheritance > Smaller
- 06.        System Inheritance > Medium-sized / smaller
- 07.        Interface Inheritance > Smaller
- 07. Specialization > Smaller
- 08.        Specialization & Data Replacement > Smaller
- 09.        Altering the Member Set > Smaller
- 10.             Member Addition > Smaller
- 11.             Member Exclusion > Medium-sized / smaller
- 12.             Member Inclusion > Smaller
- 14.        Detouring Members > Smaller
- 15.             Shadowing > Medium-sized / smaller
- 16.             Overriding > Medium-sized
- 17.        Altering Command Implementations > Smaller
- 18.             Command Extension > Smaller
- 19.             System Command Extension > Smaller
- 20.             System Command Overriding > Smaller
- 21.             System Command Shadowing > Smaller
- 22.             System Command Extension By Shadowing > Smaller
- 23.             System Command Extension By Overriding (Questionable) > Smaller
- 24.             System Command Overriding By Extension > Smaller
- 25.        Destructive & Non-Destructive Specialization Methods > Smaller
- 26. Misc Inheritance Situations > Medium-sized / smaller
    - > Moved to Inheritance Main Concepts.
- 27. Enforcing & Preventing Specialization > Larger > Would probably keep it separate.
- 28. Deeper Specialization.docx > Larger > Would probably keep it separate.
- 29. Alternate Version Through Inheritance > Smaller
    - > Maybe move this detail elsewhere.
        Might not be worth an entirely separate article.
- 30.1. Extending System Objects (Older) > Larger
    - > Not sure what the status of this is? It has the word 'Older' in it.
        Is it deprecated? Covered elsewhere already?
        I don't know. But at this stage maybe I do not need to know.
- 30.1. Extending System Objects in a Diagram (Older) > Medium-sized / smaller
    - > Would probably merge it with the main article.
- 31. Inheritance Ideas > Medium-sized
```

##### 2020-05-22 Done Merging Events Articles Together

Possibly this is one you want to put into a single document.  
Most of them are small.
"13. Qualified Event Names" should be out of scope, since it is about text code?  
The articles before 'System Events' might be put into one article.  
I might put System Events in one article.  
System Events can almost be demoted to a Construct Draft, but just like System Objects is in there, I might want to keep System Events part of the Encircle Language Spec (for now). (The correspondence between System Objects and System Events is that they seem more like part of a run-time or if Encircle would function more like a stand-alone language, rather than mostly a diagram notation).  
The last 3 articles might become a single 'misc' article. But perhaps some of them have a place in the main article.

```
- 01. Events Introduction > Smaller
- 02. Prime Event Example, Button Clicked > Smaller
- 03. Events Main Concepts > Smallish
- 04. Event Situations > Smallish
- 05. Explicit Implementation of Event Object > Smaller
- 06. Explicit Interface of Event Object > Smaller
- 07. Event Interface Reference > Smaller
- 08. System Events > Medium sized / smaller
- 09.        System Events in Normal Notation > Smaller
- 10.        Simplified System Event Notation > Medium sized
- 11.        System Event Parameters > Medium sized / smaller
- 12.        System Event Design Choices > Smaller
- 13. Qualified Event Names > Smaller << out of scope >>
- 14. Interaction Events > Smaller
- 15. Black Boxing Events > Medium sized / smaller
- 16. Event Alternatives> Smaller
- 99. Ideas > Smallish
```

##### 2020-05-22 Done Merging Interfaces Articles Together

```
- 01. Interfaces Introduction > Small
- 02. Interfaces Main Concepts.docx > Medium sized
- 03. Interface Aspect.docx > Small
- 04.        System Commands for the Interface Aspect.docx > Medium sized / small
- 05.        System Commands for the Interface Merging Aspect.docx > Small
- 06.        Interface Aspect in System Interface.docx > Medium sized / small
- 07.        Interface Assignment Types.docx > Medium sized
- 08.        Interface System Command Calls.docx > Medium size
- 09.        Interface Connectors.docx > Small
- 10.        Interface Connections.docx > Small
- 11.        New Command with Interface Parameter.docx > Small
- 12. Command Interfaces.docx > Small < <use case >>
- 13. Interface Referencing and Redirecting.docx > Small << notation demonstration >>
- 14. Member Grouping.docx > Medium sized / small << edge-case >>
- 15. Relationships Through Interfaces.docx > Medium sized << notation demonstration >>
- 16. Interface Referrers.docx > Small << edge-case >>
- 17. Reliability of Interfaces.docx > Medium sized / small << edge-case >>
- 18. Group By Source.docx > Medium sized / small << out of scope? >>
- 19. Imaginary Backward Relationships.docx > Small << out of scope? >>
- 20. Target Interfaces.docx > Medium sized, because of ideas, main text is small. << main concept >>
- 21. Mutual Commands, Mutual Interfaces (Unfinished).docx > Small << construct draft >>
- 22. Extensive Classification with Interfaces (Unfinished).docx > Small << construct draft >>
- 99. Interfaces Ideas.docx > Small > Move to main article.
```

None of the articles are that big. The size differences are a bit all over the place.
Logically I might group together all Interface Aspects articles.
The Intro and Main Concepts seem logical to group.
I think I'll just start with those and take it from there.
There's something about text code in Interface Assignment Types. That could be moved to Encircle Construct Drafts.
Maybe move the Loose Ideas all to a separate article at the end.

I discuss problems with interface reliability in case of automatically established bidirectional relationships. The idea of always having bidirectional relationships between things is something I want to distance myself from in the Encircle Language Spec, and perhaps leave as a topic for Encircle Construct Drafts. But right now the idea seems embedded into the Encircle Language Spec, and without significant modification, it does not seem you can deprecate it yet. I think such redesign of Relationships may take place in the future (to leave out automatic bidirectional relationships). But I think it is only then that I also adapt the text about this edge cases. So the question that worried me is whether it is out of scope or not. The answer for now seems to be: no, it is in scope, but the design of the concept of Relationships may be changed in later efforts.

##### 2020-05-20 Done Merging Black Boxes Articles Together

There are quite a few relatively small articles.
But I have doubts how to group them to bigger articles.
I do not think I want to group them together just in one big article.
I might just go for it, grouping the first smaller articles into a bigger one.

- Smaller, integrated into a single article:
    - "01. Black Box Introduction"
    - "02. Black Box Main Concepts"
    - "03. Public & Private"
    - "04. Friend Declaration"
    - "05. Notations of Private"
    - "06. Friend Declaration in Instances"
    - "07. Public & Friend Connections"
    - "08. Access Controlling Aspects"
    - "09. Object-Bound, Reference-Bound & Access Control"
    - "13. Assignment between Friend Members"
    - "14. Friend = Wavy Line"
- Group these together:
    - "10. Public & Private Connectors > Kinda medium sized"
    - "11. Public & Private Connections > Relatively bigger."
    - "12. Public & Private Assignment > Kinda medium sized."
- Putting these together in one article:
    - "20. Black Box Miscellaneous Issues"
        - Looks unfinished.
        - Objects Take Over Class Access Control: Might move to article Black Boxes, section Friend Declarations in Instances.
    - "21. Black Box Side-Issues"
        - Looks unfinished.
        - Might move these Encircle Broader View:
            - Black Boxing and User Access Control
            - Programmers and Users
    - "22. Black Box Details, May Cover Last"
        - Unfinished drafts.
        - Might move these Encircle Construct Drafts:
            - Level Limitation
            - Module Level Limitation
            - Downsides to Black Boxes
            - Get For Access and Get For Copy
            - Inaccessible System Aspects
            - Compared to Traditional Black Boxing (goes in too deep on automatic containment)
            - Other Details
        - Special case:
            - Simplified Access Connectors: I think those ideas could be moved to Simplified Access Control Notation, because that is what they are about. Big brainstorm though.
    - "23. Black Box Details, Might Not Cover"
        - Same as above.
        - Moving it to Encircle Construct Drafts after some considerations.
- "23.3. Black Box Details, May Not Cover, Simplified Access Control Expression in a Diagram"
    - Left it for what it is. Am not calling it unfinished. It seems finished. Maybe might change in the future, but it looks like a worked out idea.
- Moved from Encircle Language Spec to Encircle Construct Drafts:
    - "23.1. Black Box Details, May Not Cover, Simplified Access Control Expression"
    - "23.2. Black Box Details, May Not Cover, Simplified Access Control Expression in Text Code"

##### 2020-05-20 Done Merging Execution Control Articles Together

- [x] I think I want to merge it into the following set of articles:
    - [x] "1.0.1. Introduction to Execution Control"
    - [x] "2.0.1. Conditional Execution"
    - [x] "3.0.1. Loops"
    - [x] "4.0.1. Jumps"
    - [x] "5.0.1. Loop-Related Jumps"
- [x] Reason: I had almost merged it into one document, but I like how the separate documents seem to nicely categorize the different kinds of execution control. Also: merging it into one document would give me a tendency to use more heading levels and the styling for those is not optimal yet. Not a strong argument maybe, but it does make me think: More heading levels might be 'proof' that a separation in several articles is not a bad thing.
- [x] I just wanted to save some time merging each pair of documents lots of times only to merge them into a larger document again.
- [x] Taking a look at how it looks now.

##### 2020-05-20 Done Merging Parameters Articles Together

- [x] ~~Maybe merge all the Parameters content into one article if it is not too much.~~
- [x] Relatively small:
    - [x] "02.0. Parameter Passing.docx:"
    - [x] "03.0. Joint Display of Access Connectors and Object Relationships.docx"
    - [x] Moved their text to the "Miscellaneous Parameter Topics" article.
- [x] "05.0. Imported Parameter Concepts"
    - [x] Not large topics. Maybe Required & Optional is a bit larger. Half of it or so is idea texts, but not bad ones I think. Basically just the version from the previous version of the documentation (Symbol Language.doc).
    - [x] Merging together seems appropriate.
- [x] "10.0. Miscellaneous Parameter Topics"
    - [x] Also not large articles.
    - [x] Merging together seems appropriate.
- [x] ~~I think I want to merge things together in phases, before I decide whether or not I want to turn it into just one bigger article.~~

##### 2020-05-18 Done Merging Commands Articles Together

- [x] I still mean to rename the docs so the 'in a Diagram suffixes are gone.
- [x] Could not see a pattern in what I would want browsing the first few documents.
- [x] Maybe I want to group the first ones into a Main Concepts article.
- [x] I might want to inspect it some more in search of ideas.
- [x] Main Concepts:
    - [x] I suspect I would like to put the 10 documents Commands.docx until Active Clause.docx in one document.
- [x] Hard to group:
    - [x] Start & Stop.docx until 13.1. Changing Inactive to Executable.docx the articles are sort of medium sized and hard to view as a group together, I think.
- [x] Personal feeling: I think the information rate is too high for me now. Lots of topics rush by my eyes at a large pace and my energy level is dropping.
- [x] Even if I do not know how I could group together many of the articles logically, if I can find a few groups, that would already benefit the overviewability of the topic list.
- [x] ~~These are small:~~
    - [x] ~~"15.0. Command References Inside Commands.docx"~~
    - [x] ~~"16.2. Executables & Executions.docx"~~
    - [x] ~~"17.1. Procedure.docx"~~
    - [x] ~~"18. Resolution When Not Allowed For Commands.docx"~~
    - [x] ~~"22.0.     Sub-Commands Not Manually Started.docx"~~
- [x] "19. Parent Controls Its Sub-Executions.docx":
    - [x] Seems like the 3 articles after it are part of it, but not sure.
- [x] Creation behavior:
    - [x] There seem 8 'Creation Behavior' articles. They might not be small, but grouping them to one article might tidy up. Also, it does not seem to me a topic you always want to see in detail. Maybe look at it once and say "Ok, so that's how that could work." Now the topic is quite prominently present in the article list.
- [x] These seem groupable:
    - [x] "35.2. Inactive Command Object Redirection.docx"
    - [x] "36.1. Inactive Command Class Redirection.docx"
    - [x] "37.2. Executable Command Class Redirection.docx"
    - [x] "38.2. Executable Command Object Redirection.docx"
- [x] These seem groupable:
    - [x] "39.1. Target Command Object.docx"
    - [x] "40.1. Target Command Definition.docx"
    - [x] Or maybe put in Command Redirection.
    - [x] Those two have loose ideas in them.
    - [x] I might not want to stop myself from merging articles that have loose ideas. (My argument against it seems to be: It might get messy.)
    - [x] I also might not want to step away from the 'put loose ideas where they belong'.
    - [x] So maybe I want to accept that some loose ideas get spread a little over the content here and there.
    - [x] The idea with the loose ideas was to go through them at some point seeing if any of it is still usable or not and then maybe discard them, or integrate the ideas into the content. Something like that.
- [x] Out of scope? 42.0. Implementation of System Commands.docx
- [x] Example diagrams:
    - [x] Maybe put them all in one article.
    - [x] ~~Maybe rename and see what they mean.~~
- [x] Some topics' titles look like main concepts to me. I want to evaluate later if I want to move them to Commands Main Concepts.docx.
    - [x] Maybe if ut were'd for the Start and Stop article in between I would just move more to Commands Main Concepts.
    - [x] Consider merging the content of these with into the Commands Main Concepts.docx:
    - [x] "13. Reading & Writing Parameters.docx"
- [x] Merge these two:
    - [x] "17. Command Object Referrers.docx"
    - [x] "18. Command Definition Referrers.docx"

##### 2020-05-18 Done Merging System Objects Articles Together

- [x] Deciding what to do with these, was a bit intense. Especially when I hit a part of the content I have reservations about.
- [x] System Commands:
    - [x] Articles for the various aspects might be merged to one article. Those are like 15 articles or so. Most of them are small. 3 of them are a bit larger.
- [x] System Interfaces:
    - [x] Articles for the various system objects might be put together into one. Not that all of them are small. Just that enough of them are. It seems a bit of a hinder to have to open them one by one. A single article might make browsing the content easier. The amount of articles might be more overwhelming that an article that has some pages.
- [x] Assignment + subtopics
    - [x] May be turned onto 1 article.
- [x] I think the main parts may become more obvious from the article list if I merge together more articles into one.
- [x] System Command Call Notations:
    - [x] 4 smaller, 3 larger
    - [x] Not sure if for the size of them I would merge them together.
    - [x] It is kind of one topic.
- [x] ~~Misc topics at the end:~~
    - [x] ~~Not sure yet if merging is appropriate.~~

##### 2020-05-16 Done Reorganize Encircle Language Spec Files

- [x] The bulk of the content is in the Coding Concepts.
- [x] Diagram Expression content:
    - [x] Is now in more than 1 place.
    - [x] "1. Diagram Expression" folder:
        - [x] Describes Basic Diagram Elements.
        - [x] The argument, that the diagram elements must be quickly introduced at the beginning, I am not sure about that anymore. So not sure if this actually must be at the beginning of the documentation anymore.
    - [x] "6. Expression\1. Diagrams"
        - [x] Seems less finished up. I am not sure I would want to put that at the top of the documentation or at least not in this state.
    - [x] "7. Other Topics\9. Old or Boring\About Programming In General.doc"
        - [x] This is old text, that when rewritten I might even want as the introduction text that the Encircle Language Spec starts with, or maybe just part of it.
        - [x] Is not really a diagram expression topic specifically.
- [x] ~~I might want to somehow merge those diagram topics together.~~
- [x] And put the Coding Concepts sub-folders just in the root.
- [x] In what order will I 'mix' the Coding Concepts and the Diagram Expression topics?
    - [x] Brainstorm: I don't think I want to just start with the Objects chapter. I do like that something starts with the overview. Right now that is the Basic Diagram Elements. Later it may be something else. I think I will keep Basic Diagram Element at the top. Then just the code concepts. Then Other Diagram Expression Topics, just a new folder, a flattened out version of the old.
    - [x] I guess I am just making a flatter list of things and keeping most of the order.
    - [x] 'About Programming In General.doc' 
        - [x] Could be put at the top as the introduction.
        - [x] Actually, just reading it over, I think it may be still to rough of a text, that I want to make a bit more neutral, before making it the main thing to start with.
        - [x] It and other bits of texts from the original Symbol Language.doc may compose a new introduction to the Encircle language after some reformulating.
        - [x] All in all, I think this content is a but rough for putting at the beginning of the documentation.
- [x] There is a clash in index pages. "Code Concepts.doc" and "Language.doc" may need to become one and cleaned up.
- [x] Moving "Language.doc" content to "Code Concepts.doc" in a controlled fashion.
    - [x] There is no heading 'Object Order'.
- [x] I think I am just going to knead the content.
- [x] The folder subdivision is now much simpler.
- [x] "8.Previous Versions" folder:
    - [x] Has the version of the documentation: Symbol Language.doc.
    - [x] Also contains those Symbol Pictures. I do not want to publish all of them.
    - [x] I do not think I want this document in the published material: D:\Source\JJs Software\Software System Docs\1.1. Encircle Language Spec\8. Previous Versions\2004-00-00 XX    Symbol Language\Other Files\Coding.txt.
    - [x] Or rather, this has some content in it, that I find questionable.
    - [x] I see two zips with pictures.
    - [x] How do I handle this? In the future I want to go list out all files in the history and remove things from the history that I do not want to publish. Those zips might become one of those files.
    - [x] But when I clean up the current state, will I find all the files back that I want to remove from history? Some have obvious file names. So I guess I will.
    - [x] I question whether I even want to include those example diagrams. Or whether I want to include them in this state.
    - [x] Or maybe I will need them for a better quality referenced image? Nah, I doubt it. That seems too much work, to replace the images in the docs with possibly better images from that zip.
    - [x] It might also not be useful to readers, at least not all of it, because it is just bulky. No one might want to go through them I think.
    - [x] Perhaps a selection of it might be useful. 
    - [x] The argument 'Too interesting too throw away'. I might not agree with that anymore.
    - [x] I think most of them are also present somewhere in the documentation.
    - [x] Some of them I want to not have in source control history.
    - [x] Some I might want to keep.
    - [x] If those 2 zips with pictures are the same...
    - [x] I just compared file sizes and they are different. So the zips might not be the same.
    - [x] I could unpack and compare.
    - [x] I think if they are comparable or one is preferred over another, I could remove the other.
    - [x] I could strip one of the copies.
    - [x] Leave that one in the new documentation.
    - [x] So do I remove the one from the 'Previous Version' documentation?
    - [x] For versioning like that, I think it would have made sense to keep the one in the 'Previous Version' documentation.
    - [x] But for control over the content, that I publish, in this case I would really like one copy.
    - [x] Result of diff: 2x Thumbs.db. 4x a file that is not in 'Previous Version', but is in 'Other Diagram Topics\Example Diagrams'
    - [x] Then do I want to remove the one in 'Previous Versions'?
    - [x] I am not sure I want to unzip them first and then commit. Maybe I want to clear it out first after I unzip it, before I commit it. That might make cleaning up later easier.
    - [x] I tried to revert my commit, but it leaves behind files in my working folder.
    - [x] Reason for deleting picture: Don't want it in there.
    - [x] Reason for deleting picture: Is already visible in a document.
    - [x] Reason for deleting picture: It has private info seen right through the paper.
    - [x] Some of them I have a hard time saying goodbye to.
    - [x] I am beginning to think I might just want to remove all of them.
    - [x] Or most of them.
    - [x] The scanned ones probably.
    - [x] The ones certainly used in documentation or otherwise discardable.
    - [x] I think I would remove most of them, and only keep a couple.
    - [x] Oh, I am done.

##### 2020-04-01 Done Encircle Language Spec Planning Docs

- [x] Empty project folders:
    - [x] I could evaluate whether those empty planning docs folders are needed.
    - [x] To me it seems odd now, that 'Errors' is put out of scope.
    - [x] I think I want to move the topics 'Errors' and 'Concept Construct' from the Out-of-Scope document to the Encircle Language Spec Planning docs.
    - [x] The 'Out-of-Scope' document os currently not just postponed items of the Encircle Language Spec, but more than that: not even considered part of the Encircle Language Spec project at all anymore.
    - [x] It is still not a hard rule to be set. But putting Errors and Concepts out of view, makes it sort of not the same project for the sake of Concepts and putting my head into the sand when it is about Errors. If I have ideas about these things, they do belong in the project I think. I have a hard time thinking them away.
- [x] Formatting:
    - [x] Phase-by-phase.
        - [x] Background black.
        - [x] Name spelling JJ van Zon.
        - [x] No abbreviations in folder name and file name.
        - [x] Rename 'Document' to 'Spec'?
        - [x] Suffix with 'Plan'.
        - [x] Do the above for the Current and Future Projects
        - [x] 'Project' => 'Plan'
        - [x] Leave out the word 'Plan' if obvious.
        - [x] Headings 'Encircle Language Spec' + similar to folder and file name.
        - [x] 'Computer Language' => 'Encircle Language'
        - [x] 'Articles' => 'Spec'
        - [x] No sub folders, just files?
            - [x] Some sub-projects contain many files.
            - [x] Flattening it out might make a big list.
            - [x] Keeping some folders but have other as loose files, makes you lose that time-line feeling.
            - [x] Too much doubt -> Postpone.
        - [x] Maybe prefix all with Encircle Language Spec Plan. Then simplify the rest of the title, because Plan is already implied.
            - [x] Getting path length problems. Collapsing sub-folders with only one file after all.
        - [x] Not sure if that prefixing looks so great.
            - [x] It looks cluttered. And I cannot apply it consistently, because of path length problems. Branch. Try without prefixes.
            - [x] 'Spec Plan' somewhere in there looked ok.
            - [x] My doubts are that if this doc is in the internet, the title means a lot, so why not have it be complete? It does already have that completeness somewhere in the URL, but...
            - [x] Maybe let go of the toilet role principle and just call something 'Automatic Containment for Relationships.doc'. Not 'Plan', not 'Spec' just lazy. Maybe it is ok.
            - [x] My being better at systematics than words might be in the way. So that I don't easily decide what's clear enough.
        - [x] Convert to docx without Compatibility Mode.
            - [x] What use is that, if I want to convert it to MD instead?
            - [x] Conversion to MD is not great if I use color coding it the docs.
        - [x] Remove '& Copyright'
            - [x] > Only found 1 occurrence: 'Encircle Language Spec Ideas'.
        - [x] Remove unnecessary title page white space and 'version XXXX-XX' mentioning.
        - [x] Make main heading and such not take up so much space.
        - [x] Month in the headings, so it is clear that the fact that it is a time period is leading.
            - [x] In the front or the back of the sub-project name?
            - [x] In the file names too in case they have a folder?
            - [x] ~~Months in headings: not entirely convinced about the difference of the order where the month ends up between 'Project Plans' and 'Project Summaries'.~~
        - [x] 'TODO' => 'Notes'? > Cannot find it.
        - [x] Set proofing language to English US. > I don't see the problem anymore. Maybe the conversion to docx fixed it.
        - [x] First pages layout
        - [x] Page header and footer
            - [x] I am good with no page headers and footers.
        - [x] File properties (author and such)
            - [x] If they are odd. Not that odd => Leave it there.
            - [x] Still have to do Done projects.
        - [x] Update lists of contents
        - [x] Legend:
            - [x] Brainstorm: I might keep the legend as it is. It may be more work to check which colors are used where and to change it? Maybe not, maybe that would be the right way to go.
            - [x] 'Legend' => 'Legend of Symbols and Markings'?
            - [x] Use simpler color coding.
            - [x] There is ambiguity between coloring of back then and now.
                - [x] Brown meant I think postponed (indefinitely). Some share of brown even meant 'part done, part postponed'. Now brown means do not do. (And part done, part postponed is orange.)
                - [x] Light grey used to mean do not do. Now it means done.
            - [x] Normalize the legends.
            - [x] Make it 1 central document
            - [x] This document has a legend right inside it: Concepts as External Modules Spec Goal (2008-05) (postponed).docx
        - [x] Font Calibri
            - [x] Just the normal font, not the headings.
        - [x] ~~Headings do not have colors.~~
            - [x] ~~Are not going to work for me anyway, with the low brightness on my screen.~~
            - [x] ~~It starts being not so functional anymore, the changes.~~
- [x] I somehow don't trust this is all there's to it about Encircle Language Spec planning docs. Look over the state of it. It *would* be fun to move on to a next topic and have something finished. But somehow I don't believe it. > It is. I lean towards the actual language spec rather than the planning, now.

##### 2020-03-22 Done Organize Planning Docs

- [x] I moved around folders, for a preliminary split up between Encircle Docs and Circle 3 Programming projects.
- [x] I could change titles of projects inside the doc content too.
    - [x] I am unsure whether I want to call the projects 'Encircle Docs'. Maybe 'Encircle Language Specification'.
    - [x] I do want to go for the name 'Encircle' as opposed to 'New Computer Language'.
        - [x] I don't mind that this makes my documentation stick to a name that in theory might later change. It probably will not change at all.
    - [x] But Encircle Docs is too general, I think. It should be Encircle Language Specification.
    - [x] I don't care for the abbreviation 'Spec'. I am not a fan of abbreviation and I don’t think it makes it much more concise or clear.
    - [x] Also: I am hitting my limit here. I'm tired and getting all sorts of symptoms.
    - [x] Encircle Language Design is also an option. 'Specification' may raise expectations about finishedness.
    - [x] Encircle Language Design Planning
    - [x] Encircle Language Specification
    - [x] 'Specification': suggests finishedness, but does it? CSS is all sorts unfinished modules.
    - [x] Leaving out 'Specification' or 'Design': Makes distinction with Circle 3 Programming hard to see.
    - [x] The word 'Encircle' should be in it.
    - [x] The word 'Language' at least sheds light a bit on what it actually is.
    - [x] But Encircle Language Specification Plan is just a long name.
    - [x] But 'New Computer Language Functional Design' was too, so that is not an argument?
    - [x] 'Spec': Is an abbreviation. I generally dislike those, but I think in this case it is appropriate. It is adopted as a word by the community.
- [x] I could evaluate whether those empty planning docs folders are needed.
    - [x] The 'update ... articles' sub-projects
        - [x] Defined as empty project doc folders: I see some of it back in the Encircle Language Spec's Strategy doc, Project Steps and Time Planning, but not in the Products doc. Some redo's are defined, be it not in Products doc. It seems the reason for redoing is not always stated. I think I should make the list complete in all the planning docs where appropriate. Then I can get rid of the remaining empty sub-project folders.
        - [x] Mentioned them in the Products doc now.
        - [x] Removed the empty project doc folders.
        - [x] Look at Encircle Language Spec Strategy for things to put in Encircle Language Spec Products.
        - [x] Look at Encircle Language Spec Project Steps & Time Planning for things to put in Encircle Language Spec Products.
            - [x] There is a lot there that specifies the reasons to change the articles.
        - [x] Consider that some elaborations in the Encircle Language Spec Products document might belong elsewhere.
            - [x] Do they belong in Encircle Language Spec Strategy?
            - [x] Sort of collides with the Sub-Project folders idea. Maybe details belong in a sub-project folder and a general reference to it in the strategy doc.
            - [x] Maybe go the other way: put sub-projects strategy in the main strategy doc and get rid of separate sub-projects. (My gut says: no, keep sub-project descriptions. That's what they are for: elaboration on a sub-project's scope.)
            - [x] Decision: Rule: Any elaboration now in the Products planning doc, belongs in a sub-project document.
- [x] Sub-Projects:
    - [x] The documents could probably be shorter. Lots of those Project Summaries are not so useful template texts, not filled in. The notes at the bottom would do.
    - [x] Then it is basically just loose ideas, that might have been given a too prominent place. Maybe put it elsewhere, if it is just unhelpful for visual overview, perhaps. > Some are more than that. I keep em this way.
- [x] I like that I seem to build tolerance (back) for not exactly knowing where I am going with it, gradually shaping it, and just taking my time to make things more overviewable, regardless of whether someone might think it is time well spent or not. I myself just create more overview and understanding of the material that way.

### Scoping

#### TODO

##### 2021-03-30 TODO Scoping Encircle-Language-Spec-Plans

- [ ] Encircle-Language-Spec-Plans repository
    - [ ] 'Out-of-scope' things might need distinction between "Broader View", "Construct Drafts" and not to be part of the Encircle-Language-Spec-Plans at all.

#### Done

##### 2020-12-05 Done Scope (for Git Migration)

- [x] Outline:
    - [x] It currently seems to be part of a Software System Docs repository.
    - [x] The parts about Encircle might be isolated into a separate Git Repository.
    - [x] With history intact.
    - [x] By copying the Software System Docs repository and stripping it down.
- [x] NOTE:
    - [x] I feel I am scoping blindly.
    - [x] I think I did this before.
    - [x] This might be just trial run.
    - [x] Possibly useful paragraphs:
    - [x] "2019-12-29 Done Brainstorm Scope (Useful)"
    - [x] "2019-08-05 Brainstorm Open Source"
    - [x] Those still may not scope things clearly.
    - [x] (Seems about Encircle Language Spec vs 'the rest'.)
    - [x] (I am looking for Encircle Docs vs 'the rest' now. (Encircle Docs = language spec + construct drafts + broader view)
    - [x] Just winging it for now.
    - [x] Maybe define scope sharply later.
    - [x] May do multiple runs until it seems right.
- [x] Picture files:
    - [x] Trying to cross-reference picture files with Excel.
    - [x] Helper: <https://www.extendoffice.com/documents/excel/2104-excel-return-first-last-non-blank-cell-in-row-column.html>
    - [x] I may be better of using C#. Bending my mind too much.
- [x] Scope:
    - [x] In general the scope seems to be:
        - [x] "*Any* of the ideas, that might remotely relate to anything that could be remotely seen as *programming language design."*
    - [x] Including "Language" topics.
        - [x] (Perhaps) including former versions of Symbol and Creator.
        - [x] Excluding "Text", "VB Code", "C++ Code" (code generators)
        - [x] "Circularity": Might keep it.
        - [x] Not that sure about keeping Creator documentation. > Keeping it for now.
    - [x] No "Operating System" topics
        - [x] But keeping:
            - [x] "Concurrency"
            - [x] "Input / output"
            - [x] "Internet as a Single Computer"
            - [x] "Object Storage" (index page)
            - [x] ~~"Unifying Disk & Memory" > Content seems chaotic brainstorming.~~
    - [x] No "Framework" topics
        - [x] But keeping the "Data Concepts":
            - [x] "Object Order"
            - [x] "Binaral"
            - [x] "Defaults" / "Default Values"
            - [x] "Locking"
            - [x] "Transactions"
        - [x] But removing:
            - [x] "Enum"
            - [x] "Boolean"
        - [x] But keeping index pages of:
            - [x] "Integration"
            - [x] "Expression"
            - [x] "More Text Codes" / "Additional Text Codes" / "Legacy Text Codes"
            - [x] "Protocols"
            - [x] "Libraries"
    - [x] No "Applications & Media" topics
    - [x] Pictures:
        - [x] Removing zips
        - [x] Removing picture files
        - [x] Except the ones remaining in master.
    - [x] Removing things with intellectual property ambiguities:
        - [x] Removing "IPC" topic
        - [x] "C:\Repositories\Software System Docs\2. Framework\2. Data Concepts\12. Scans\Image62.jpg"
    - [x] Archive: Might be selective about files in "Archive" folder.

##### 2019-08-05 Done Brainstorm Scope

- [x] Encircle Broader View: Maybe the design of the programming language should lose some ambition and express that only as dreams.
- [x] I notice I talk a lot about implementation rather than notation. For instance: Does a dashed circle mean it is used as a class, enforced to be a class, static inside its container, how does it work in the system interfaces? What if it is just the notation that is the main idea, what if the implementation isn't. That might even make system interfaces' precise definition not important or maybe just subjected to diagrams drawn out to represent things from another language, like C#. C# getters and setters might be in a system interface notation. But setting an object reference's interface dynamically in runtime... may be too much of an implementation detail. I think it is a language definition / runtime implementation separation. In think the engineers at Microsoft might be right about developing language spec / runtime / framework / compiler quasi-independently. Maybe I can be inspired by that and make my language definition a little simpler. I am subjected to the pitfall of wanting to cover every little minor edge-case, of which I have a fear that it may make the whole system fall to pieces. I already warned myself about that in the Encircle Language Spec Strategy document. But now I think other people might actually read this, I start to think: maybe limit the scope. Somehow define the diagram notation and what it represents and not want to work out how things would work in a runtime. Runtime would be a system where the diagrams and actually the data that internally describes the diagram, to be loaded and run as computer programs. I think I wanted to check the usability of the notation by shining light on any little aspect of it, I could find. But I think some details are not that important. Maybe those are to be demoted to possible implementation details, to keep the main part of the story clean. I am OK with apologizing in the documentation, that this might not be usable or something. The description in the Strategy document is pretty much spot on, I think.
- [x] Encircle Construct Drafts: I get the problem that next to introducing new notation, I also wanted to introduce new concepts. A new conceptual take on things. I think it all became a little much.

##### 2020-05-14 Done Scoping | Split Up Encircle Docs

- [x] Next step might even be starting to split up the Encircle Language Spec itself in 'in scope' and 'out of scope'.
- [x] Doing a git push.
- [x] Renaming git repo Encircle Docs to Software System Docs.
- [x] Renaming git repo Project Docs to Planning Docs.
- [x] Moving around folders.
- [x] "Previous Versions\2005-07-28 00    Creator 0.4":
    - [x] For my own overview it might be useful.
    - [x] But for a clear presentation of the Encircle Language Spec, it seems to contribute much.
    - [x] It might obscure the whole to include this.
    - [x] An argument for including it, might be to prove it has a development history, but I might not value this that much.
    - [x] Perhaps move it to one of the other parts of the Encircle docs than the spec? Broader view or something?
- [x] Branching
- [x] "Language\Integration" and " Language\Libraries"
    - [x] Under the Language folder: might I move those to the Framework part? They are not concept frameworks, but they don't need to be.
- [x] "10. Encircle Constructs Drafts\6. Expression\6. More Text Codes": 
    - [x] Has the sub-folders "1. Parser" and "2. Text Templates". I do not think those topics belong in Encircle Construct Drafts. Maybe in Encircle Broader View. But maybe those topics do not belong in Encircle Language docs at all. More like framework. The index page includes other sub-topics, that used to be in that folder: such as 'other text codes', 'math' and 'assembly'. So some time in the past those topics were all in one place. I am not sure to exclude all of those topics from Encircle Language and then maybe move them to the Framework part of the Software System docs, or whether some of it somehow has a place in broader perspective.
    - [x] They are probably there, because in the main subdivision of Software System, they would fall under 'Code' and that might be what made them end up in the proximity of Encircle Language Spec. So it indeed probably does not belong under Encircle at all, but it does belong under 'Code' in Software System.
- [x] By now I have:
    - [x] Categorized topics from "Language" over "Encircle Language Spec", "Encircle Constructs Drafts", "Encircle Broader View" and "Framework". 
- [x] Checking if I like how topics ended up in one of 3 categories.
- [x] I have deleted files in my commit. I only want to see renames.
- [x] Commit
- [x] Some 'Operating System' topics might belong in an Encircle Language topic group.
- [x] Some documents cover multiple topics. I would like to split those documents up. 
    - [x] I could just make copies.
    - [x] And then strip out content that does not apply.
    - [x] ~~To what degree is it useful to rephrase those directory indexes to reflect the contents better? > It might be better to not do that right now.~~

##### 2020-03-07 Do Not Do: Brainstorm Circle 3 Programming Planning Docs

(Circle 3 projects are software development projects, unlike Encircle Docs projects, which are language design projects.)

It appears around 2010 I started off with programming Circle 3 with the intention of a more rigorous planning methodology and higher quality technical documentation. Around the same time I switched employers. The new employer did not value my doing planning or documentation, just coding. In projects at home it seems I adopted that way of working. So planning docs and tech docs were no concern anymore. I focused on coding. I think I also stopped keeping an hour sheet at home. That felt was freeing. It felt too much like work logging the hours I spent at hobby projects. But the real motivation for the shift in way of working, seems to be that I cannot have 2 methodologies at the same time: one at home and another one at the office. That seems intrinsic to how my mind handles things.

So I have these near-perfect planning docs for Circle 3, while the execution of the projects was almost only coding, no planning, no documentation.

I don't think I want to reformulate the goals of Circle 3 programming projects, to exclude software design. It is not about making those planning docs good.

##### 2020-03-22 Do Not Do: Circle 3 Programming Planning Docs

- [x] I could change titles of projects inside the doc content too.
    - [x] Also for Circle 3 Programming, though less importantly.
- [x] Could I just go with it, call it 'Circle 3 Programming'? And if I want to mention in the planning docs that to documentation was of little concern, just do it with a more open formulation, like 'documentation was of little concern' or 'very little documentation turned out to be written in these projects. The focus turned out to be on programming the code.'?
- [x] I could put a remark or something in the Circle 3 Programming docs that I did not do any documentation, even though it was the initial plan to do that.
- [x] I was going over some sub-project docs to check if any documentation was written during those projects.
- [x] Other sub-projects I scanned were not clearly any doc issues in them. 

##### 2020-04-13 Done Brainstorm Scope

- Scope:
    - Some content in the idea box is also out-of-scope.
    - Strategy: Goal of the Language: It mentions fundamental principles, that may become out-of-scope. Higher Goal does too. Will I separate these things? So say: it’s a (diagrammatic) programming language. I had thoughts about saving the higher goals for later.

The scope used to be split in two: Language Spec and the rest.

Now I lean towards a split up in 3 or 4 actually: Language Spec / Broader Perspective / Construct Proposals / Other.

This changes things. This puts even more out of scope of Language Spec. Earlier on I thought anything that has to do with language spec could be in scope of this project, but part of its postponed parts. Yeah this seems arbitrary terminology, that seems to mean the same, but I am going with it. Earlier anything language speccy would be still in the project definition, but deemed optional. This split up was by feeling it is part of the language or not part of the language. Now I actually have in mind 3 categories of things that kind of fall under that umbrella 'part of the language': Language Spec / Broader Perspective / Construct Proposals.

I feel maybe I am not finished making the first split up and now already starting with the next?  
\>> I want to check that.

Also the new split up would give the wilder ideas a place, not on the big pile 'other', like internet as a single computer would be 'broader perspective'. Actually... you could interpret it differently. Everything not part of Language Spec will at first be put on the pile 'Other'.

Maybe it is better to put off fine-tuning the scope for now. First make it neat the way it is. I was making such nice progress with that, wasn't I?

##### 2020-05-10 Done Scoping: Symbol Language and Software System Planning Docs

- [x] Scope the planning docs even further.
- [x] I went through all the planning docs.
- [x] Marked in red things in the Main Project documents, things I would like to place out of scope.
- [x] These two documents may have content to weed out at one point:
    - [x] "2009-08 Review by Ramses, Small Plan.docx" has out-of-scope things. It's just a little hard to extract. Perhaps postpone that when I reconsider reformulating this content again.
        - [x] Marked some content in red.
        - [x] Take out the person's name.
        - [x] Still want to split the document up in two.
    - [x] "Diagrams, Coding Principles & Coding Concepts Plan (obsolete).docx": I may want to consider moving this out of scope, or at least part of it.
        - [x] Marked some content in red.
        - [x] Still want to split the document up in two.
- [x] The other Encircle Language Spec Plan docs seem fine regarding scoping for now.
- [x] Still want to move the things marked red in the documents, to the out-of-scope documents.
- [x] ~~Or consider the 'Software System' topics to put in scope.~~
    - [x] ~~The content seems of not much use for inclusion in Encircle Language Spec, not the planning docs nor the produced 'specification' docs.~~
    - [x] ~~Could be that this folder is relevant: "2001 - 2002 Symbol"~~
        - [x] ~~It is basically 4 empty folders to indicate projects, that took place, on the time line, without having a description. There is probably notes in hour sheets about this period.~~
    - [x] ~~Could be that this folder is relevant: "2003 - 2009 Software System Documentation"~~
        - [x] ~~"2007-10 Rethink Software System, Project Plan.doc":~~
            - [x] There it seems to start interweaving with Encircle Language Spec topics.
            - [x] The goal does not really talk specifically about programming languages. The notes taken while doing that project, mention several topics about programming languages, but just naming larger parts, not details. Not really much can be found that goes specifically into Encircle Language Spec and the diagram notation. I do not think much is of use in the Encircle Language Spec Plan documentation. It seems 'Symbol attempts' is the real first effort put into the diagram notation, that is mentioned in these planning docs (perhaps aside from what's in the hour loggings, which have not been considered yet).
            - [x] I do not think I can even formulate just a few sentences 'this and that' has been done regarding Encircle Language Spec in this project, while the project was also about larger parts. It's just that inconcrete.
        - [x] ~~"2009-04 01         Full Revision of Documentation    2009-04 - 2009-06"~~
            - [x] ~~"Software System Full Revision of Documentation, Goal.doc"~~
                - [x] ~~Most things are actually about Software System as a whole.~~
                - [x] ~~Only in general the Encircle Language Spec is mentioned, but no content seems to be concretely about Encircle Language Spec.~~
            - [x] ~~"Full Revision of Doc, Elements & Time Estim.doc"~~
                - [x] ~~"Main Modules: (19 articles, 90 sections)": There is the first time concrete work for Encircle Language Spec is mentioned, done during the project "Full Revision of Documentation    2009-04 - 2009-06".~~
                - [x] ~~At "- Sub-Modules: (25 articles, 218 sections)" it starts going into a bit more detail about it.~~
                - [x] ~~Up until now, just some main parts of Encircle Language Spec are named. Not sure if it is really that significant information to tell about projects and their execution.~~
                - [x] ~~It is recognizable for me, the topic subdivision. I could extract some info from it later. I could decide later what to do.~~
            - [x] ~~"Software System Full Revision of Documentation, Reflection.doc"~~
                - [x] ~~Half way, this reflection turns into almost the literal content of what the goal is of the Encircle Language Spec project.~~
                - [x] I think I can remove it. It is basically the strategy doc of Encircle Language spec. Consider that later.
                - [x] ~~It is interesting to see that Encircle Language Spec is exactly the next project after this.~~
                - [x] ~~So this is indeed the interlude to the Encircle Language Spec project. I like to see those connections.~~
            - [x] ~~"02. Software System Full Revision of Documentation, Implementation, Reach Goal A.doc"~~
                - [x] ~~Has some detail about Encircle Language Spec, but not much.~~
            - [x] ~~"04. Software System Full Revision of Documentation, Implementation, Reach Goal B.doc"~~
                - [x] ~~Among other things, lists main parts of Encircle Language Spec again, for which contents/direction 'pages' were written.~~
            - [x] ~~"06. Software System Full Revision of Documentation, Implementation, Finishing Touch.doc"~~
                - [x] ~~Almost random details.~~
        - [x] ~~The other parts of "2003 - 2009 Software System Documentation" contained nothing relevant.~~
    - [x] ~~Should any of that be included in the Encircle Language Spec Plan docs?~~
        - [x] ~~"2003 - 2009 Software System Documentation" is sort of the prequel to Encircle Language Spec. Haha.~~
        - [x] ~~And the "2001 - 2002 Symbol" phase starts with initial ideas about Encircle language, and ends with the unfinished Symbol.doc, though not much was written down about the progress (though probably things are in hour loggings, not considered yet.)~~
    - [x] ~~Looking at "1. Software System.doc":~~
        - [x] ~~If none of this part of the planning docs is usable for inclusion in Encircle Language Spec planning docs, it may be worth a peek at the actual document Software System.doc or the 'redirection pages'.~~
        - [x] ~~I like it. I do not think I see much content I would use for Encircle Language Spec. From earlier ideas I had, I expected to find more. Perhaps I looked it over wrong. Or maybe now much is narrowed in scope, some more content from this document does not fall into scope anymore, making less of it very usable in Encircle Language Spec. Just bits and pieces maybe, but I expect to find texts of similar content and quality near the topics of Encircle Language Spec already.~~

##### 2020-04-01 Done Scoping Encircle Language Spec Planning Docs

- [x] Encircle Language Specs Done projects:
    - [x] It is a lot of content. It is not practical for me to go into detail about it now. It is only the past plans, not the future, so less important.
- [x] Details:
    - [x] Get rid of content about 'studying'?
    - [x] Command as a Concept Spec Plan seems a super project but later turns out not to be.
        - [x] Actually, it is a parent project.
    - [x] Done project "Document Internet as a Single Computer" is out-of-scope...
        - [x] Lots of fundamental principles may become out-of-scope of the Encircle Language Specs Project and might become part of a separate piece of documentation Encircle Language Broader View or something.
        - [x] Not sure if right now I want to dump it in a Done folder with all these many projects in it.
        - [x] Does it matter? I am trying to isolate just Encircle Language Spec from Other / anything else.

##### 2020-04-01 Done Scoping Encircle Language Spec Planning Docs

- [x] Encircle Language Spec Products doc: Move postponed work from Done section to the Postponed section.
- [x] The document "Circle 3 Excluded Requirements" has topics that might be interesting for the Encircle Language Spec project.
    - [x] Was at: Round Up looking for things to add/move from Circle 3 Programming to Encircle Language Spec.
- [x] Circle 3 Programming, Preliminary Designs:
    - [x] Yes, definitely quite some useful texts in that document, that belong in the Encircle Language Spec project.
    - [x] The texts seem to belong in the actual Encircle Language Spec docs, not its planning docs.
    - [x] In the past I made effort to dump even unfinished ideas right inside the docs.
    - [x] I had doubts about it, since it would litter the docs with unfinished, lower quality material.
    - [x] But I remember doing it, because otherwise loose ideas would be spread over numerous sub-project documentation and would get out of view.
    - [x] Do I move these texts to the appropriate spot in the Encircle Docs now?
    - [x] Do I also move ideas from Sub-Projects there? Maybe those are too short to matter. And not really loose texts, but goals. Somewhere in the middle. So maybe I should copy/move some texts to the loose idea boxes of Encircle Language Spec.
    - [x] I'm staring at 'Concepts' now. But Concepts is out-of-scope. Very out-of-scope. Does it matter? Any content about it is to be dumped into the appropriate spot in the documentation.
    - [x] Object Order: Some of it is in Data Concepts. But I fundamentally need it in the Encircle language. It's not just list order. It's more fundamental. It can be command execution order, that is dependent on it. I just don't know where it belongs in the chapters. Maybe just its own chapter I was making a separation between coding concepts and data concepts once. Now most coding concepts are just part of the programming language and most data concepts are not. Just the separation is not as precisely clear as that.
- [x] Circle 3 Programming, Requirements:
    - [x] Has technical design requirements.
    - [x] I could look at them, take them out, compare them to the Encircle Docs requirements, to see if they are in there or have a place in there.
    - [x] Nah.
- [x] Concepts construct:
    - [x] I am missing writing the Concepts construct documentation from the planning docs. I only see it in the Circle 3 Programming, Excluded Requirements.
- [x] Lower contents:
    - [x] The idea of lower contents is described in planning docs not in Encircle Docs Planning, but in '1. Circle 3 Programming' planning.
    - [x] You can also find some texts about it here: Circle 3, Lower Contents, TODO.doc

##### 2020-03-22 Done Scoping, Project Names

- [x] Inspecting the sub-projects just to find whether documentation was of any concern in those projects, might be too intense for me right now.
- [x] The question I was trying to answer with that was: Is it accurate to call the super-project 'Circle 3 Programming'?
- [x] The reason for calling it that, is to make it clearer what the project entails, separating it better from the super-project with the name 'Encircle Docs', so that there is a clear distinction that one is about programming and the other is about documentation.
- [x] But from the top of my head I kind of already know that the focus of those Circle 3 projects was programming, not documentation.
- [x] I just want clarity on the distinction between projects Encircle Docs and Circle 3 Programming, but giving it a clearly distinctive name.

##### 2020-03-16 Done Scoping Circle 3 Requirements Docs

- [x] I moved content from Circle 3 Requirements to New Computer Language Products doc.
- [x] I could rename it to Circle 3 programming, rather than Circle 3 software development, because programming was all I did, not full blown software development cycles. Right? ('Programming' is a bit ambiguous too. It could mean program the dev environment or program using the new language. But I am OK with it.)
- [x] Maybe check sub-project docs later to verify that I didn't do any documentation.

This is spreading my attention over too many different things. Is there a more practical approach?

This is too intense. I have to stop again.

##### 2020-03-08 Done Reading Circle 3 Requirements Docs

The requirement group 'Priority C: Classes' has 1 language design feature: < Diagram Notation Design > Static. So that is to be moved to the language design planning docs.

'Priority E: Integration' contains brainstorming instead of a list of items.

> (I notice I get inspired to like implementation projects for Circle 3. I feel the enthusiasm in it. I somehow stopped working on it, though. Also it is not my goal right now. The goal is publish Encircle language design eventually.)

Some of the content in 'Priority E: Integration' could be part of language design, at least diagram metrics design and automatic containment. 

'Priority F: Large Amounts of Items': Spiraling could be part of diagram metrics documentation. And object order.

'Round-Up': Most are documentation issues, which in theory could be moved to the language design project instead. Except, they are 'technical design' documentation issues, which do not have a place in either the language design project or the circle 3 programming project, because 'technical design' I did not consider language design, because I would have called language design 'functional design'. 'Technical design' according to my views back then, would have be document how I implemented things in the programming of Circle 3, not how the language functionally works, but how Circle 3's .NET code works internally. However, I could see the topics up for 'technical design' as topic that also could use an update to the functional design. So I could consider those topics for extending the Encircle language spec project's requirements. Then I could consider removing documentation issues from the Circle 3 programming planning docs, because I wasn't going to do them anyway.

I ran over all the content of Circle 3 Requirements and above are the conclusions of what to possibly do.

##### 2020-03-07 Done No Planning or Docs Back Then

Circle 3 Strategy is pretty much done.
Circle 3 Requirements: change coloring and formatting.

That does not take away I want to split topics in these planning docs between language design one one end and programming at the other.

##### 2020-02-23 Done Reading Circle 3 Strategy

An idea for today would be to read "Circle 3 Strategy". That document is supposed to be about software development, not language design. At least, that is the new goal I have with that document. Some things in it are relevant for the Encircle Docs.  
"Goal of the Language" is where it is part about the language design, not so much the software development. I might use/move this text to the Encircle Planning Docs.  
Was at "More Tips" processing things.

At what point am I going to be more rigorous in splitting off the Encircle Planning Docs from the rest? Not yet, I think. It's still a mash up of both in the planning docs I am reading now.

##### 2020-02-20 Done Scoping

Today finished splitting time planning and projects step into in-scope and out-of-scope documents.

##### 2020-02-16 Done Notes

Working on splitting time planning and projects step into in-scope and out-of-scope documents. (worked on it for 45 minutes this day.

##### 2020-02-13 Done Scoping

Working on New Computer Language, Products.docx:

I do not want to necessarily want to shorten the list of products any further. Even the list of Done work. Because some parts are part done and it would be easier for me, would I work on it, to have the same subdivision of the pieces TODO as the pieces that are done.

What I do might want to change is the rough order in phases of the stuff TODO.  
I might just go over it a few times, reformulating.

I am splitting off parts of New Computer Language, Products.docx into a separate document with the out-of-scope things.  
I want to go over the Postponed topics, to see what content can be moved to the 'out-of-scope' document.

Now I still want to weed out the 'Topics Roughly' moving things to the 'out-of-scope' document with the products.

Also the Strategy can be stripped of things 'out-of-scope'.

##### 2020-01-13 Done Scoping

I read and reformulated some texts from "New Computer Language, Strategy.doc". 2 hours or so. I am now too tired.  
That document does not cover many things out of scope of language specification. It just briefly talks about programming experimental versions and licensing it and stuff, but little enough to keep it in there, were I to isolate this into a pure language specification writing project, which I intend it to.

##### 2020-01-04 Done Rough Plan

Rough plan:

- [x] Remove detail from products doc.
- [x] Split main planning docs into 2: content about the diagrammatic programming language and content outside of that subject area.
- [x] Or read some sub projects docs.

I had those plans with it, but did nothing about them this day.

##### 2019-12-29 Done Brainstorm Scope: Diagrams / Constructs / Gap Lifting

- [x] The application of them are different (of *diagrams, conceptual constructs* and *boundaries lifting*).
- [x] Proposed constructs: 
    - [x] Another example is the automatic diagram organization topics. The diagram notation idea can live without some of the wild ideas in that. For instance, interchangeability between containment and referential structure or inversibility of containment in case of bidirectional relationships. Also the striving to want almost all relationships between objects to be bidirectional, does not apply if you want to use the diagrams to express systems in which you have a choice if relationships are bidirectional or unidirectional. Also giving things a different name (aspects are all of a sudden called concepts) is not a priority, and perhaps even alienating. Those are just some ideas I have about how to pull things apart. 
- [x] I think maybe those differences in application call for a rigorous split up: *diagram notation / constructs drafts / gap lifting*. Diagram notation is a bit of a grey area, because it wants to use constructs. Some of the notation capabilities imply different variations of otherwise fixed constructs. I think a separation of some main groups of concepts is appropriate here, so the ideas are better transferable and perhaps better usable and applicable. It might make the general idea about the diagram notation more pure and also more freely usable, not in a fixed way. An argument that falls away when you open sourcing and not patenting or something, is that things do not need to have a closed, unambiguous definition. Things can be just part usable, using and replacing rules as one wishes. You can say at some point the diagram notation surpassed the original goal on two ends. I had somewhat of an explosion of ideas then surrounding this notation. Boundaries between ideas were not well defined. That's a (good?/bad?) quality of my way of thinking, I guess. But I tend to want to focus things, by splitting things apart in the main blocks, so it that it might become more practical (for others or myself).
- [x] "Encircle Language Spec" / "Encircle Language Broader View" / "Encircle Language JJ's Construct Proposals"
- [x] I don't like the last name. It seems long.
- [x] Proposals seems more community-based, not single authorish.
- [x] Language Spec vs Broader View:
    - [x] The idea that the diagram expression should be canonical and unambiguously express anything from any computer language, might not be a rule I want to uphold in the Encircle Language Spec docs. For instance if C# has certain rules for scoping of implied accessibility rules of members, you might not want to express that in a diagram. It sort of would make no sense if the diagrams are applied like a helper tool in Visual Studio to visualize certain aspects of C# code, to have symbols that disambiguate something, that is not ambiguous according to C#. The concept of canonicalizing things, may have a better place in Encircle Language Broader View docs, I mean to isolate from the Encircle Language Spec. A reason for unambiguous expression may only become clear, if you look at those ideas about possible broader applications of this notation: specifically where in a diagram you just switch from one source language to the next, by navigating the symbols. (E.g.: Now the diagram expresses something with C# as the source, navigate onward and you may see some diagram expressing something that came from JavaScript... the rules change, maybe the diagram expression should be unambiguous.) I think it is good and keeps it simpler and ideas less stuck on each other, to speak in options for diagram expression. There is a general theme in the expression. It is not all wishy washy, but there is wiggle room for how to use it. I just want to share the idea, not impose how it should be used.

##### 2019-12-29 Done Scope: Diagram Topics

Eventually, you might split the now in-scope topics apart in pieces that are in-scope and others that are out-of-scope. Some ideas just aren't the original ones, not a hot idea, and not prone to be adopted. For instance: The spaces in identifiers, text code ideas... I might have done good by keeping conceptual thoughts apart from diagram thoughts. I tend to want to merge those two aspects for the benefit of the reader. But I also tend to want a diagram notation that can be applied to other programming languages as a source for the diagrams. In that case, not all wild conceptual ideas are relevant. I did have thoughts: how would I implement this if I did it from the ground up, how would I implement that if I did it from the ground up, like interfaces, inheritance, ref-ness etc.

##### 2019-12-29 Done Brainstorm Scope (Useful)

- [x] Out of scope:
    - [x] 'Operating system' like components
    - [x] Studying
    - [x] Fundamental principles
        - [x] Basically all of them are probably out-of-scope.
        - [x] Do I limit the ambitions with the project?
        - [x] Do I remove fundamental principles that are questionable or irrelevant, like that the code base is written in C++, or things that may speed up development, things others could figure out, making how I feel about it not add much? Maybe ease up on things, talk less strict about things?
    - [x] 'Software System': an abstraction layer above the new computer language.
        - [x] ~~Even the large 'introduction' document to 'Software System': you might put part of it in one for 'language' and just refer to it from the main document.~~
        - [x] I think I should take interesting parts from the general Software System documentation.
        - [x] Then drop them somewhere in the Encircle Language Spec documentation.
        - [x] Also for the planning docs: there are Software System Documentation out-of-scope projects. Perhaps part of it was Encircle Language Design.
        - [x] > Not much usable content is still in scope.
    - [x] Computer language topics out-of-scope:
        - [x] Concepts / aspect oriented programming
        - [x] Database principles
        - [x] Concept libraries
        - [x] Machine language
        - [x] Internet as a single computer
        - [x] So many things, but I want to leave them out.
- [x] The data concepts and coding concepts thing, and the aspect oriented-like thing, I may want to put that out of scope. I might want to accept that the idea I present has limited potential, and might not apply to what you can do with a database, or ambitious aspect oriented programming ideas... just object oriented programming expressed in diagrams is enough. I did not have a clear idea back then how to merge the two or three concepts into that diagram language. I had some general ideas, but not entirely concrete. I should just leave it at that. That seems more achievable.

##### 2019-12-29 Done Brainstorm Scope

- [x] What do I do with things, that are out-of-scope? Do I just bluntly remove them from the documentation, or do I go through the trouble of parking the texts elsewhere?
- [x] Would I rename 'Computer Language' to something else, admitting it is a programming language, and only expressing the hope that it would become a language to a user to, where constructs are simpler. Do I simply admit that these were my ambitions with the project, and if people claim arrogance, then let them?
- [x] I am hoping at some point, the planning docs get smaller... because these documents are huge and intimidating.
- [x] Maybe I should just make 2 project folders eventually in the Planning Docs repository: one for the new computer language and one for the rest, that are much like eachother, but one stripped down to computer language functional design topics, and the other in which to dump the rest: anything deemed out-of-scope of the entire new computer language topic. Those are different than topics out-of-scope because postponed, but still much to do with the new computer language. Maybe at first, even 'worse', I make 2 documents in each folder: One with topics that belong to the new computer language, and another document much like it, in which the rest is put, that I would want to leave out of it.
- [x] I think a new concept to me, introduced in this new project is that: I do not need to do everything. Like this from "New Computer Language, Products.doc: "You have to be able to introduce new basic data structures and give them the nonagon symbol, and have different kinds of possible indexers, etcetera." I don't have to. I could do without. Ideas might be viable and interesting without all details being covered, without all proofs being given. I wanted to work out *everything* at some point. I also was a afraid, that if I didn't, people would not believe in the idea. Maybe I got over-ambitious, because I saw so much potential. I think I was able to work out a lot, but then I would get distracted by another project and then it turned out, I never got back to it. Scoping is a trick for that, when managing projects. Setting the boundaries and limitations of what the project would cover. I never wanted to do that back then. I wanted a framework in which everything would fit and then choose seemingly randomly what I would cover next. In one way I like the freedom of that. But on the other hand, it becomes a never ending story. I sometimes had the ambition of actually making *all* of it. I might have been able to create a playground in which I can go wild, but someone else would never want to cover all of that. Someone else would never take over your programming life, just a scoped programming project and then maybe. So I want to scope it. And lose the 'programming it out' part. And loose 'it is also a framework and an OS and any commonly used application'. It is actually quite hard for me to let go of that idea. I liked my playground back then. I wanted proof, that this could be used to realize software quicker, so one man can do what would have taken an army of programmers to do before. But I don't have that ambition anymore. Right now I just want to publically give away the programming language idea. I think I notice a lot of insecurities about people thinking it is a good idea or not. Maybe because I was trying to sell the idea, rather than just give it away? I get that I wanted a framework into which all of my ideas fit. I like some of the modularization of the concepts. But I do want to just cut away a few things. I think I am still trying to sell an idea, but then in a different way. I do not have the intention to sell it for cash, but I do want to not make it too ambitious, cover too much, so large in scope, that no one would pick it up anymore. 
- [x] The time planning document ("New Computer Language, Project Steps & Time Planning.doc") looks far more overviewable and less intimidating. It all seems so manageable there.
- [x] The document with the list of products ("New Computer Language, Products.doc") is overwhelming, because each article written is mentioned separately and that means almost each paragraph of produced writing is mentioned separately. If I would just mention the basic outlines, this might be better. Earlier, back then, it may have helped me see what I did and see how much I wanted to do. But with the goal I have now, I think it loses its purpose, and simplicity of the planning docs is more important than rigorous tooling for detailed planning of my own work.

##### 2019-12-15 Done Scoping

- [x] I read over the document "New Computer Language, Strategy.doc" in full and did some reformulations, also removing my never realized studying goals.

##### 2019-08-05 Done Brainstorm Restructuring Docs

The Encircle Planning Docs took a turn at some point in time. At one point it was mostly about documentation, then it became about both documentation and programming. But the planning docs folders do not seem to be fully updated to that change. Maybe I can do that in the context of *this* project. First some more reorientation.

'Program Software System' now looks 'outdated', compared to the programming work described in 'Document Software System'.  
I might actually move many of those topics from 'Future\Interesting Now' to 'Postponed'.  
I also would want to put a cut into all the planning docs and all the circle docs: this is the language and this is the rest.  
So it gets isolated. In the past I wanted to put everything I did (and will ever do) with software development at home in a single system so general that I called it 'Software System'. Many docs are general and describe both that language + OS-like topics and applications. I might want to cut that in two: language and the rest. I might like to open source the language at one point and just leave the rest out of it.

I think I interwove these things maybe a little too much. I just liked to subdivide things into a single system of subdivision into which everything fitted. Also, the interweaving may have been stimulated by my wanting to combine this 'Creator' project with the 'Encircle' language project. The 'Creator' project was about model-driven development, aspects and framework more than being a real computer language. I wanted to combine the two things into a single system, so that may have lead me to try and put everything into a single system. Now, I think I know that Encircle is the computer language and you could program model-driven aspect oriented software with it, if it can provide the aspect construct. Really, I think it helps to not try and solve all problems at once. 

### Planning | in General

#### Done

##### 2020-05-27 Done Brainstorm Priorities

- [x] I am not sure how to approach things right now.
- [x] ~~I could also try and pick a design issue from the list 'Language Design / Content Changes' above.~~
- [x] ~~I feel somehow I had more plans, but I forgot about them.~~
- [x] ~~Maybe there are few main problems I would like to highlight.~~
- [x] ~~Somehow I tend to want to just start at the top and start reformulating.~~
- [x] I guess I am not sure where to start.
- [x] And I am also still a little surprised that I am at this stage. I feel I must have forgotten something that must be left to do, before I can do this.
- [x] ~~I think maybe heavy redesign is off the table for now, because I estimate that would be too intense for now.~~
- [x] I also have in mind marking work as postponed for 'Encircle Broader View' and 'Encircle Construct Drafts', cleaning up the brainstorms that covert those + Encircle Language Spec. That way I might create overview over the TODO notes.
- [x] The feeling I forgot something, feels like it could be in the texts below, but the texts below seem to be too rough and unstructured to give me that insight and overview. If it were more structured and overviewable, and done stuff marked as done, postponed stuff marked as such and split into coherent chunks. I think I would like that.
- [x] So structure the TODO and Postponed things about Encircle Language Spec Revamp notes, might be what I want to do first.

##### 2019-08-05 Done Writing Style Mixed Issues

- [x] ~~The work might be modularized. I am not attracted to how CSS3 is modularized, each piece of specs with a different state of being finished up. It seems messy. But I can employ the same organization to accept certain concepts are just more crystalized out than others, making it easier to share, even in an unfinished state, and stimulating keeping things separated and separately usable even when other parts are just really still messy. > Scoped things more sharply instead, so more is finished up better percentually.~~
- [x] ~~I took a look at some of the postponed work. I worry about the messiness of the content. And if the loose ends will make the idea fall apart. And whether this makes it even fit for publishing. I just don't know. But I think I should come back to it later. Because I had strategies for this. And I might be too hard on myself. A clear 'flag' [Preliminary documentation] in red somewhere at the top usually does the trick. Might tell people clearly not to expect too much from the text that follows. Just being clear about that might be enough.~~

##### 2020-05-24 Done Notes Planning

- [x] Maybe merge more article together in the first chapters.
- [x] Maybe list out main language design issues.
- [x] ~~Some work in Future Sub-Projects may already be done.~~
    - [x] ~~> Applies to the TODO item 'Merge conceptual explanation with diagram explanation'. Those 2 things may now be put into the same article, but the explanations are still often 2 explanations instead of one. So I do not think I can call it done.~~

##### 2020-05-10 Done Brainstorm Effort

It may not be within my capacity to do some of the things I plan to do. Thinking critically about word usage and whether I am stating things too strictly... I feel this might not correspond with my energy budget. I made a careful conclusion about that before. Publishing might be more important, than if I might come off too strongly in the text. It feels like this effort is pulling me down more than I might be able to handle. It seems to be weighing on me.

Perhaps I can drop the goal of trying to use a different language style. My next goal was scoping. I seem to still be bargaining with the idea, like: "Maybe I can just reformulate when it *really* seems to harsh." I think maybe that won't work. Because I tend to evaluate the harshness, and this evaluation is 'jittery': sometimes it seems to be 'on', sometimes 'off', sometimes too on tightly, sometimes maybe too weakly. Perhaps I am better off dropping the whole goal of rewording it. I like learning to use language with more air in it, for my personal life for communication to others, or to prevent holding on too tightly to an idea. But this hobby project may need some air in it. Paradoxically, by not loosening up the language. I feel that writing new texts, I already seem to adopt a ligher way of conveying ideas. Evaluating existing texts seems harder.

I think I lean towards the decision of dropping the goal of reformulating texts to be more 'open'. I still have to get used to the idea.

Little reformulations here and there is something I do when reading over and editing my own texts. Some wording changes I might want to be tolerant towards. But the anxiousness might be something I want to let go of.

I feel like I recognize a personality in my own texts, that I adopted to hopefully be taken more seriously. I feel I am on a different wavelength now, or that I want to be.

So with that new perspective on the work, I was done and satisfied with the last page of the text I was working on within like a minute. Perhaps now I can focus more on what I actually chose to do: scope the project some more.

##### 2020-05-08 Done Brainstorm Priorities

- [x] Rewording the Done projects is getting a bit boring.
- [x] ~~Maybe wrap up Parameters planning doc.~~
- [x] Scoping was an alternative thing to focus on.
- [x] ~~Something else could be actually digging into the Encircle Language Spec docs themselves.~~
- [x] I think scoping is a better choice for now.
- [x] I want to go over the Encircle Language Spec Plan documents, moving things out of scope off the top of my head.
- [x] Side-goal: I read nicer docs, giving my head a bit of a break.
- [x] I think I will mark things with red before actually moving content out.
- [x] Still lots of definites in the wording of the main planning docs.
- [x] I do like too see it reworded it to nothing being a strict rule anymore and you can always make up your own mind. It seems this does not harm the integrity of the idea.

##### 2020-03-15 Done Planning

I read over notes to know where I was, and mark some things of as 'done'.

This was too intense. I wonder if starting to change documentation will be too intense too or if I should stop now. Or if other activities or non-activities will be even more intense. I choose to stop for a while now. After a little over 20 minutes.


Postponed
---------

### Tone Change | in General

#### Postponed

##### 2020-06-01 Postponed Checklist Tone Change

- [ ] ~ (More helpers are in my personal development notes, not here, sorry.)
- [ ] ~ Marking trigger words in red.
- [ ] ~ Possibly mark questionable trigger words with a star (*) too.
- [ ] ~ Finding replacement words, possibly using online thesaurus.
- [ ] ~ Vary natural language grammar constructs?
- [ ] ~ Going over the document again to reformulate.

##### 2020-04-18 Postponed Brainstorm Writing Style

- [ ] ~ The aim is to use less definite, more open language.
- [ ] ~ (I can view ideas on how in my personal development notes, not here, sorry.)
- [ ] ~ Also check: whether the stories make sense.
- [ ] ~ And whether the content is still in scope.
- [ ] ~ Remove links, since they break so easily.
- [ ] ~ Casual mentionings of article titles are also fragile. They break quite easily.
- [ ] ~ That seems quite a lot to check. Maybe that is why it is not easy.

##### 2020-05-27 Postponed Checklist Reformulating Chapters

- [x] Done projects:
    - [x] The postponed reformulation of the done projects is on my mind.
- [x] New Intro:
    - [x] But that makes me think: I want to give it a new beginning in the first place: use some of the old Symbol Language documentation and reformulate a gentler intro.
- [ ] ~ Reformulating:
    - [ ] ~ More open, less resolute language
    - [ ] ~ I could start reading and reformulating top to bottom.
    - [ ] ~ Introduction
        - [ ]  Applying trigger word marking technique to this already reworded document?
    - [ ] ~ For topics TODO / Done: See *Encircle Language Spec Product List*.

##### 2019-08-05 Postponed Mixed Writing Style Issues

- [ ] ~ The read uses terminology in a very specific way, that is not shared with my peers, therefor not easing readers into the material.
- [ ] ~ Rename the term 'Code Base' to something like 'Base Code' or 'Base of the Code'.
- [ ] ~ I seem to have had several goals fighting over each other, in projects done long ago about this documentation:
    - [ ] ~ Explaining it to myself.
    - [ ] ~ Designing the concepts, separately from the notation.
    - [ ] ~ Tying together loose ends.
    - [ ] ~ Making it easy to read for someone else.

##### 2019-08-27 Postponed Simpler Rules

- [ ] ~ I think the 'being blunt' might help. It is not blunt unfriendly, because the explanations might become so much simpler if you say: this is that, this is that, instead of and this far-fetched edge case is solved in this difficult, abstract, theoretical, but precisely determined way, that I'm not sure I even understand anymore... : )

#### Done

##### 2020-06-18 Done Brainstorm Reconsidering Writing Style

I seem to not like it when I make the rules for reformulating things so strict. It is sort of paradoxical too. The text produced is supposed to be not as strict, but the rule for making the text not strict, is strict.

It was supposed to feel like hobby.

I think I would like to change the rules by which I was reformulating these texts.  
I think I want to be more ok with words that seem to exaggerate or be quite strong. For instance "distinct", ''rule", "defined". Maybe I want to keep those words in there.  
I think I am noticing that many words just are black and white. If I use a thesaurus I get to see words that might also be quite strong.  
Maybe I can leave it with adding maybe's and perhapses and leave words that seem to express it strongly, in there.

Reasons for changing the way to do it might be:

- It seems to make me anxious being hyper aware of these 'forbidden' words.
- The text seems to now lack flair, and might not grab attention as well anymore.
- I feel I use more in between words, that carry not much meaning. It seems wordier than necessary.

I used to aim to be concise. In doing so, some thing might start to seem a bit commanding or something. But I did do my best then to make the text clear. Maybe this is not such a bad thing and maybe I was not doing that badly at it after all. Maybe just adding some wiggle words is enough, so that I might form an intermediate writing style. Perhaps that will be concise, strong, but leaving room for other options.

I would like to feel comfortable writing again. I would like to not do it 'wrong' like before, if that was even wrong.

##### 2020-05-31 Done Wiggle Word Difficulty

- [x] A less pleasant experience yesterday with the trigger word marking.
- [x] Still the problem that formulations not necessarily come naturally to me.
- [x] I liked describing a system of trigger words.
- [x] I also kind of liked picking them out, marking them red.
- [x] But trying to find alternate formulations for them, was tricky.
- [x] One thing that seems to bother me, is that I do not see that a rule is too fixated, until I have formulated it in a more open sense and sensed that it is feels closer to the truth. But I do not seem to read a resolute sentence and realize it could use wiggle room. I mostly just see a valid rule, not one too harshly stated.
- [x] Another aspect to consider is that formulating new sentences quite automatically I insert the wiggle words, probably because I did train myself a bit to use them more. But seeing the problem in existing texts is harder somehow.
- [x] I would like that after marking trigger words in red, it would be a matter of arbitrarily inserting wiggle words, removing adjectives or changing definite verbs to more polite ones.
- [x] But I end up scratching my head trying to find a way to reformulate something. Difficulty to find the 'nicest' alternate word, or sometimes even to realize something is even wrong with the trigger word I marked in red.
- [x] Sometimes my brain says: nothing is wrong with trigger word, but when I replaced it with difficulty, I realize the trigger word did seemed to be 'wrong' after all, and realize that things are not necessarily that black and white.
- [x] But my mind, that is reading and understanding these existing sentences does not sense anything wrong with them really, so has difficulty finding a proper way to change it, or even a reason. It's it like my mind resists changing the sentence, because at first I fail to see why.
- [x] An additional problem seems to be that I have very little energy. This computer hobby usually takes little energy. I am built that way. But certain things about it do take energy. This task seems to tap into something my mind does not automatically do naturally or easily. Not sure why. It just takes too much effort.
- [x] I kept re-evaluating the sentence as rewritten: whether it 'walked' well, whether it still made sense, whether the wording is varied enough in the document as a whole. That might be a lot of language processing for me right now.
- [x] So after this reflection I am left with a question: How to proceed?
- [x] Alternative: I am not sure, but could I proceed the same way, and just hope I will have more energy now?
- [x] Alternative: It may need focus to try and insert wiggle words sort of 'robotically', maybe not even looking at the meaning of the sentences.
- [x] > One alternative seems to need energy. The other altenative seems to need focus. Neither is aplenty.
- [x] Alternative: Build up more wiggle word dictionary. May be hard, because thinking of alternate words seems energy draining.
- [x] Limitation: That the document I work on now goes from one topic to the next, might not help me.
- [x] Limitation: Switching between the chapter content and the overview content is probably difficult switching for me.
- [x] Limitation: Doing it in a way to avoid where my problems are, requires focus, which seems to be a problem in itself.
- [x] Limitation: I think maybe language processing is problematic for me right now.
- [x] Alternative: Using the existing wiggle word dictionary, inserting wiggle words robotically. No careful evaluation.
- [x] I do estimate that the above should be the kind of thing I used to be good at. But focus was the problem yesterday. Could not hold myself to a plan anymore yesterday, I guess. Maybe I can today.
- [x] Helper: Putting up a Post It: "Insert wiggle words robotically", for focus.
- [x] Helper: Keeping the wiggle room dictionary closed? (prevent switching)
- [x] Helper: Use thesaurus.com for words.
- [x] One problem I see with 'insert wiggle words robotically', is that inserting wiggle words was not my only goal editing this documentation. Maybe I can make wiggle words one phase and reformulation a second phase, and not do it in one blow, because it seems to make it more difficult. I just do not want to forget that I also want to make the text better content-wise, not just change the tone.
- [x] While doing it:
    - [x] Accept limited word variation at first?
    - [x] Yes, when I cannot find a word, it is hard on me.
    - [x] Sometimes a text might be deprecated. Saves some reformulation, but may personally mean more information processing > more easily tired.

##### 2020-04-18 Done Brainstorm Writing Style

- [x] ~~It kind of bothers me that the story starts in the middle. Where are the other sub-project descriptions? Maybe mixed with other big projects, like 'Software System Documentation'. Maybe.~~
- [x] Brainstorm: I worry a lot if the words come off too strongly. On top of that I am not in a very subtle mood right now. If I was feeling more calm and friendly, I might have better judgement about it. Maybe I cannot do this right now. I can only judge language constructions, not whether it feels right. When my base line mood would be calm and friendly, I can just feel whether the words bump with that or not. That might be easier. Sometimes just using calmer language, makes me calmer, but right now it does not seem to be working.
- [x] Wording:
    - [x] Is it really such a problem, that I talk in definites about steps taken and rules of the systematics as I try to work them out? Maybe in talk like that, still add a 'might'. Imagine what if you would not explain to yourself, but to someone else that has to work it out further. Imagine what it would feel like if someone else read it. Like you're being dictated rules, perhaps.
    - [x] After that I might want to change command-like sentences and rule-like statements, to just add 'might' to it or other wiggle words. I would talk to myself that way, just maybe comes off harsh. Maybe being less strict towards myself is also not a bad idea.
    - [x] Added maybe's.
    - [x] Perhaps after that a reformulation phase. I tend to come up with nicer flowing alternatives to just the word 'maybe'.
- [x] Brainstorm wording:
    - [x] Maybe I go a different direction with this.
    - [x] With my gut I might assess whether the language is too blunt or not.
    - [x] Maybe if it just list things, that actually happened, then it might not be much of a problem.
    - [x] Definite language to create a pseudo-truth for a false sense of control, might be a problem.
    - [x] Things stated as rules, that are not hard rules might be a problem.
    - [x] When setting rules to follow a plan, wiggle words might be helpful.
    - [x] Black and white opinion about something that may or may not be true, might be a problem.
    - [x] In some sentences it seems more obvious. If they sound opinionated and black-and-white.
    - [x] Maybe I am looking for clues in texts where there are none. Sort of like when I am driving and see no other traffic, I am scared that there may be traffic, that I am not seeing.
    - [x] Words like 'annoying' or 'constantly' trigger more easily. Stating something as definite, without 'maybe's seems a more subtle 'problem'.

##### 2008-08-31 Done Writing Style Ideas

Encircle Language Spec, Writing Style,  
2008-08-31

Sometimes it is just clearer to have an article, with diagrams in it straight away, without any article with just textual explanations. In the future, the whole form of the documentation might change as such and have diagram expression be more present in the conceptual explanations.

JJ

### Commands | Tone Change

#### Postponed

##### 2020-07-24 Postponed Checklist Reformulating Commands Main Concepts Article

- [x] Fine-tune styling.
- [ ] ~ Evaluating if texts are in scope, possibly moving them.
    - [ ] ~ But most sections seem appropriate and in-scope to me, except maybe the bottom edge-cases, but I think I will get to that in time eventually.
    - [ ] ~ Commands Anywhere has a Broader View feel to it according to my opinion.
    - [ ] ~ Terms "In" and "Out" might be avoided.
        - [ ] ~ I seemed to be juggling the concepts Get and Set on one hand and In and Out on the other, before realizing they might not be synonymous.
        - [ ] ~ I seem to go into specifics about Input/Output. I might want to move those specifics out at one point. I think I would like to evaluate that as I sequentially go through the text.
        - [ ] ~ I might actually move the section where those terms are used: move them from the Commands chapter to the Parameters chapter.
        - [ ] ~ Perhaps later be honest in the Parameters article about this paradox. Other people may also feel uneasy about it and it makes it maybe more understandable why the terms are avoided.
- [ ] ~ Marking trigger words in red.
    - [x] With find and replace
    - [x] Manually
    - [ ] ~ Over-used words?
        - [x] "The"?
- [ ] ~ Finding replacement words, possibly using online thesaurus.
    - [ ] ~ Going through text sequentially.
    - [ ] ~ Sometimes moving things to an 'Out of Scope' section.
    - [ ] ~ Terms "In" and "Out" might be avoided.
        - [ ] ~ Because it seems ambiguous (for instance an object reference (__'Object In__' parameter?) can be considered both input and output at the same time.)
        - [ ] ~ Replacement terms might be ones such as __Get Object__ Parameter or __Set Value__ Parameter. It may not look as pretty, but it might help me avoid the paradox that I experience if I were to call them __In__ and __Out__.
- [ ] ~ Put subjectivity in perspective.
- [ ] ~ Change the orange markings (pictures, texts to move or change).
- [ ] ~ Pictures:
    - [ ] ~ Maybe draw new ones in one go, on paper and then scan it.
    - [ ] ~ Sometimes borrow (pieces of) other pictures
    - [ ] ~ Or simplify pictures by editing them.
- [ ] ~ Merge conceptual/diagram explanations:
    - [ ] ~ When I reformulate things top to bottom, I might at one point feel that the merging of conceptual explanation and diagram explanation is actually finished, because right now, often they are put near each other, but not really became one merged text.
- [ ] ~ I have difficulty not wanting to change the story, while the aim is to just reword it, and I seem to experience an impossibility not absorbing the story. My conundrum might be solved, by adding indicators that everything is just a suggestion, so that no idea would disrupt anything, even when I may not entirely agree with it myself. Sometimes I might do the changes anyway.
- [ ] ~ Going over the document again to reformulate.
- [ ] ~ I might go over the loose ideas in the document and cross out or distribute those.
- [ ] ~ Spell check.


### System Objects | Tone Change

#### Done

##### 2020-06-26 Done Reformulating System Objects Article

- [x] Fine-tune styling.
- [x] Evaluating if texts are in scope, possibly moving them.
- [x] Marking trigger words in red.
    - [x] With find and replace
    - [x] Manually
    - [x] Over-used words? "The", "related"?
- [x] Finding replacement words, possibly using online thesaurus.
    - [x] "Relation" => "Relationship"?
- [x] Put subjectivity in perspective.
- [x] Change the orange markings (pictures, texts to move).
    - [x] Maybe I forgot to merge the conceptual description with diagram demonstration.
- [x] More over-used words / trigger words?
    - [x] "The"
    - [x] "Full"
        - [x] I still might be stating half-truths where I use trigger words. I do not seem to notice it at first. I just said 'full system interface' but later I introduce more members, so is the word 'full' appropriate? This raises insecurity with me. I often do not even seem to see it happen.
- [x] Going over the document again to reformulate.
    - [x] Temporarily taken out:
        - [x] It could be used by other system objects to wrap an object reference into context.
        - [x] A reference may come into play when objects relate to each other.
    - [x] I have difficulty processing the info/reading.
- [x] Pictures:
    - [x] "System Interface for the Class Aspect"
        - [x] Not many pictures here.
        - [x] Each sentence might call for the question: how would that look in a diagram? Some of it might not even be clear to me. I might want to consider one by one.
    - [x] Maybe draw new ones in one go, on paper and then scan it.
    - [x] Sometimes borrow (pieces of) other pictures
    - [x] Or simplify pictures by editing them.
- [x] Merge conceptual/diagram explanations:
    - [x] When I reformulate things top to bottom, I might at one point feel that the merging of conceptual explanation and diagram explanation is actually finished, because right now, often they are put near each other, but not really became one merged text.
    - [x] More prominently the possible merging of System Commands and System Interface sections.
    - [x] (I wonder if System Commands and System Interfaces could become 1 section, because is the System Interfaces section(s) the visualization of the System Commands? I tend to not like conceptual explanations without accompanying diagrams anymore, so perhaps.)
- [x] I have difficulty not wanting to change the story, while the aim is to just reword it, and I seem to experience an impossibility not absorbing the story. My conundrum might be solved, by adding indicators that everything is just a suggestion, so that no idea would disrupt anything, even when I may not entirely agree with it myself.

#### Postponed

##### 2020-07-04 Postponed Checklist Reformulating System Command Call Notations Article

- [x] Fine-tune styling.
- [ ] ~ Evaluating if texts are in scope, possibly moving them.
- [ ] ~ Marking trigger words in red.
    - [ ] ~ With find and replace
    - [ ] ~ Manually
    - [ ] ~ Over-used words? "The"?
    - [x] Rename "Object Get" to "Get Object" etc.
        - [ ] ~ Did not do it in the pictures.
- [ ] ~ Finding replacement words, possibly using online thesaurus.
- [ ] ~ Put subjectivity in perspective.
- [ ] ~ Change the orange markings (pictures, texts to move or change).
- [ ] ~ Pictures:
    - [ ] ~ Maybe draw new ones in one go, on paper and then scan it.
    - [ ] ~ Sometimes borrow (pieces of) other pictures
    - [ ] ~ Or simplify pictures by editing them.
- [ ] ~ Merge conceptual/diagram explanations:
    - [ ] ~ When I reformulate things top to bottom, I might at one point feel that the merging of conceptual explanation and diagram explanation is actually finished, because right now, often they are put near each other, but not really became one merged text.
- [ ] ~ I have difficulty not wanting to change the story, while the aim is to just reword it, and I seem to experience an impossibility not absorbing the story. My conundrum might be solved, by adding indicators that everything is just a suggestion, so that no idea would disrupt anything, even when I may not entirely agree with it myself. Sometimes I might do the changes anyway.
- [ ] ~ Going over the document again to reformulate.
- [ ] ~ Spell check.


### Planning Docs | Tone Change

#### Done

##### 2020-04-13 Done Brainstorm Reword Circle Language Spec Planning Docs

- Reformulate:
    - I would want to read over those Done projects content before publishing. I should know what I publish exactly and have evaluated it and made some adaptations possibly. Probably nothing in it is a secret, so you don't need to remove it from source control history, but slight changes might be good.
    - I did not read the content of the sub-projects or the idea box.
    - I think, I guess, I would want to go through content top-down for reformulations?
- Tone:
    - Some things especially in evaluations may seem cocky when I call my own successes very, very good. I don't know if I need to change that. I also use I and you interchangedly when I talk about myself. Not sure if I have to change that. The plans sometimes talk in definites. Maybe openness is better language, I mean more wiggle room in the wording. Not sure if that's a problem.
    - I worry what people would think of me. If they'd think I'm arrogant... maybe I should not worry about that.
    - Cockiness/speaking in definites, and scope/out-of-scope are 2 different things. My intermediate goal now was to change the tone, not to change the scope covered by the documents? There are still gray areas of scope. I think I should deal with that later?

##### 2020-04-18 Done Reword 2008-07 02        Assignment Spec Project Summary.docx

- [x] Adding maybe's and perhapses.
- [x] Second phase reformulating > Did not change much, but did change a few things.
- [x] The word 'you' seems overly used. Try to reformulate to object-centric grammar, instead of person-centric.
- [x] Maybe read one more time for possible small typing errors.

##### 2020-04-18 Done Reword 2008-05 02 Classes & Relationships Specs Project Summary.docx

- [x] ~~Rename "Relationship" => "Relationship" > I would keep the term relationship in there for now, otherwise I would have to go through so much documentation. If I refer to a product with the work relationship in it and change it in the planning docs, then I also would have to change it in the language spec docs and that is just a whole lot of work. I briefly looked up a discussion online about these words, and it does not seem people can find a really clear distinction or rule, just wishy washy hand wavy stuff, I think. It's just that in IT the term is usually 'relationship'. In the spirit of not alienating readers you might change it, but it does not seem semantically incorrect would you accidentally use the word 'relationship' instead.~~

##### 2020-04-18 Done Reword 2008-06 02 Command as a Concept Spec Project Summary.docx

- [x] It mentions topics very much out of scope.
- [x] I think it might not be harmful to keep that mentioning in there.
- [x] Maybe I am trying to hide the out-of-scope topics too rigorously.
- [x] There seem to be maybe's and perhapses missing, but it does not seem to sound too blunt.
- [x] Reconsider to split into in-scope and out-of-scope parts.
- [x] Brainstorm: The input / output topics is so present in this sub-project description. It does not seem lightly touching the topic. Sometimes it is half a paragraph that goes on about just that, while it is not in-scope anymore. Maybe it is worth trying to extract it out, so the summaries of the work become simpler.

##### 2020-04-18 Done Reword 2008-06 03        Clarify Command as a Concept Spec Project Summary.docx

- [x] I would like to look at the end-result of the project 'Clarify Command as a Concept Spec' to see if the description of the work done still makes sense if you split it in two.
- [x] Maybe the sub-project Clarify Command as a Concept is mostly out-of-scope.
- [x] That whole project should be out of scope, because the end-result is just about input/output and concurrency resolution.
- [x] That would change the super project description too.

##### 2020-04-18 Done Reword 2008-07 01        System Objects Spec Project Summary.docx

- [x] Maybe reformulate harsher words, rather than understanding the text of all the notes. The notes are really unpolished.
- [x] > Was at 'Other Issues' taking out the more harsh wordings.
- [x] I see the difficulty of using the words 'concept' vs. 'aspect'. I want to call it 'aspects' everywhere. But contradictory: 'aspects' is now considered out of scope, while I cannot easily prevent mentioning it at all, because it was in the back of my head during some of these projects. I also have this a little with the term 'code base' which I want to rename to 'base of the code', because 'code base' is a term often used differently in IT.
- [x] Out of scope ideas:
    - [x] I see this document talks about what I would rather call a runtime. Figuring out how Encircle could work stand-alone up and running is probably not in the scope of this project anymore. Just describing the language, mostly the diagram notation, is.
    - [x] I see a sentence where I call the System Objects essential for the workings of Encircle. But if you see the notation as separate from the runtime it does not seem that essential.
    - [x] So how do I reword this putting these ideas out of scope, without harming the integrity of the content?
    - [x] Hyp: In the original text I express that I feel system objects are essential, as a run-time, not for the notation.
    - [x] I keep seeing the idea of a runtime back. It's an interesting idea, but not in the anymore scope as I want to isolate it. I am reluctant to remove the text, because it is so nicely descriptive about that idea.
    - [x] All in all, I am still uneasy about multiple subjects now considered out of scope, being intermixed in the texts of this sub-project description.
    - [x] The 'other issues' seems to contain loose ideas not fully worked out, part of the aspects construct for instance, or about a run-time. It seems to me some of those ideas, e.g. under 'Other Issues' could be cut-pasted to out-of-scope Encircle Language projects.
    - [x] It seems the System Objects Spec Project Summary has a some content that is maybe lazily left in there, while they are also like future ideas?
    - [x] Q: The things that I now consider out of scope, that are mentioned in the sub-project planning documentation for System Objects, are those things even inside the actual language spec content for System Objects? Or is the language spec content also littered with now consider out of scope content?
    - [x] I read most of the content of the System Objects chapter. I forgot what for. To assess whether the topics in the planning docs about it even made it into the documentation. Maybe I can assess that later.
    - [x] Read the sub-project documentation again, to see if some things can be moved out-of-scope?
    - [x] As I read the first sentences of the sub-project planning doc, I tend to want to redescribe it, now I can put it into context. As I explain that context, the integrity of the planning doc seems in tact again.
    - [x] I want to keep reading over and reformulating.

##### 2020-04-18 Done Reword The Done Encircle Language Spec Planning Docs

- [x] Ideas document: ISNSE = Internet as a Single Computer > But why? Internet aS a[N] Single Entity?
- [x] Brainstorm: Scope the Done projects?
    - [x] I was already putting things out of scope, not just reformulating. I have done that for the Future projects, because putting it out of scope was easier than reformulating some of the difficult text. Maybe that rule does not hold up for reformulating the Done projects. I want to realize that the focus is on reformulation, not scoping. Only if it helps me get through the reformulations, I may want to also fine-tune the scoping in the planning docs.
    - [x] So the same argument kind of applies. If I know it is out of scope, I can just move it without further reformulation.
    - [x] Fortunately I am quite clear on what I put out of scope.
    - [x] Q: Will all 'fundamental principles' be put out of scope?
    - [x] Exp: Read some of the actual documentation.
    - [x] A: Yes, 'fundamental principles' is out of scope with the current ideas I have now.
    - [x] By the way: I saw '2. Concurrency' under '3. Operating System' in the Encircle Docs. I couldn't find that content before. Found it.
- [x] I tend to want to subdivide all the Done projects into groups, like I did the Future projects. (in the Other folder, not Encircle Language Spec).
    - [x] But I get cramps in my face.
    - [x] It's hard, because it means processing many disparate pieces of information, which takes too much energy/strain for me.
    - [x] Feels bad to leave a grouping/categorization half- finished.
    - [x] Can I make this easier for myself? Dim the screen. Dark mode would have been nice, but don't have it on Windows 7. Take it slower. Worry less about (small) mistakes. Accept this will take a while. Forget about everything else?
- [x] Done projects (now out of scope)
    - [x] ~~2008-03 02        Fundamental Principles Spec Part A Project Summary.docx"~~
    - [x] ~~2008-03 03             Orient in First Four Fundamental Principles Project Summary.docx~~
    - [x] ~~2008-03 04             Computer Language Programmed Within Itself Spec Project Summary.docx~~
    - [x] ~~2008-03 05             Generic, No Generators Spec, Project Summary.docx~~
    - [x] ~~2008-04 02        Get Clearer View over Difficult Topics Project Summary.docx~~

##### 2020-04-18 Done Encircle Language Spec Planning Docs: Reword Main Project and Future Sub-Projects

- [x] The aim is to use less definite, more open, language and to take out the personal 'I' form.
- [x] I think a lot of documents do not contain as much prose as Encircle Language Spec Strategy, so maybe things are doable after all. Also it does not drain my energy much. It is relaxing work to me. So I am not sure how much it matters, how long it takes.
- [x] ~~Limitation: I choose to not reorganize/resubdivide the sub projects. I choose to just change the wording.~~
- [x] Main Project
    - [x] Mostly finished rewriting the content.
- [x] Future Sub-Projects
    - [x] Assignment Spec Update Ideas.md
    - [x] ~~Automatic Containment Spec Plan.docx~~
        - [x] ~~Split up topics about Diagram Metrics from Automatic Containment: two topics. Those intertwine in those two documents.~~
        - [x] ~~Automatic Containment was going to be put out of scope, because it is so difficult and really in the way of explaining how to use these diagrams normally.~~
        - [x] ~~I said I would focus on reformulating, not on scoping, but I just don't want to reformulate this content, it is so unclear.~~
        - [x] ~~Would I simply move more to the 'out-of-scope' document? I doubt, because I moved 'Errors' and the 'Concept Construct' from out-of-scope to in-scope but postponed, because they 'felt' part of the language. Now the scoping rules change and I am wondering about how to organize things for a moment.~~
        - [x] ~~Looking at the folder subdivision of the planning docs, it does seem like it should be moved there. And so does the concept construct. Moved back again.~~
    - [x] Classes Spec Update Ideas.md
    - [x] Commands Spec Update Ideas.md
    - [x] Concept Construct Spec Project Summary.docx
        - [x] Move out-of-scope.
    - [x] Concepts as External Modules Spec Goal (2008-05) (postponed).docx
        - [x] Move out-of-scope.
    - [x] Concurrency Resolution Spec Project Summary.docx
        - [x] Move out-of-scope.
        - [x] 'Advanced Input/Output' is Concurrency Resolution?
        - [x] There is overlap, but I'm not sure. If I read over the product list, I think I'd have to look into it deeper to determine if all of that Input/Output stuff is up for postponement. 
        - [x] I have looked at multiple sources of information, but cannot determine yet if the topics mentioned under the Input Output section of the Products List are in scope or out of scope, due to the concurrency resolution's being in-scope and out-of-scope.
        - [x] ~~I feel part of the TODO products are already done.~~
        - [x] ~~I feel 'normal' parameter topic are intermixed with concurrency resolution / automatic execution order too much?~~
        - [x] Or is it to shed new light on these topics in the area of automatic execution order?
        - [x] ~~Alternative: Split apart in two: The parts / product list items, that I know are about concurrency resolution / automatic execution order would be put out of scope and then parts I am not sure about, would stay in in-scope with some comment shedding light on that doubt.~~
        - [x] Exp: Read over a product list in the Future Sub-Project document "Input Output Spec Project Summary.docx".
        - [x] Hyp: All the topics under Input / Output inside the main "Encircle Language Spec Product List.docx" are not trivial parameter topics, but more a small ramp of parameter topics leading towards the automatic execution order concept.
        - [x] ~~Hyp: But the Integration of Parameter Input/Output Concepts do seem already done topics.~~
        - [x] Hyp: But may fall under the same umbrella: now put into the light of automatic execution order.
        - [x] Parameters and input/output concepts entangle. The proposed product list would aim to disentangle those topics and explain their precise relationship.
        - [x] I had a brainstorm. I put that in the Future Sub-Project doc in the out of scope folder.
    - [x] Diagram Metrics Ideas.md
    - [x] Diagrams, Coding Principles & Coding Concepts Plan (old).docx
        - [x] At first glance, this seems to have the same scope as the whole project Encircle Language Spec.
        - [x] Maybe it can be thrown away (or archived), because it's already described by newer documents.
    - [x] `Execution Control Spec Update Ideas.md`
    - [x] `Module Spec Update Ideas.md`
    - [x] `Objects Multiplicity Spec Ideas.md`
    - [x] `Objects Spec Update Idea.md`
    - [x] `Parameters Spec Update Ideas.md`
    - [x] `Relationships Spec Update Ideas.md`
    - [x] `Static Spec Idea.md`
        - [x] The second half is an idea, that is explanatory on some of my ideas about static. But also it uses a concept I want to put out of scope: Code = Data. I want to save such concepts for 'Encircle Language JJ's Construct Proposals' or something.
        - [x] I would not want to remove it, if I look at that it explains how I see 'static' in a broader view.
        - [x] But to understand my own doubts about the different ways to see the concept of 'static' that idea description explains a lot and otherwise I might think: where did that idea go and how does it work?
        - [x] I feel that this concept of static might have a place in the general descriptions, but to apply this to the concept of Code = Data, though interesting to me, might not have to be part of that, because it may confuse and alienate the reader, who might be more familiar with more regular implementations of the concept.
    - [x] `System Objects Spec Update Ideas.md`
    - [x] Text Code Spec Project Summary.docx
        - [x] Out of scope
        - [x] But change the main project description too.

##### 2020-04-18 Done Encircle Language Spec Planning Docs: Format the Project Summaries

- [x] Change formatting in bulk (of Done Projects / Project Summaries)
    - [x] Change fonts and layout in bulk first.
        - [x] All normal text Calibri 11.
        - [x] Heading 2:
            - [x] Use heading 2 for e.g. 'Goal' and 'Date & Time'.
            - [x] Heading 2 Calibri 10 bold, 9pt before, 9pt after
            - [x] Instead of 'Dates' say 'Date & Time'
            - [x] Americanish heading case usage
        - [x] Sub-title:
            - [x] Author and location Calibri 10, italic, 0.5 cm indented
            - [x] No 'date' subtitle, since it is implied by the content of heading 1
            - [x] Make spacing uniform.
        - [x] Indent of normal text is not consistent among documents.
        - [x] Heading 1:
            - [x] Heading 1 month in separate line
            - [x] Heading 1 no comma's at the end of the lines
            - [x] Shorter heading 1
            - [x] Heading 1 Calibri
        - [x] Maybe double-check the formatting afterwards by opening all documents on top of each other, closing them one by one, to see if all is uniform.
        - [x] Forgot the Done projects that have their own folder.
            - [x] > They use different templates, so this formatting and making consisntent, probably does not apply to those.
        - [x] Don't Future Sub-Projects also have documents in that 'project summary' format?
            - [x] Alternative: format those too.
            - [x] Alternative: Go look for more project summaries in the Encircle Language Spec Plan folders.
            - [x] ~~Alternative: Don't do it.~~

##### 2020-04-13 Done Encircle Language Spec Planning Docs

- [x] I made a slight beginning with a next phase of scoping the project. But I want to turn back. 
- [x] Check if I can check this in.
- [x] Do reformulations while maintaining the current scoping.
- [x] This is a lot of work. I am not even sure if I can do it.
- [x] It being forbidden to use the word 'I' and to be afraid to come off cocky... those are very strict rules to set for myself. Maybe too strict. I have trouble with this. Time may be better spent on something else.
- [x] It's weird that if you want to make a project public property, it is strange to have the word 'I' in a project definition. In notes, maybe, but in central project definition it may be weird... But changing this just conflicts with my lack of energy.
- [x] In my efforts to speak in a non-personal tense, I sometimes switch to the 'you' form and then it just sounds like I can't even keep the terms 'I' and 'you' apart... maybe I am over-conscientious and insecure here. 'You' is fine if you explain how one might experience something.
- [x] I read some articles over personal and impersonal forms of language like that.

##### 2020-01-30 Done Reformulating Planning Docs

I read over New Computer Language, Strategy.doc and reformulated stuff.
I am cleaning up New Computer Language, Products.doc: simplified color coding, removed mentioning 'in a Diagram' and 'in Text Code' article variations. I might remove detail from done work, but keep it in the proposed work. May remove some 'musts' by 'mays'. Might add intro docs to calm the reader's nerves down, on the overwhelming amount of topics. Do I need to excuse myself for introducing topic names, without actually describing what it entails? Don't know. That description would *be* the product. I have a conundrum. I cannot describe the product without making the product, because the description is the product.

#### Postponed

##### 2020-04-18 Postponed Reword 'Done' Planning Docs

- [x] 2008-05 01 Diagram Expression Specs Project Summary.docx
- [x] 2008-05 02 Classes & Relationships Specs Project Summary.docx
- [x] 2008-06 01 Execution Control Spec Project Summary.docx
- [x] 2008-06 02 Command as a Concept Spec Project Summary.docx
- [x] 2008-06 03        Clarify Command as a Concept Spec Project Summary.docx
- [x] 2008-07 01        System Objects Spec Project Summary.docx
- [x] 2008-07 02        Assignment Spec Project Summary.docx
- [x] 2008-08 00        Commands Spec Project Summary.docx
- [x] 2008-09 01        Organize Encircle Language Ideas Project Summary.docx
- [x] 2008-09 02        Parameters Spec Plan.docx
- [x] 2008-10 01 Scatter Symbol Language Documentation Content Project Summmary.docx
- [x] 2009-06 01 Encircle Language Spec Plan Part B, Sub-Projects.docx
- [ ] ~ 2009-06 02 Encircle Language Spec Plan Part B, Evaluation.docx
    - [ ] ~ > Stopped, because I seem panicky about which words to pick and whether someone might be rubbed the wrong way with it somehow.
- [ ] ~ 2009-06 01 Planning + Black Box Spec Part A, Eventual Plan, Goal Description.docx
- [ ] ~ 2009-06 02 Planning + Black Box Spec Part A, Eventual Plan, Elements.docx
- [ ] ~ 2009-06 03 Planning + Black Box Spec Part A, Evaluation.docx
- [ ] ~ 2009-06 04 Planning + Black Box Spec Part A, Initial Plan, Goal Description.docx
- [ ] ~ 2009-06 05 Planning + Black Box Spec Part A, Initial Plan, Elements & Time Estimation.docx
- [ ] ~ 2009-06 01 Planning + Black Box Spec Part A, Notes, Startup.docx
- [ ] ~ 2009-06 02 Planning + Black Box Spec Part A, Notes, Cycle 1, Process Idea Box.docx
- [ ] ~ 2009-06 03 Planning + Black Box Spec Part A, Notes, Cycle 2, Black Box Part A.docx
- [ ] ~ 2009-06 04 Planning + Black Box Spec Part A, Notes, Cycle 3, Redo System Objects & Assignment Part A.docx
- [ ] ~ 2009-06 05 Planning + Black Box Spec Part A, Notes, Wrap Up.docx
- [ ] ~ 2009-08 Review by Ramses, Small Plan.docx
- [ ] ~ 2009-09 01 Wrap Up Black Box, System Objects & Assignment Specs, Goal.docx
- [ ] ~ 2009-09 02 Wrap Up Black Box, System Objects & Assignment Specs, Startup.docx
- [ ] ~ 2009-09 03 Wrap Up Black Box, System Objects & Assignment Specs, Implementation.docx
- [ ] ~ 2009-09 04 Wrap Up Black Box, System Objects & Assignment Specs, Wrap-Up.docx
- [ ] ~ 2010-02 01 Interfaces Spec, Strategy.docx
- [ ] ~ 2010-02 02 Interfaces Spec, Product List.docx
- [ ] ~ 2010-02 03 Interfaces Spec, Steps.docx
- [ ] ~ 2010-02 04 Interfaces Spec, Evaluation.docx
- [ ] ~ 2010-05 01 Events Spec, Strategy.docx
- [ ] ~ 2010-05 02 Events Spec, Product List.docx
- [ ] ~ 2010-05 03 Events Spec, Steps.docx
- [ ] ~ 2010-05 04 Events Spec, Evaluation.docx
- [ ] ~ 2010-05 01 Inheritance Spec, Strategy & Steps.docx
- [ ] ~ 2010-05 02 Inheritance Spec, Products List.docx


Done
----

### Search Tools

#### 2020-04-09 Done Explore (Content) Search Options

- [x] Exp: Visual Studio Find in Files
- [x] Obs~ Some paths are too long...
- [x] The file had a path of 260, which I think is the max for Windows 7, but some API's use 255 as a max.
- [x] Exp: Shorten to 255. Find in Files again
- [x] Obs~ Error is gone.
- [x] Exp: Get rid of an intermediate folder to shorten the path and still keep descriptive names.
- [x] Obs~ Visual Studio Find in Files will not search doc contents.
- [x] Hyp:    Windows 7 File Explorer will not find whole words. For some things that's relevant for other things it is not. (I thought I saw it).
- [x] Exp: search "*.doc"
- [x] Obs: Now it does not match "*.docx".
- [x] Hyp: I thought I saw that some times.
- [x] Exp: Windows 7 File Explorer. "D:\Source\JJs Software\Project Docs\Encircle Language Spec Plan". Search "content:Joost".
- [x] Obs~ It shows 2 files, if I open them (docx's) and search for Joost in Microsoft Word, I get no result. Odd.
- [x] Hyp: File properties?

### Planning Docs | Content Changes

#### 2020-04-15 Done Encircle Language Spec Planning Docs

- [x] I finished 'Encircle Language Spec Strategy'.
- [x] 'Encircle Language Spec Product List' seems finished.
- [x] The word 'Legacy' is in there, which I tried to avoid.
    - [x] Integration was not the best word, it seemed.
    - [x] 'Inherited' is too ambiguous a term.
    - [x] It is because other languages have those concepts?
    - [x] Oh, wait, it is my own subdivision.
    - [x] Maybe the word Legacy is ok there, because there is only the danger of putting down my own work, not others'.
    - [x] It seems like it could be both.
    - [x] 'Existing' is a little ambiguous too.
    - [x] Why was integrate such a bad word according to my brother?
    - [x] Synonyms?
    - [x] I am going for 'integrate'.
- [x] 'Encircle Language Spec Steps & Time Planning' should be next.
    - [x] Yeah, has definite language, that might need more wiggle room.
    - [x] Sometimes I don't even notice it, because I am so used to try and gain a sense of control over the situation, that I just speak in definites.
    - [x] Resolute language is solved.
    - [x] 'Overview for Progress Monitoring' is not the same list as the scored and prioritized work items above it.
    - [x] Why is there even a separate list for 'Progress Monitoring'? It seems handy for quick overview, but why is the main list not quickly giving that overview then? Improve the main list instead and remove the 'Overview for Progress Monitoring'? Because it might just not be handy to have two things.
    - [x] Inheritance is already finished.
        - [x] Do I update that now? Or do I see that as replanning that should be done later? Don't know. It just looks inconsistent this way.
- [x] Done Encircle Language Spec Ideas.
    - [x] The wording is in rougher format, but it is not very long, so should be doable.
    - [x] It may have out-of-scope content.
    - [x] Maybe read over again. Second time around it still seems kind of resolute.