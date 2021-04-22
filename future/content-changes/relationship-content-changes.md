Circular Language Spec Plans
============================

Relationships | Content Changes
-------------------------------

__Contents__

- [Postponed](#postponed)
    - [2020-06-15 Postponed Content Changes for Relationships Chapter](#2020-06-15-postponed-content-changes-for-relationships-chapter)
- [Done](#done)
    - [2020-06-19 Done Deprecating Double Dashed Ring Notation for Relationships](#2020-06-19-done-deprecating-double-dashed-ring-notation-for-relationships)
    - [2020-06-19 Done Brainstorm Bidirectional Relationship Notation](#2020-06-19-done-brainstorm-bidirectional-relationship-notation)
    - [2020-06-15 Done Content Changes for Relationships Chapter](#2020-06-15-done-content-changes-for-relationships-chapter)
    - [2020-06-15 Done Scoping/Changing Relationships Sections](#2020-06-15-done-scopingchanging-relationships-sections)
    - [2020-06-15 Done Content Changes Relationships Chapter](#2020-06-15-done-content-changes-relationships-chapter)
    - [2020-05-25 Done Brainstorm Content Changes for Relationships](#2020-05-25-done-brainstorm-content-changes-for-relationships)
    - [2020-06-14 Done Reformulating Relationships Chapter](#2020-06-14-done-reformulating-relationships-chapter)

### Postponed

- [ ] ~ Relationship Direction
- [ ] ~ Relationships with Pointers

-----

- [ ] ~ Relationships articles might need an update considering that the notation(s) for static might change things.
- [ ] ~ Perhaps merge conceptual explanation and diagram notation.
    - [ ] ~ The split up into a conceptual explanation and then separately an article for the diagram notation, might have been easy for writing the docs, but could be merged into a single article again for readability.
- [ ] ~ Perhaps change the notation for a bidirectional relationship.
- [ ] ~ Do relationships make sense anymore, when related classes are not necessarily fixed by the class?
    - [ ] ~ \> Seems this is just the distinction between relationships between classes and relationships between objects. The two classes might be not related if the relationship is not defined in the class, but you may still relate an object of certain a class to another object.

-----

- [ ] ~ The readability of these articles might be questioned. See 'Redo Easy Themes' in the document Circular Language Spec Strategy.

-----

- [ ] ~ Maybe change the term 'relation' to 'relationship'. That is the term commonly used for it in IT.

#### 2020-06-15 Postponed Content Changes for Relationships Chapter

- [ ] ~ The Relationships chapter is now before the System Objects chapter. I question whether the Relationships chapter might not better go after the System Interface chapter. 
- [ ] ~ The file '2. Relational Structure (Use As Cross Out Later).docx' might be placed in a 'previous versions' folder? I wonder how needed it is for Circular. It might be interesting to keep, not to rip apart as the file name seems to suggest should be done.
- [ ] ~ I also miss, that classes might contain (static) data that looks like object relationships. This means I think, basically that you could see a mix of class and object structure. Perhaps a picture of that may take away some uneasiness and insecurity about applicability of this notation.
- [ ] ~ The idea of multiple types of objects in a single list, might be pushed to the background?
- [ ] ~ Special notations such as 'related to itself', maybe put those a separate part, so the main point may flow better?
- [ ] ~ Is there a more containerish way to express things. For instance the 'Example': could I place documents inside Application with a sort of reference to parent notation?

![](images/2019-08%20Circle%20Language%20Spec%20Revamp%20Notes.013.png)

(minus the wiggly line)

- [ ] ~ Might that work for bidirectional relationships too?

### Done

#### 2020-06-19 Done Deprecating Double Dashed Ring Notation for Relationships

The Basic Diagram Elements chapter may mention the double dashed ring notation. I think I remember it already expressed doubt about it. I may extend Basic Diagram Elements with the proposed relational ring notation, and maybe carefully express preference for it.

Plan:

- [x] Deprecating double dashed ring notation in the Relationships chapter.
- [x] Using (single bordered) relational ring notation in the Relationships chapter.
- [x] Commenting on both notations in the Basic Diagram Elements chapter.
- [x] Not changing the other chapter's content. That might come or should be excusable.
- [x] It may deviate from other tasks (like tone adaptation). I do think it is in line with overall goals. One thing might help the other.

#### 2020-06-19 Done Brainstorm Bidirectional Relationship Notation

I have some difficulty dealing with the following: I do not seem to have much hope anymore for the double-dashed bordered ring notation that might be proposed in the current text. I tend to like the explicit two line notation with a relational ring around it. I now 'fail' to see how that might be more convoluted. The double-bordered ring seems a tiny bit far fetched in its being derived from *automatic containment*, which might not seem to be part of the Circular Language Spec anymore. The derivation might be also difficult to understand without background about this difficult topic of automatic containment, which was (temporarily?) abandoned over its complexity and unresolved issues. (Might be an idea for the future, but not now was the current thought.) I am now failing to see how merging the lines together might create clarity or terseness. It was supposed to be easier on the eyes, less detail, for something that was supposed to be used all over the place. I am not so convinced it might be used all over the place, and not so convinced that the notation proposed is clearer. I like the lines to be a bit purer in what they express, as in, aspect correspondence. I, and maybe others at some point, might be confused that line connections change meaning just like that. I sort of like that you can see that the relationship from an OO point of view looks like two properties closely related. That's quite some talk about why I am not convinced about this notation.

It sort of feels wrong to put effort into texts about a notation I do not seem to like that much anymore.

Possible consequences of changing the notation now:

- Might deviate from reformulation efforts and make that slower or in jeopardy of coming to a halt.
- Might be many places in the docs to change the notation in (disputably).
- May take on more work in a detour task.
- Not currently the focus / main goal.

I however, also feel that a perceived excess in effort going into text that might be deprecated, could be an issue I might not feel entirely ok with.

Maybe a bit of observation over the text, to see where the notation is used. I suspect not in many places. I think many topics might be described independently of the bidirectional relationship notations.

The double dashed ring notation might be used in:

- The Relationships chapter itself.

This brainstorming also costs energy.

I might solve it more easily. In the Relationships chapter I might switch over to the relational ring notation. Then when other chapters might use the double dashed ring notation, the arguments are already given: the Relationships chapter no longer might mention it, the Basic Diagram Elements chapter might express the preference of relational ring notation. Then any piece left that still might use the 'old' notation might be excused. This may be a side-effect of stating things more 'humbly' instead and being more direct where there is doubt.

I used to think expressing doubt or uncertainty might make people dismiss an idea. Now I do not feel like that anymore and might be better off reverting to a way more close to what I was born with. I might want to hold on to that. The language style I try to introduce might not be one that might not come naturally to me. It might be one that clashes with my original language style + other people's demands as I perceived them. So perhaps adopted behavior rather than original behavior might be what makes it difficult to switch language style. To have difficulty finding the balance in. If I can find a point in the past where honesty and humility was my go-to kind of voice...

#### 2020-06-15 Done Content Changes for Relationships Chapter

- [x] The Referrers list might be only part of the system interface.
- [x] Bidirectional Relationships Between Objects:
    - [x] The idea of one reference forward creates one reference back may not be universal. In one implementation it might. But I have made implementations of bidirectional relationship management code, where this might not seem to be the case. I think the notation might be more neutral or keep more options open, to perhaps accommodate a more honest, open and inclusional view on the topic. Perhaps the framework dependence matters. Perhaps an admission of framework dependence is enough. / But I also might like to explore how bidirectional relationships between objects might look in more possible implementation situations.
    - [x] Framework-dependent:
        - [x] For bidirecitonal relationships between objects might be different implementations of synchronized bidirectional relationships, that might invite other notational subtleties. This is just one idea of a way object relations might be subtly different from class relationships. Bidirectional relationships might be managed certain ways by certain software frameworks, and the way things are kept in sync on both ends of the relationship, might inspire slightly different ways to notate it.
    - [x] The framework-dependence seems introduced too early, perhaps. Or too suddenly. The descriptions in this section seem to be about how I planned to implement it. So the notation may be too implementation dependent. / Perhaps introducing several variations of notations may make sense and make things a bit more open.
    - [x] ~~What happened to unidirectional relationships between objects? Those do not seem to be explored. Perhaps there are surprising subtleties in it, that might be explored?~~
- [x] Bidirectional Relationship Synchronization:
    - [x] It seems to be mentioned textually, that relationship synchronization's workings might be displayed as part of the system interface. No image is there (unfortunately)? The system interface at this point in the documentation might not be explained yet, hmm... I also often opt to not refer to other chapters, but I might make an exception here.
- [x] Bidirectional Relationships Between Objects:
    - [x] ~~I do not see class relationships in the picture. I am not sure if that leaves in doubt about the link between class relationships and object relationships. Oh, in "Bidirectional Relationship Synchronization" I seemed to have a similar issue. I also doubt that the image might become clearer with classes in it. The issue in the other section seemed different, because I used class names in the explanations. But maybe I could show images with classes after having shown an image with only objects, to attempt to make clear what the correlation is. > The next section ("Bidirectional Relationship Synchronization") has I think nice pictures showing that correlation. So I think this is fine.~~

#### 2020-06-15 Done Scoping/Changing Relationships Sections

- [x] I feel there might be details of the Relationship chapter that may be postponed to Circular Construct Drafts or Circular Broader View or something.
- [x] I feel that the relationships chapter could introduce the notation, maybe descriptions of the concept, what it is about, what it is for. Maybe how it could be applied. Something about a relationship being bidirectional and the the two ends of the relationship can be kept in sync.
- [x] The sub-topics and what might be done with them:
    - [x] Relationships Between Classes
        - [x] Still might merge conceptual description and diagram demonstration together.
    - [x] Bidirectional Relationships Between Objects
        - [x] May have a valid reason to be there.
        - [x] It seems, that explaining it with pictures with explicit notation may help explain the concept more precisely. And 'might be's may loosen things up a bit.
        - [x] Merged the diagram notation and conceptual descriptions together a bit.
    - [x] Bidirectional Relationship Synchronization
        - [x] To support the notation for a synchronized bidirectional relationship, it might help that the concept of a synchronized bidirectional relationship is described. I may want to define it.
        - [x] But this section might seem to go into implementation details, that you might not need in a description of the notation. Perhaps in a description of a run-time, a framework, but I think a conceptual explanation might be more appropriate.
        - [x] It seems most (difficult?) text is about implementation details that I might opt to move out of this notation description.
        - [x] Conceptual description and diagram notation have become one text with pictures.
        - [x] I might want to change the order so it starts with a simpler picture, where the relationship is indeed synchronized at first and then try and cover what might happen if it was not. > I feel that it reads alright currently and the order change might not be needed. I did remove some redundant sentences for brevity.
- [x] I think I do have a plan.
    - [x] Moving around texts as described above per sub-topic.
    - [x] Kept in the description of class-relational design ideas.
    - [x] Reformulated what remains in more open language.
    - [x] Introduced the notation for relational rings + explicitly showing the two 'counterparts' of the relationship.

#### 2020-06-15 Done Content Changes Relationships Chapter

- [x] The Relationships chapter is larger than the Classes chapter.
- [x] I feel uneasy going through the text marking trigger words in red. It is a lot of text, and it sort of feels like wasted energy sometimes.
- [x] For subjects to postpone I might not value trigger word marking as much as texts I might use at an earlier time.
- [x] I had an uneasy feeling like that when I went through the Classes chapter. Eventually I feel I have boiled the Classes down to something more close to core of the subject and postponed half of the content to Circular Broader View.
- [x] I think I might do something similar with the Relationships chapter.
- [x] I saw implementation details in the text. I saw some concepts, that either might be out of scope or maybe have a place in the System Objects chapter.
- [x] I do not feel that rewording things is wasted energy as a whole.
- [x] But I want to think that if I feel uneasy doing something, there might be a reason why.
- [x] The reason why might be here that the topics I might not really want to cover there.
- [x] Maybe I could just read and go by the topics to evaluate whether I feel they are in scope or whether they might be moved.
- [x] I used to use my intuition like that. I used to trust it. For some reason I seem to have forgotten to trust my intuition.
- [x] (I think I should rename relation to relationships, since it seems a more common thing to call it.)
- [x] Sub-topics and what might be done with them:
    - [x] Referrers
        - [x] Perhaps move to System Objects or otherwise to Circular Construct Drafts or maybe Circular Broader View?
    - [x] Class Referrers
        - [x] Probably the same as above.
    - [x] Relationships between Classes:
        - [x] Not sure what this adds. Seems sort of a bridge towards the 'Relationships between Objects' section.
        - [x] I now moved it close to the top as an extended introductory text, because it might shed light clarifying the main point of relationships.
    - [x] Related Classes
        - [x] Keep it there? Seems a general outline of what unidirectional relationships are, which might be nothing new to introduce in the documentation, but seems an interlude to the other relationship topics.
        - [x] Under "Related Classes\Diagram Notation" I tend to explain details of notational choices, that might not be that relevant to the general point. If explained at all, they might be put elsewhere. Basic diagram elements I what I deemed a place for talking about how relationships between symbols might be implied by various rules.
    - [x] Bidirectional relationships
        - [x] Describes some points of view from a software design perspective I guess.
        - [x] Then goes into that Relationships sort of are bidirectional relationships, which maybe is not a given, so maybe I might not say it that way and may reformulate this.
        - [x] The Diagram Notation part might start to go into that it is not quite solved to apply both *automatic containment* versus *ubiquitous bidirectional relationships* at the same time. Those two concepts may not be part of Circular Language Spec anymore, so that might be moved to Circular Construct Drafts or Circular Broader View. When the postponed concepts are taken out of the text, what might remain of the content? It may make it easier. Notational things might be in there still then.
        - [x] I wonder where my idea went, for a relational ring around the two lines of the two counterparts of a bidirectional relationship. I may just want to introduce it there, even though I was not extending content currently, I am missing this.
        - [x] Besides the things I might like to change, I sort of like the text as I scrolled through it.
        - [x] Section "Counterpart out of Sight"
            - [x] Implicit notations seem to cause jeopardy for ambiguity.
            - [x] In my aim to express multiplicity that is out of sight, combined with my reverting to explicit relationship counterpart notation ("relational ring" notation), the notation looks like what I might have in mind for the notation for 'optional'.
            - [x] I propose to leave this 'problem' unsolved: move the 'Counterpart of of Sight' to Circular Construct Drafts. The argument "something out of sight' is out of sight" seems to make sense enough for this 'problem' not to be considered a problem at all.
            - [x] In another way of viewing it, a proposed notation looks like it 'lies' about the containment structure.
        - [x] Section "No Reuse of Merged Imaginary References"
            - [x] Only seems relevant when automatic containment is relevant and when the sort of deprecated double dashed ring notation might have been relevant. Because those 2 topics might not be considered relevant right now, the topic could move away from Circular Language Spec and into Circular Construct Drafts perhaps. Not even Circular Broader View?
    - [x] Dual and Unary
        - [x] Much of this might be moved or removed, because in essence this might have been covered under the section of Relationships. The issues raised there might be software design issues, perhaps not relevant to the notation. The Relationships section may be renamed to Bidirectional Relationships maybe.
        - [x] I might replace these terms with bidirectional and unidirectional. I think I was searching for shorter clear terms, but I sort of decided to try and use more common IT terminology.
        - [x] I might want to not push the bidirectional relationships too much to the foreground. I may want to make it more neutral on the subject. That should be in line with trying to use more open wording.
        - [x] The Referrers concept seems to be mentioned there again. That might be moved to the System Objects chapter, or to Circular Broader View or Circular Construct Drafts.
    - [x] Referrers Versus Related Objects
        - [x] This might be moved away from Circular Language Spec, since the Referrers topic is too.
    - [x] Relationship to a Pointer
        - [x] According to chapter subdivision ideas I have not, this might be moved to the Pointers chapter.
    - [x] Relationship Direction
        - [x] May tap into a problem that comes with automatic containment, a concept I believe I decided to move away from the Circular Language Spec. So this sub-topic might too.
- [x] Model-based / class-relational design:
    - [x] I am guessing that after the content is changed like that, not that much notation might be introduced, but more an idea of thinking in terms of relationships between classes might be sort of pushed there. That idea might not serve the notation all that much. It may serve an idea I have for aspect oriented programming that might not become part of the Circular Language Spec. I have a question for myself: Might I leave out the topic of relationship-oriented software design, and just strip it to a notation introduction? The alternative seems to be to explain a way you might organize and model code, that to me seems an interesting topic, but might that have much to do with the Circular language notation? I think maybe this is one of those moments where you move a text you like out of the works, to serve the whole and the goal better? Not sure.
    - [x] I think maybe I could get away with apparently squeezing in 'ideals' about software structuring while introducing the relationships notation? Or is that sleezy somehow? I think I might say nothing wrong and the notation is there to support that (common?) software design choice, so why not raise some points about it? They could shed light on why the notation exist in the first place.
- [x] I might already be moving out about half of the (complicated?) text or so. I might consider moving the texts around first, before reformulating in more open wording, just so save some time.
- [x] I think I pushed away the idea of 'what am I doing it all for' and found value in what might become the end result.

#### 2020-05-25 Done Brainstorm Content Changes for Relationships

I question the way the Relationships topic is approached. 

I think it is an interesting idea. But it seems presented in a way that all relationships are supposed to be bidirectional. In one of my prototype apps for a programming environment this idea was sort of centric. But now that the notation seems more important to me, trying to push constructs that might not be that widely applicable, this seems to disturb the story.

It seems to be more about an idea for ubiquitous bidirectional relationships. It seems that Relationships in my view back then was synonymous for bi-directional relationships and my idea was you should make most relationships bi-directional. But the problem with, that I have with that now, is that doing so sort of removes hierarchy: everything seems to land on the same level of the containment structure, if every relationship is mutual. I had some ideas how to then solve that again, with relationship direction. I think I still like that idea. But now I have a construct proposal, that seems to be pushed too hard to the foreground, that seems something you should be able to choose, not something you should be pushed down your throat, excuse the sarcasm. And unless I finish it, it seems to hinder the notation, that I find more important than having all relationships be bi-directional.

Maybe I might demote the Relationships construct to Circular Construct Drafts entirely. Maybe. It seems about what you could do with these unfinished 'Creator' systems I once programmed. But what you could do with Creator had to do with aspects, relationships, libraries of aspects, that tap into a way to describe relationships. Possibly all those concepts might be put aside. Maybe to pick up at one point later, but not so much part of the Circular notation. I do think that in the Circular projects in the past, I had figured out that the Creator concepts are probably integrable with Circular, though the precise notation was not worked out to the last detail. I remember now, that I was quite keen to try and make sure the Circular and Creator ideas were to be combined into one. Later on I think I had it clearer in my head where these two ideas met, and how they could go together.

Maybe describing it more 'openly' might just make it usable as a proposed construct notation. Right now the aim is not so much that everything might work as a run-time or that automatic determination of containment structure is also let go of, which might simplify things. I just might not want to propose that this is a required thing.

I think I remember that some other chapters do tap into it. Maybe it is nicer to just keep it separated into this topic on its own, so not to make other notation explanations dependent on it.

#### 2020-06-14 Done Reformulating Relationships Chapter

- [x] I might go over the loose ideas in the document and cross out or distribute those.
- [x] Going over the document again to reformulate.
- [x] Pictures:
    - [x] Maybe draw new ones in one go, on paper and then scan it.
    - [x] Sometimes borrow (pieces of) other pictures
    - [x] Or simplify pictures by editing them.
    - [x] Maybe write out more what the pictures mean precisely.
    - [x] I think I notice a tendency to sometimes be helped with a step by step explanation/justification for each symbol or line, when it raises questions for me. But I also have another tendency sometimes, to let the images follow and support the conceptual story, rather than adding text to explain the pictures, the pictures might be there to explain the conceptual text. I do not seem to have a rule there.