Circular Language Spec Plans
============================

Parameters | Content Changes | 2021-05
--------------------------------------

__Contents__

- [Parameters | Content Changes | 2021-05](#parameters--content-changes--2021-05)
  - [Postponed](#postponed)
    - [2020-07-24 Postponed Parameters Content Changes](#2020-07-24-postponed-parameters-content-changes)
    - [2021-03 ~ Parameters Content Changes](#2021-03--parameters-content-changes)
    - [2019 Postponed Merging Conceptual Descriptions with Diagram Demonstrations](#2019-postponed-merging-conceptual-descriptions-with-diagram-demonstrations)
    - [2020-05-20 Postponed Content Changes for Parameters](#2020-05-20-postponed-content-changes-for-parameters)
    - [2020-06-11 Postponed Content Changes for Parameters / Command and Classes Loosely Coupled](#2020-06-11-postponed-content-changes-for-parameters--command-and-classes-loosely-coupled)
  - [2021-05-03 Brainstorm Parameter Passing Reorganization](#2021-05-03-brainstorm-parameter-passing-reorganization)

### Postponed

#### 2020-07-24 Postponed Parameters Content Changes

- [ ] ~ Terms "In" and "Out" might be avoided.
    - [ ] ~ I seemed to be juggling the concepts Get and Set on one hand and In and Out on the other, before realizing they might not be synonymous.
    - [ ] ~ I seem to go into specifics about Input/Output. I might want to move those specifics out at one point. I think I might like to evaluate that as I sequentially go through the text.
    - [ ] ~ Perhaps later be honest in the Parameters article about this paradox. Other people may also feel uneasy about it and it makes it maybe more understandable why the terms are avoided.
- [ ] ~ Terms "In" and "Out" might be avoided.
    - [ ] ~ Because it seems ambiguous (for instance an object reference (__'Object In__' parameter?) can be considered both input and output at the same time.)
    - [ ] ~ Replacement terms might be ones such as __Get Object__ Parameter or __Set Value__ Parameter. It may not look as pretty, but it might help me avoid the paradox that I experience if I were to call them __In__ and __Out__.
- [ ] ~ Where I use parameter notation with connectors, I might want to be honest to for now ignore what those connectors mean, just accept that it makes them public and makes them parameters.

#### 2021-03 ~ Parameters Content Changes

The in / out / thru ideas about *Parameters* might take preference over one of parameters as a loosely coupled relationship between commands and classes. That take on it might have made things rather complicated instead of being more helpful. Parameter passing input output seemed simpler and perhaps a more usable alternative.

Once it was the other way around. The parameter passing input output idea seemed to have been set aside, because of some difficulty defining what __Input__ and __Output__ mean precisely on a more detailed level as well as in grander scope. But a simplified version of this story it might be more helpful as a way to express parameters in this diagram language.

#### 2019 Postponed Merging Conceptual Descriptions with Diagram Demonstrations

- [ ] ~ Might merge conceptual descriptions with diagram demonstrations.
- [ ] ~ The split up into a conceptual explanation and then separately an article for the diagram notation, might have been easy for writing the docs, but could be merged into a single article again for readability.

#### 2020-05-20 Postponed Content Changes for Parameters

- [ ] ~ Maybe make the idea of ubiquitous bidirectional relationships between commands and objects less centric. Or perhaps at least diverge into other approaches, so attempting to make room for expressing what goes on in other languages, rather than replacing the construct by another take on it.
- [ ] ~ I think maybe that bidirectionality is not of much use in this Circular Language Spec. It seems better off being placed in Circular Construct Drafts, because it just might not resonate much with other languages, programming seems to be able to live without it, and it seems alienating and full of implications, that seems to make concepts fall apart that did not seem to need to be ripped apart in the first place. I might be too harsh about it here. It is an interesting idea, I think, but it just complicates the idea of the diagram notation, which seems centric, not drastically changing how constructs work.
- [ ] ~ The Imported Parameter Concepts might be tidied up. The ideas from the original Symbol Language.doc might be processed: discarded or embedded into the main text. Merging the texts of the conceptual explanation and diagram notation might make things more overviewable and shorter / less text.
- [ ] ~ The approach of in/out/thru may be a more appropriate description.
- [ ] ~ Thru parameters had a particular implicit notation introduced in "Symbol Language (2004)": an object line that goes in both directions. Perhaps one implicit notation too many. But perhaps it can be introduced as an alternative.
- [ ] It seems the parameter connections might be implicit assignments (perhaps readable in "Symbol Language (2004)". It might only be implied in "Commands" > "Creation Behavior of Commands" in the Spec currently (2021-03-03). Perhaps it might deserve to be mentioned this possible implicit behavior of the lines (that cross command boundaries?). It might not be like that in all cases (clauses?). Introducting the concept lightly surrounded with maybe's may help.
- [ ] ~ This Argument: Making a mention of this.

#### 2020-06-11 Postponed Content Changes for Parameters / Command and Classes Loosely Coupled

- [ ] ~ (Moved to Circular Broader View\Classes)
- [ ] ~ I have questions about the dashed line usage of lines of the smaller squares:  
![](images/2019-08%20Circle%20Language%20Spec%20Revamp%20Notes.016.png)  
I do not understand why the class might point out the external command definition with a dashed line, while the objects point out the external command definition with a solid line. I think I might have followed a style choice more than an exact depiction of things? Might both lines express something that kind of works, leaving the options open for a stylistics choice to have class structure be more with dashed lines and object structure be more with solid lines? I suspect that I might leave this doubt open.
I am a bit amused by my own typical behavior, because half an hour later, I see that the explanation was already in the text.
I do feel it might be quite something to burden the reader with. I am hoping for a more clear meaning for dashed shapes in the future.

- [ ] ~ Another point of doubt might be:  
  ![](images/2019-08%20Circle%20Language%20Spec%20Revamp%20Notes.017.png)  
  Why is the line on the right no extended to the circle, so class structure and object structure look more alike except for the dashed and solid lines?

- [ ] ~ This "Command and Classes Loosely Coupled" idea (exchangeability between class-commands and command-parameters) might be moved to construct drafts. An approach with centric concepts of "Value In", "Value Out", "Object In", "Object Out" might be more practical. There might be (draft) content on that for instance in the "Symbol Language (2004)" document and perhaps elsewhere too. The idea of "Command and Classes Loosely Coupled" might have unnecessarily complicated things.

### 2021-05-03 Brainstorm Parameter Passing Reorganization

- [ ] ~ Might want organize it differently.
- [ ] ~ Confusion about what 'in' and 'out' mean seems to start soon.
- [ ] ~ Might want to list parameter passing types, and then the diagram notation.
- [ ] ~ And perhaps alternative names for the parameter passing types.
- [ ] ~ May want to limit it to writing the direct aspect of the parameter: value get/set, object get/set, rather than writing or reading from sub-objects.
- [ ] ~ Might leave out philosophy about whether writing or reading from an object reference, might make it in, out or thru. That might be for the Input Output chapter (in Construct Drafts possibly).
- [ ] ~ Passing values ByRef may be covered, but passing objects by ref may be double indirection, perhaps suitable for the pointers chapter.
- [ ] ~ Also C# has differentiation between __ref__ and __out__ parameters and lately also __in__ parameters. They may mean something different, also depending on whether it is value types or reference types. Reference types might have double indirection there, while value types seem to have singular indirection. It may be worth mentioning that in parameter passing after all. Because it might want to create a bridge between parameter passing types in e.g. C# and the diagram notation, rather than strictly keeping double-ref'ness situations in the Pointers chapter.
- [ ] ~ Passing structs may also have a consequence. Their values might be cloned one level deeper. It was called cloning with depth 2 once, but for mapping to e.g. C# it might just be the default behavior of by value parameter passing for structs. It may not be practical/needed to use the cloning depth notation for that.
- [ ] ~ The system of organization of parameter passings in C# or VB may clash with that of Circular. It might be relevant to clarify situations in Circular, but also map it to arguably common situations from other systems. It might be about *conveying* the idea. Clarifying how it might work. Otherwise it may leave many questions unanswered. Perhaps looking at Encircle inspires labeling them parameter types differently.
- [ ] ~ Info: [VB.NET ByVal, ByRef](https://docs.microsoft.com/en-us/dotnet/visual-basic/programming-guide/language-features/procedures/passing-arguments-by-value-and-by-reference) 
- [ ] ~ Info: [C# Parameter Passing]( https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/method-parameters)
- [ ] ~ Link about VB ByVal, ByRef seems to confirm my impression of the ByVal/ByRef difference for value types and reference types. In that sense the current explanation for Circular is incomplete, because ByRef for instance could work 2 different ways.
- [ ] ~ The info link about C# is also quite sound with my impressions.
- [ ] ~ The Circular parameter concepts and the mapping to constructs from other languages may be two separate things. Perhaps comparable to the Commands story. In the original parameter passing story in Circular (< 2021-05-04) things may seem to over flow into each other.
- [ ] ~ More like: *These* are the building blocks and *this* is what you can construct with it. Also with the wiggle room notation choices in it.