Encircle Language Spec Plans
============================

Scoping | 2019-08 | Notes
-------------------------

### TODO

#### 2020-06 ~ Scoping

- [ ] Is it a *notation* or is it a *run-time*?
    - [ ] (Texts might insist that Encircle is a run-time, while the notation might be the main point of things.)

#### 2021-03-30 TODO Scoping Encircle-Language-Spec-Plans

- [ ] Encircle-Language-Spec-Plans repository
    - [ ] 'Out-of-scope' things might need distinction between "Broader View", "Construct Drafts" and not to be part of the Encircle-Language-Spec-Plans at all.

### Done

#### 2020-12-05 Done Scope (for Git Migration)

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

#### 2019-08-05 Done Brainstorm Scope

- [x] Encircle Broader View: Maybe the design of the programming language should lose some ambition and express that only as dreams.
- [x] I notice I talk a lot about implementation rather than notation. For instance: Does a dashed circle mean it is used as a class, enforced to be a class, static inside its container, how does it work in the system interfaces? What if it is just the notation that is the main idea, what if the implementation isn't. That might even make system interfaces' precise definition not important or maybe just subjected to diagrams drawn out to represent things from another language, like C#. C# getters and setters might be in a system interface notation. But setting an object reference's interface dynamically in runtime... may be too much of an implementation detail. I think it is a language definition / runtime implementation separation. In think the engineers at Microsoft might be right about developing language spec / runtime / framework / compiler quasi-independently. Maybe I can be inspired by that and make my language definition a little simpler. I am subjected to the pitfall of wanting to cover every little minor edge-case, of which I have a fear that it may make the whole system fall to pieces. I already warned myself about that in the Encircle Language Spec Strategy document. But now I think other people might actually read this, I start to think: maybe limit the scope. Somehow define the diagram notation and what it represents and not want to work out how things would work in a runtime. Runtime would be a system where the diagrams and actually the data that internally describes the diagram, to be loaded and run as computer programs. I think I wanted to check the usability of the notation by shining light on any little aspect of it, I could find. But I think some details are not that important. Maybe those are to be demoted to possible implementation details, to keep the main part of the story clean. I am OK with apologizing in the documentation, that this might not be usable or something. The description in the Strategy document is pretty much spot on, I think.
- [x] Encircle Construct Drafts: I get the problem that next to introducing new notation, I also wanted to introduce new concepts. A new conceptual take on things. I think it all became a little much.

#### 2020-05-14 Done Scoping | Split Up Encircle Docs

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

#### 2020-03-07 Do Not Do: Brainstorm Circle 3 Programming Planning Docs

(Circle 3 projects are software development projects, unlike Encircle Docs projects, which are language design projects.)

It appears around 2010 I started off with programming Circle 3 with the intention of a more rigorous planning methodology and higher quality technical documentation. Around the same time I switched employers. The new employer did not value my doing planning or documentation, just coding. In projects at home it seems I adopted that way of working. So planning docs and tech docs were no concern anymore. I focused on coding. I think I also stopped keeping an hour sheet at home. That felt was freeing. It felt too much like work logging the hours I spent at hobby projects. But the real motivation for the shift in way of working, seems to be that I cannot have 2 methodologies at the same time: one at home and another one at the office. That seems intrinsic to how my mind handles things.

So I have these near-perfect planning docs for Circle 3, while the execution of the projects was almost only coding, no planning, no documentation.

I don't think I want to reformulate the goals of Circle 3 programming projects, to exclude software design. It is not about making those planning docs good.

#### 2020-03-22 Do Not Do: Circle 3 Programming Planning Docs

- [x] I could change titles of projects inside the doc content too.
    - [x] Also for Circle 3 Programming, though less importantly.
- [x] Could I just go with it, call it 'Circle 3 Programming'? And if I want to mention in the planning docs that to documentation was of little concern, just do it with a more open formulation, like 'documentation was of little concern' or 'very little documentation turned out to be written in these projects. The focus turned out to be on programming the code.'?
- [x] I could put a remark or something in the Circle 3 Programming docs that I did not do any documentation, even though it was the initial plan to do that.
- [x] I was going over some sub-project docs to check if any documentation was written during those projects.
- [x] Other sub-projects I scanned were not clearly any doc issues in them. 

#### 2020-04-13 Done Brainstorm Scope

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

#### 2020-05-10 Done Scoping: Symbol Language and Software System Planning Docs

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

#### 2020-04-01 Done Scoping Encircle Language Spec Planning Docs

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

#### 2020-04-01 Done Scoping Encircle Language Spec Planning Docs

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

#### 2020-03-22 Done Scoping, Project Names

- [x] Inspecting the sub-projects just to find whether documentation was of any concern in those projects, might be too intense for me right now.
- [x] The question I was trying to answer with that was: Is it accurate to call the super-project 'Circle 3 Programming'?
- [x] The reason for calling it that, is to make it clearer what the project entails, separating it better from the super-project with the name 'Encircle Docs', so that there is a clear distinction that one is about programming and the other is about documentation.
- [x] But from the top of my head I kind of already know that the focus of those Circle 3 projects was programming, not documentation.
- [x] I just want clarity on the distinction between projects Encircle Docs and Circle 3 Programming, but giving it a clearly distinctive name.

#### 2020-03-16 Done Scoping Circle 3 Requirements Docs

- [x] I moved content from Circle 3 Requirements to New Computer Language Products doc.
- [x] I could rename it to Circle 3 programming, rather than Circle 3 software development, because programming was all I did, not full blown software development cycles. Right? ('Programming' is a bit ambiguous too. It could mean program the dev environment or program using the new language. But I am OK with it.)
- [x] Maybe check sub-project docs later to verify that I didn't do any documentation.

This is spreading my attention over too many different things. Is there a more practical approach?

This is too intense. I have to stop again.

#### 2020-03-08 Done Reading Circle 3 Requirements Docs

The requirement group 'Priority C: Classes' has 1 language design feature: < Diagram Notation Design > Static. So that is to be moved to the language design planning docs.

'Priority E: Integration' contains brainstorming instead of a list of items.

> (I notice I get inspired to like implementation projects for Circle 3. I feel the enthusiasm in it. I somehow stopped working on it, though. Also it is not my goal right now. The goal is publish Encircle language design eventually.)

Some of the content in 'Priority E: Integration' could be part of language design, at least diagram metrics design and automatic containment. 

'Priority F: Large Amounts of Items': Spiraling could be part of diagram metrics documentation. And object order.

'Round-Up': Most are documentation issues, which in theory could be moved to the language design project instead. Except, they are 'technical design' documentation issues, which do not have a place in either the language design project or the circle 3 programming project, because 'technical design' I did not consider language design, because I would have called language design 'functional design'. 'Technical design' according to my views back then, would have be document how I implemented things in the programming of Circle 3, not how the language functionally works, but how Circle 3's .NET code works internally. However, I could see the topics up for 'technical design' as topic that also could use an update to the functional design. So I could consider those topics for extending the Encircle language spec project's requirements. Then I could consider removing documentation issues from the Circle 3 programming planning docs, because I wasn't going to do them anyway.

I ran over all the content of Circle 3 Requirements and above are the conclusions of what to possibly do.

#### 2020-03-07 Done No Planning or Docs Back Then

Circle 3 Strategy is pretty much done.
Circle 3 Requirements: change coloring and formatting.

That does not take away I want to split topics in these planning docs between language design one one end and programming at the other.

#### 2020-02-23 Done Reading Circle 3 Strategy

An idea for today would be to read "Circle 3 Strategy". That document is supposed to be about software development, not language design. At least, that is the new goal I have with that document. Some things in it are relevant for the Encircle Docs.  
"Goal of the Language" is where it is part about the language design, not so much the software development. I might use/move this text to the Encircle Planning Docs.  
Was at "More Tips" processing things.

At what point am I going to be more rigorous in splitting off the Encircle Planning Docs from the rest? Not yet, I think. It's still a mash up of both in the planning docs I am reading now.

#### 2020-02-20 Done Scoping

Today finished splitting time planning and projects step into in-scope and out-of-scope documents.

#### 2020-02-16 Done Notes

Working on splitting time planning and projects step into in-scope and out-of-scope documents. (worked on it for 45 minutes this day.

#### 2020-02-13 Done Scoping

Working on New Computer Language, Products.docx:

I do not want to necessarily want to shorten the list of products any further. Even the list of Done work. Because some parts are part done and it would be easier for me, would I work on it, to have the same subdivision of the pieces TODO as the pieces that are done.

What I do might want to change is the rough order in phases of the stuff TODO.  
I might just go over it a few times, reformulating.

I am splitting off parts of New Computer Language, Products.docx into a separate document with the out-of-scope things.  
I want to go over the Postponed topics, to see what content can be moved to the 'out-of-scope' document.

Now I still want to weed out the 'Topics Roughly' moving things to the 'out-of-scope' document with the products.

Also the Strategy can be stripped of things 'out-of-scope'.

#### 2020-01-13 Done Scoping

I read and reformulated some texts from "New Computer Language, Strategy.doc". 2 hours or so. I am now too tired.  
That document does not cover many things out of scope of language specification. It just briefly talks about programming experimental versions and licensing it and stuff, but little enough to keep it in there, were I to isolate this into a pure language specification writing project, which I intend it to.

#### 2020-01-04 Done Rough Plan

Rough plan:

- [x] Remove detail from products doc.
- [x] Split main planning docs into 2: content about the diagrammatic programming language and content outside of that subject area.
- [x] Or read some sub projects docs.

I had those plans with it, but did nothing about them this day.

#### 2019-12-29 Done Brainstorm Scope: Diagrams / Constructs / Gap Lifting

- [x] The application of them are different (of *diagrams, conceptual constructs* and *boundaries lifting*).
- [x] Proposed constructs: 
    - [x] Another example is the automatic diagram organization topics. The diagram notation idea can live without some of the wild ideas in that. For instance, interchangeability between containment and referential structure or inversibility of containment in case of bidirectional relationships. Also the striving to want almost all relationships between objects to be bidirectional, does not apply if you want to use the diagrams to express systems in which you have a choice if relationships are bidirectional or unidirectional. Also giving things a different name (aspects are all of a sudden called concepts) is not a priority, and perhaps even alienating. Those are just some ideas I have about how to pull things apart. 
- [x] I think maybe those differences in application call for a rigorous split up: *diagram notation / constructs drafts / gap lifting*. Diagram notation is a bit of a grey area, because it wants to use constructs. Some of the notation capabilities imply different variations of otherwise fixed constructs. I think a separation of some main groups of concepts is appropriate here, so the ideas are better transferable and perhaps better usable and applicable. It might make the general idea about the diagram notation more pure and also more freely usable, not in a fixed way. An argument that falls away when you open sourcing and not patenting or something, is that things do not need to have a closed, unambiguous definition. Things can be just part usable, using and replacing rules as one wishes. You can say at some point the diagram notation surpassed the original goal on two ends. I had somewhat of an explosion of ideas then surrounding this notation. Boundaries between ideas were not well defined. That's a (good?/bad?) quality of my way of thinking, I guess. But I tend to want to focus things, by splitting things apart in the main blocks, so it that it might become more practical (for others or myself).
- [x] "Encircle Language Spec" / "Encircle Language Broader View" / "Encircle Language JJ's Construct Proposals"
- [x] I don't like the last name. It seems long.
- [x] Proposals seems more community-based, not single authorish.
- [x] Language Spec vs Broader View:
    - [x] The idea that the diagram expression should be canonical and unambiguously express anything from any computer language, might not be a rule I want to uphold in the Encircle Language Spec docs. For instance if C# has certain rules for scoping of implied accessibility rules of members, you might not want to express that in a diagram. It sort of would make no sense if the diagrams are applied like a helper tool in Visual Studio to visualize certain aspects of C# code, to have symbols that disambiguate something, that is not ambiguous according to C#. The concept of canonicalizing things, may have a better place in Encircle Language Broader View docs, I mean to isolate from the Encircle Language Spec. A reason for unambiguous expression may only become clear, if you look at those ideas about possible broader applications of this notation: specifically where in a diagram you just switch from one source language to the next, by navigating the symbols. (E.g.: Now the diagram expresses something with C# as the source, navigate onward and you may see some diagram expressing something that came from JavaScript... the rules change, maybe the diagram expression should be unambiguous.) I think it is good and keeps it simpler and ideas less stuck on each other, to speak in options for diagram expression. There is a general theme in the expression. It is not all wishy washy, but there is wiggle room for how to use it. I just want to share the idea, not impose how it should be used.

#### 2019-12-29 Done Scope: Diagram Topics

Eventually, you might split the now in-scope topics apart in pieces that are in-scope and others that are out-of-scope. Some ideas just aren't the original ones, not a hot idea, and not prone to be adopted. For instance: The spaces in identifiers, text code ideas... I might have done good by keeping conceptual thoughts apart from diagram thoughts. I tend to want to merge those two aspects for the benefit of the reader. But I also tend to want a diagram notation that can be applied to other programming languages as a source for the diagrams. In that case, not all wild conceptual ideas are relevant. I did have thoughts: how would I implement this if I did it from the ground up, how would I implement that if I did it from the ground up, like interfaces, inheritance, ref-ness etc.

#### 2019-12-29 Done Brainstorm Scope (Useful)

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

#### 2019-12-29 Done Brainstorm Scope

- [x] What do I do with things, that are out-of-scope? Do I just bluntly remove them from the documentation, or do I go through the trouble of parking the texts elsewhere?
- [x] Would I rename 'Computer Language' to something else, admitting it is a programming language, and only expressing the hope that it would become a language to a user to, where constructs are simpler. Do I simply admit that these were my ambitions with the project, and if people claim arrogance, then let them?
- [x] I am hoping at some point, the planning docs get smaller... because these documents are huge and intimidating.
- [x] Maybe I should just make 2 project folders eventually in the Planning Docs repository: one for the new computer language and one for the rest, that are much like eachother, but one stripped down to computer language functional design topics, and the other in which to dump the rest: anything deemed out-of-scope of the entire new computer language topic. Those are different than topics out-of-scope because postponed, but still much to do with the new computer language. Maybe at first, even 'worse', I make 2 documents in each folder: One with topics that belong to the new computer language, and another document much like it, in which the rest is put, that I would want to leave out of it.
- [x] I think a new concept to me, introduced in this new project is that: I do not need to do everything. Like this from "New Computer Language, Products.doc: "You have to be able to introduce new basic data structures and give them the nonagon symbol, and have different kinds of possible indexers, etcetera." I don't have to. I could do without. Ideas might be viable and interesting without all details being covered, without all proofs being given. I wanted to work out *everything* at some point. I also was a afraid, that if I didn't, people would not believe in the idea. Maybe I got over-ambitious, because I saw so much potential. I think I was able to work out a lot, but then I would get distracted by another project and then it turned out, I never got back to it. Scoping is a trick for that, when managing projects. Setting the boundaries and limitations of what the project would cover. I never wanted to do that back then. I wanted a framework in which everything would fit and then choose seemingly randomly what I would cover next. In one way I like the freedom of that. But on the other hand, it becomes a never ending story. I sometimes had the ambition of actually making *all* of it. I might have been able to create a playground in which I can go wild, but someone else would never want to cover all of that. Someone else would never take over your programming life, just a scoped programming project and then maybe. So I want to scope it. And lose the 'programming it out' part. And loose 'it is also a framework and an OS and any commonly used application'. It is actually quite hard for me to let go of that idea. I liked my playground back then. I wanted proof, that this could be used to realize software quicker, so one man can do what would have taken an army of programmers to do before. But I don't have that ambition anymore. Right now I just want to publically give away the programming language idea. I think I notice a lot of insecurities about people thinking it is a good idea or not. Maybe because I was trying to sell the idea, rather than just give it away? I get that I wanted a framework into which all of my ideas fit. I like some of the modularization of the concepts. But I do want to just cut away a few things. I think I am still trying to sell an idea, but then in a different way. I do not have the intention to sell it for cash, but I do want to not make it too ambitious, cover too much, so large in scope, that no one would pick it up anymore. 
- [x] The time planning document ("New Computer Language, Project Steps & Time Planning.doc") looks far more overviewable and less intimidating. It all seems so manageable there.
- [x] The document with the list of products ("New Computer Language, Products.doc") is overwhelming, because each article written is mentioned separately and that means almost each paragraph of produced writing is mentioned separately. If I would just mention the basic outlines, this might be better. Earlier, back then, it may have helped me see what I did and see how much I wanted to do. But with the goal I have now, I think it loses its purpose, and simplicity of the planning docs is more important than rigorous tooling for detailed planning of my own work.

#### 2019-12-15 Done Scoping

- [x] I read over the document "New Computer Language, Strategy.doc" in full and did some reformulations, also removing my never realized studying goals.

#### 2019-08-05 Done Brainstorm Restructuring Docs

The Encircle Planning Docs took a turn at some point in time. At one point it was mostly about documentation, then it became about both documentation and programming. But the planning docs folders do not seem to be fully updated to that change. Maybe I can do that in the context of *this* project. First some more reorientation.

'Program Software System' now looks 'outdated', compared to the programming work described in 'Document Software System'.  
I might actually move many of those topics from 'Future\Interesting Now' to 'Postponed'.  
I also would want to put a cut into all the planning docs and all the circle docs: this is the language and this is the rest.  
So it gets isolated. In the past I wanted to put everything I did (and will ever do) with software development at home in a single system so general that I called it 'Software System'. Many docs are general and describe both that language + OS-like topics and applications. I might want to cut that in two: language and the rest. I might like to open source the language at one point and just leave the rest out of it.

I think I interwove these things maybe a little too much. I just liked to subdivide things into a single system of subdivision into which everything fitted. Also, the interweaving may have been stimulated by my wanting to combine this 'Creator' project with the 'Encircle' language project. The 'Creator' project was about model-driven development, aspects and framework more than being a real computer language. I wanted to combine the two things into a single system, so that may have lead me to try and put everything into a single system. Now, I think I know that Encircle is the computer language and you could program model-driven aspect oriented software with it, if it can provide the aspect construct. Really, I think it helps to not try and solve all problems at once. 
