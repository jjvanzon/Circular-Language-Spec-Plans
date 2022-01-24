﻿Circular Language Spec
======================

Strategy
--------

__Contents__

- [Strategy](#strategy)
    - [Introduction](#introduction)
    - [Goals](#goals)
    - [Earlier Goals](#earlier-goals)
    - [Scope](#scope)
        - [More about Scope](#more-about-scope)
    - [Theme Picking](#theme-picking)
        - [Focusing on Easier Themes](#focusing-on-easier-themes)
        - [Redoing Easier Themes](#redoing-easier-themes)
        - [Rules of Thumb](#rules-of-thumb)
        - [Plan the Specifics](#plan-the-specifics)
        - [Project Order](#project-order)
    - [Productive Writing](#productive-writing)
        - [Creative vs. Productive](#creative-vs-productive)
        - [Tasks](#tasks)
        - [Standard Work in Next Projects](#standard-work-in-next-projects)
        - [Conceptual Explanations vs. Diagram Explanations](#conceptual-explanations-vs-diagram-explanations)

### Introduction

*Circular* aims to become a programming language once.

I spent quite some time in my 20's thinking about this idea of how to visually express the internals of computers and programming languages.

*Circular Language Spec* tries to describe it.

It is an idea for a new computer programming language, mostly about a diagram notation that might show things, that go on inside a computer. It might once become a way to navigate and write code.

### Goals

More personal goals might be:

- Occupying my head
- Working on a project that seems to matter

It was released, but not announced anywhere yet, because of quality issues:

- Organization of content
- Milder tone

Some quality issues might be addressed: moving around texts, changing document formatting, and changed the writing style. 

In the future goals might extend to:

- Language design topics

To get the documents in a state better accessible for others. But for now that might not seem in the cards. Tight time planning does not seem an option either.

### Earlier Goals

A while ago the goal of the project was to describe ideas locked up my head. It was meant to preserve my thoughts about this language. This was done, by attempting to make a specification of the new programming language, adequate as a starting point for turning it into a usable product. Then the idea was that it might be given away, sold, implemented or not worked on for years and then the ideas might not fade away. Theoretically if anyone wanted to, they might be able to continue working on it from that point on. That might create some peace of mind and possibilities for the future. Around __2010__ that goal seemed mostly realized.

Between 2010 and 2012 the goal was __programming__ some of these things, to try and see it in action. It was an experiment. It did not quite get finished.

Between 2012 and 2019 the project went into a __sleep state__. New job. Different goals.

Between 2019 and 2021 the goal was to __open source__ it. It took some time to untangle the project from other docs. Eventually it was published. The goal used to be to patent it, but that is no longer the case. Not sure how to make money off of this, and it seems no use tucked away on a hard drive.

### Scope

Around 2004 the idea may have been to cover *everything*. Now (2021-03) scoping it to large blocks might be considered better:

- [ ] Diagram notation
- [ ] ~ Programming language vs standard libraries
- [ ] ~ Integration with other systems  
        (e.g. using diagrams to express C# code, folder structures, etc.)
- [x] ~~Implementations~~
- [x] ~~Precise rules~~
- [x] ~~Stand-alone Circular programming environment~~
- [x] ~~What apps might be programmed in it?~~
- [x] ~~Could this run as a stand-alone OS?~~
- [x] ~~Aspect Framework / "Creator" projects~~

#### More about Scope

- No programming
- No apps
- Just documentation
- More about existing content, rather than new ideas.
- Only "Language" topics (not "Framework", "Operating System" or "Applications & Media")

### Theme Picking

This section tries to cover strategies for rough planning and *theme picking*. This may mostly apply to *language design* and not so much to *content reorganization*.

#### Focusing on Easier Themes

Less finished-up documentation was moved to the bottom of the documentation. If a topic is more complete and polished, it might be moved back up again.

The idea is to first describe things, that are already clear ideas, first skipping the harder themes, with less of a clear view. There are multiple themes, that can be worked out with more ease than others. That may be quicker and that work might be more 'overdue'.

One reason for this might be, to get more work done quicker. Another reason might be, that the current projects are about making *existing* ideas easier to pick up, instead of *newer* ideas. Another argument can be: documenting harder topics, might create documentation of lesser quality, less accessible. So a good decision seems to be, to do easier topics first.

#### Redoing Easier Themes

Some of the more recently done documentation still seems tough to read.

This might be because when writing the documentation, the idea was still being formed. The documentation may have been written in a way easier to write. Sometimes it was tough enough getting a concept straight on paper. You might not be able to blame anyone or anything for the material first to be written in a way in, which it is easier to *write*. But later, the material and the reading order might be changed, so it might become easier to *read*.

Hazards that might make a reader loose confidence in you:

- Too much
- Too difficult
- Too messy
- Not finished = not worth reading?

But that might be a bit unforgiving.

#### Rules of Thumb

- Perhaps try to focus on themes easier to work out.
- Perhaps give more priority to existing chapters.
- Maybe try to make documenting existing ideas a past stage.
- Documenting existing ideas seems more important.
- Maybe not planning more difficult topics; those might become easier in the future.

#### Plan the Specifics

- Perhaps it is a good idea to define more specifically:
    - Which easier subjects?
    - Which existing topics to simplify?
    - Which tougher subjects?
- Perhaps defining a list of intended future sub-projects.

Maybe plan for easier topics only. The idea is: you might not know how difficult the harder topics might be in the future. They may become easier as time passes by and after the basics might be worked out better.

#### Project Order

This paragraph may be short, but this might be relavant for some focus. As a rule of thumb, this might be the planned order in which to do language design issues:

- __Easier subjects__
- __Simplifying existing subjects__
- __Tougher subjects__
    - (Perhaps by the time you get to them, it might be easier.)

### Productive Writing

In contrast to the previous section, this section is not so much about theme picking, but more about possible strategies for when a theme has been picked and you might want to start working out the content.

This section covers mostly strategies about writing texts.

#### Creative vs. Productive

- Try to form a clear idea in your head.
- You might need to have it clear in your head,  
  before it can be clear on paper.
- Your whole consciousness may need to understand a concept.
- You might not want to see yourself as a production machine.
- You might not be able to make this, if you only focus on producing text and not so much on understanding a concept.
- When you have forgotten the workings of an (important) concept, then maybe the focus may have been too much on producing documentation, rather than forming an idea in your head.

#### Tasks

There might be different kinds of tasks involved when writing these texts. Each could have a different strategy.

- Collecting existing ideas.
- Brainstorming about systematics.
- Writing texts.
- Organizing & reformulating brainstorm texts.
- Determining document / section subdivision
- Converting brainstorm texts to eventual text.
- Starting over.
- Using old content as a sort of *cross out* list.
- Brainstorming about different approach.
- Adapting texts to different approach.
- Processing details.
- Reading over.
- Folder organization.
- Scattering texts from old documents across a new form of documentation subdivision.

Below, some of these task are commented on. The focus may lie on *content*.

- #### Collecting Existing Ideas

    - You might give some importance to collecting existing ideas first (notes, 'idea boxes'). It might be quiet some work. The collection of those ideas may be a good starting point, for the eventual content. You might miss out on something good, when you skip it.

- ##### Organizing & Reformulating Brainstorm Texts

    - The method employed for organizing and reformulating brainstorm texts seems ok, but sometimes it might be better to just derive a topic list from the idea texts and start over with the texts.

- ##### Creative Thinking

    - Brainstorming about systematics might not be easy. You might not want to see this as production work. You may want to do creative thinking and take some time for it to become clear.
    
    - It may be a good idea, to not just stick to the frame of the project. It should be *one* programming language. You may want to keep the bigger picture in mind, even when a project is working a specific subject (for instance: Interfaces). It should be a good idea to look at a broader perspective too.

- ##### Determining Document / Section Subdivision

    - Sometimes there seemed too much focus on explaining each concept in its own separate article.
    - That may be too *form*-oriented.
    - It may have happened in an effort, to turn the work into countable reliable items.
    - It may not have been realized, that it might be better to put the focus on *creative* thinking.
    - Perhaps work was considered production work at times, or looking for the easiest way to get a set of articles done.
    - It might be better to focus more on *creative* thinking, instead of *productive* thinking.
    - Maybe split up the material into less articles, if that makes it easier to finish a project.
    - Making it a single document, if you must.
    - Sometimes, when things are too complicated, you might ‘artificially’ split up the story into separate articles. This can be done, to get a clearer view on things, not so much because it reads better.
    - Sometimes effort went into making the article list a set of concrete tangible concepts, which might not always be required. Sometimes when there were rules, that applied to multiple concepts, the rules were repeated in multiple articles. It should be ok to isolate a rule into a separate place and to not repeat it.

- ##### Converting Brainstorms to the Eventual Text

    - You might want to be more satisfied with having a set of stories, the way they were in the brainstorm texts. You might not want to give the articles an entirely different subdivision, than brainstorm texts had.

- ##### Document Content

    - __defend__:
        - Maybe try not to *defend* the system too much.
    - __compare__:
        - You might not want to *compare* the system too much to other systems.
    - __how & why__:
        - Maybe try to avoid talking about too many because’s and *how* and *why*.
    - __blunt__:
        - Maybe tend to be more *blunt* about how things work. Perhaps not blunt, 'unfriendly', but more like: "This means *this*, and that means *that*."
    - __knowledge of the reader__:
        - Perhaps try not to worry too much about the *level or knowledge of the reader*.
        - The material might not be read by everybody. It can be professional jargon.
        - It might not explain the workings of the CPU, the working of other languages, etcetera.
        - But if, when writing, confusion is experienced about something, adding something about it to the writing might serve yourself and perhaps others too.
        - *General* notational rules might not be covered in *specific* diagram articles. Maybe it might be useful for clarity's sake. But those notational rules could be covered separately. Rules also do not necessarily need to be referred to each other everywhere.
    - __exceptional cases__:
        - Maybe try not to worry much about *exceptional cases*.
    - __implications__:
        - Maybe try not to worry about considering the *implications* of things.
    - __uses__:
        - Perhaps try to avoid explaining all the different uses of the language. It might be hard to cover them all, since it could be considered a general purpose programming language. Basic building blocks might be provided. It might not be necessary to try and give all the examples of what to do with it.
    - __keeping it general__
        - You might for instance choose to only cover a *general view* on a topic instead of working out the exact details of a concept. 
    - __delete__:
        - Perhaps try not to be afraid to permanently delete texts, that fall under any of the above categories.

    -----

    - Maybe try not to worry about the details. They might resolve naturally later, perhaps when programming an application for it. A side-effect of covering much detail, might be imposing rules, that you might later break. Or that effort goes into coming up with rules, that are hard to uphold. Rule-richness may get rules stuck on each other.

    - The list above may work well as a set of guidelines for a sort of 'prototyping' part of a project, as opposed to a 'finishing touches' part of a project.
     
    - Perhaps it is wise to not cover details, because that also might make things easier for the reader.

- ##### Starting Over

    - Sometimes when you have a rather large collection of ideas and brainstorms, it may work better, to just extract a topic list out of it and start over.

- ##### Cross Out

    - Later you might use older material as a cross-out list, to delete older things already covered by a newer story and perhaps delete things that have become less interesting and extract stuff that might still be interesting.

- ##### Adapting Text to Different Approach

    - Adapting text to a different approach may take a while.
    - But sometimes putting more effort into this might be ok.
    - You may be tempted to see this as production work, but you might not want to see it that way.
    - Maybe try not to focus on *getting it over with*.
    - Maybe try to explain the new *concept* well and getting the details right in your head.
    - Sometimes facts seem left in, that just might not be right, just to get it over with.
    - Otherwise it may leave the story in a state of lesser quality than you want.

- ##### Document Form

    - Adding references to other articles might not be a goal. It seems high maintenance.
    - Perhaps let go of some worry, whether everything referred to, had already been explained or not.
    - 'Perfect' form may not be a requirement for the articles.

- ##### Processing Details

    - At the end of the project there might be a list of details left. You first might want to consider, not to adapt the texts to those details at all.

- ##### Reading Over

    - The efficiency aspect is loosened up for now. So perhaps read over as much as you like.

- ##### Folder Organization

    - Simplification in folder organization usually seems a good plan.

The story above, might actually also try to break things up into logical units too much. That might be too form-oriented. Sometimes the rules seem to contradict. Perhaps just use them as guidelines.

#### Standard Work in Next Projects

In each next project you pick, consider processing the idea box / loose ideas you might have, even if it seems time-costly. Reformulation of loose ideas, might actually result in a readable, structured article covering the topic. That might be one of the strategies, that could lead to good text.

A project in which you update documentation, might be trailed by an update to the redirection pages, that tell something about that documentation.

#### Conceptual Explanations vs. Diagram Explanations

Conceptual explanation and the demonstration of the diagram notation were separated in the past. This was done, because sometimes conceptually explaining something went without problems, and the problem may only have been, how to express it in a diagram. In that case it might be easier to first draw out a conceptual point of view, and next that might make it easier to work out a diagram notation. The conceptual point of view then might not change, but an (imperfect) diagram notation may be changed later, when your vision on it becomes clearer. Also: sometimes when you work out the conceptual explanation first, it becomes easier to figure out a proper diagram notation. However, you might later want to merge conceptual explanation with diagram notation explanation in certain cases, because this might be easier on the reader, to have a conceptual explanation decorated with pictures.