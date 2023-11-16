Circular Language Spec Plans
============================

Objects | Content Changes | 2020-06
-----------------------------------

__Contents__

- [Objects | Content Changes | 2020-06](#objects--content-changes--2020-06)
    - [Postponed](#postponed)
        - [2022-01-30 Postponed Content Changes for Objects Chapter](#2022-01-30-postponed-content-changes-for-objects-chapter)
        - [2020-06-11 Postponed Content Changes for Attributes Article](#2020-06-11-postponed-content-changes-for-attributes-article)
    - [Done](#done)
        - [2022-01-30 Done Content Changes for Objects Article](#2022-01-30-done-content-changes-for-objects-article)
        - [2020-06-07 Done](#2020-06-07-done)
        - [2020-06-07 Done Content Changes for Objects Article](#2020-06-07-done-content-changes-for-objects-article)

### Postponed

#### 2022-01-30 Postponed Content Changes for Objects Chapter

- [ ] Object pointing to itself may be another edge case worth mentioning.

#### 2020-06-11 Postponed Content Changes for Attributes Article

- [ ] ~ Attributes might get the 'cookie' notation.
- [ ] ~ Attributes section: Could each sub-section be expressed in a picture in a way?

### Done

#### 2022-01-30 Done Content Changes for Objects Article

- [x] Introducing a 'reference to parent' notation in the Objects article.
- [x] Stereotyping text fragments and see if things may change?
- [x] Moving terminology expositions to construct drafts?
- [x] Adding a picture with a list that is named?
- [x] Object Reference: bit repetitive: saying same thing in multiple slightly different ways.
- [x] Reading over, reformulating.

#### 2020-06-07 Done 

- [x] Maybe only merge conceptual explanation with diagram notation explanation.
- [x] The split up into a conceptual explanation and then separately an article for the diagram notation, might have been easy for writing the docs, but could be merged into a single article again for readability.

#### 2020-06-07 Done Content Changes for Objects Article

- [x] Maybe attributes can be introduced as perhaps not really a specific part of the Circular language. It is more of a concept with an explanation of how it might fit into the Circular programming language.
- [x] 'Target Objects' kind of puts aside a different interpretation of object references, where all symbols are references, even 'final target' symbols.
- [x] Attributes section:
    - [x] Enumeration of Attributes:    It has a text that might apply in an application where you might query for reflective data, perhaps for aspect oriented purposes? The issue might be a bit out of place there. Maybe elsewhere? In System Objects? Or otherwise in Circular Construct Drafts somewhere?
- [x] I might move Target Objects to Pointers now. I am pretty sure I want to give it a separate place and might not want to reformulate parts of it now?
    - [x] > Yes, I think I might do that.
- [x] 'Related Objects': The picture has the labels A and B, which do not seem to serve a function at that particular spot.
- [x] Related Objects section:
    - [x] The term sub-object seems to change meaning from time to time.
    - [x] At one point it means not the external references. At another it includes the external references. It might be more about the notation, rather than the terminology. I think I might tend to make terminology leading. I seems to explain synonyms of things in separate headings. I have doubs about the usefulness of that. Maybe thinking more of the concepts rather than the terms, might clean up the text? My goal is not to tech terminology or something, or make one up and then teach that. My goal might be to convey an idea. The term 'sub-objects' might not be a term often heard in IT. I think I just use it, because it makes the explanations work better. Maybe, since it might not seem a well adopted, perhaps therefor not well defined, term in IT, I might mention it briefly for the flow of the story, then maybe adopt common IT terminology or at least something I seem to assign a clear, non-ambiguous definition. It might be a subtle effect in the text, this ambiguity around the term 'sub-object', but it might clean things up if I do something with it. But how? 
    - [x] Maybe by using sub-object only for non-object-references, then letting go of the term. 
    - [x] The term 'object' may simply be used in a certain set of occurrences of 'sub-object' within the Objects article.
    - [x] I think the argument 'use common IT terms' that I formulated in the project outline might apply here and prevent possible confusion.
    - [x] Child object and sub-object might be synonyms. Child object also might be an object reference.
    - [x] Object references are a bit ambiguous here. The notation suggests an external link. But other interpretations of pointer suggest otherwise (denoted in the Pointers article).
    - [x] Maybe it should not be much of a problem to call it sub-objects some times. It might be a problem in the Relationship Objects section specifically, when you try to assign a (too?) specific meaning to it.
    - [x] Might the section 'Related Objects' serve a purpose at all? Maybe you can drop the term 'related object' arbitrarily and it might not necessarily might be defined, because it already makes sense on its own? The Related Objects section suggests something new and distinct is introduced, but it is really just the introduction of a term, and the sum-up of what has been previously said. Maybe this confusing effect can be thought of as rudimentary from when the documentation was more 'definition based', like a big glossary. That each term 'had to' have its own article. That might not be how I want to end up describing things.
    - [x] I do like the picture. Maybe I can just drop that picture under object reference, if it seems to clarify things. Maybe I could just suggest the synonym there too, but briefly.
    - [x] I question whether to show the picture at all and whether to define the term related objects at all.