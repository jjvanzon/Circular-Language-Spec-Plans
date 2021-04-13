Encircle Language Spec Plans
============================

Parameters | Content Changes
----------------------------

__Contents__

- [Postponed](#postponed)
  - [2019 Postponed](#2019-postponed)
  - [2020-05-20 Postponed Content Changes for Parameters](#2020-05-20-postponed-content-changes-for-parameters)
  - [2020-06-11 Postponed Content Changes for Parameters / Command and Classes Loosely Coupled](#2020-06-11-postponed-content-changes-for-parameters--command-and-classes-loosely-coupled)

### Postponed

#### 2019 Postponed

- [ ] ~ Maybe only merge conceptual explanation with diagram notation explanation.
- [ ] ~ The split up into a conceptual explanation and then separately an article for the diagram notation, might have been easy for writing the docs, but could be merged into a single article again for readability.

#### 2020-05-20 Postponed Content Changes for Parameters

- [ ] ~ Maybe make the idea of ubiquitous bidirectional relationships between commands and objects less centric. Or perhaps at least diverge into other approaches, so attempting to make room for expressing what goes on in other languages, rather than replacing the construct by another take on it.
- [ ] ~ I think maybe that bidirectionality is not of much use in this Encircle Language Spec. It seems better off being placed in Encircle Construct Drafts, because it just might not resonate much with other languages, programming seems to be able to live without it, and it seems alienating and full of implications, that seems to make concepts fall apart that did not seem to need to be ripped apart in the first place. I might be too harsh about it here. It is an interesting idea, I think, but it just complicates the idea of the diagram notation, which seems centric, not drastically changing how constructs work.
- [ ] ~ The Imported Parameter Concepts could be tidied up. The ideas from the original Symbol Language.doc might be processed: discarded or embedded into the main text. Merging the texts of the conceptual explanation and diagram notation might make things more overviewable and shorter / less text.
- [ ] ~ The approach of in/out/thru may be a more appropriate description.
- [ ] ~ Thru parameters had a particular implicit notation introduced in "Symbol Language (2004)": an object line that goes in both directions. Perhaps one implicit notation too many. But perhaps it can be introduced as an alternative.
- [ ] It seems the parameter connections might be implicit assignments (perhaps readable in "Symbol Language (2004)". It might only be implied in "Commands" > "Creation Behavior of Commands" in the Spec currently (2021-03-03). Perhaps it might deserve to be mentioned this possible implicit behavior of the lines (that cross command boundaries?). It might not be like that in all cases (clauses?). Introducting the concept lightly surrounded with maybe's may help.
- [ ] ~ This Argument: Making a mention of this.

#### 2020-06-11 Postponed Content Changes for Parameters / Command and Classes Loosely Coupled

- [ ] ~ (Moved to Encircle Broader View\Classes)
- [ ] ~ What might be mentioned if the text might be built up from the ground up? I think I might just talk about the static concept, because that seems to me the number 1 candidate for what classes might have a lot to do with and might possibly determine the dashed notation and what makes room for the distinction between classes and prototypes and might give a clearer definition of what classes and static structure might be conceptually and have that reflected in the diagrams more directly. I might move the more creative concepts away from the Encircle Language Spec.
- [ ] ~ I have questions about the dashed line usage of lines of the smaller squares:  
![](images/2019-08%20Circle%20Language%20Spec%20Revamp%20Notes.016.png)  
I do not understand why the class might point out the external command definition with a dashed line, while the objects point out the external command definition with a solid line. I think I might have followed a style choice more than an exact depiction of things? Might both lines express something that kind of works, leaving the options open for a stylistics choice to have class structure be more with dashed lines and object structure be more with solid lines? I suspect that I might leave this doubt open.
I am a bit amused by my own typical behavior, because half an hour later, I see that the explanation was already in the text.
I do feel it might be quite something to burden the reader with. I am hoping for a more clear meaning for dashed shapes in the future.

- [ ] ~ Another point of doubt might be:  
  ![](images/2019-08%20Circle%20Language%20Spec%20Revamp%20Notes.017.png)  
  Why is the line on the right no extended to the circle, so class structure and object structure look more alike except for the dashed and solid lines?

- [ ] ~ This "Command and Classes Loosely Coupled" idea (exchangeability between class-commands and command-parameters) might be moved to construct drafts. An approach with centric concepts of "Value In", "Value Out", "Object In", "Object Out" might be more practical. There might be (draft) content on that for instance in the "Symbol Language (2004)" document and perhaps elsewhere too. The idea of "Command and Classes Loosely Coupled" might have unnecessarily complicated things.