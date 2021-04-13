Encircle Language Spec Plans
============================

Commands | Content Changes
--------------------------

__Contents__

- [Postponed](#postponed)
    - [2019 Postponed](#2019-postponed)
    - [2020-08-21 Postponed Commands Chapter](#2020-08-21-postponed-commands-chapter)
    - [2020-05-18 Postponed Content Changes for Commands Chapter](#2020-05-18-postponed-content-changes-for-commands-chapter)
- [Done](#done)
    - [2020-05-18 Done Content Changes for Commands Chapter](#2020-05-18-done-content-changes-for-commands-chapter)
    - [2020-08-07 Done Content Changes for Commands Chapter](#2020-08-07-done-content-changes-for-commands-chapter)
    - [2020-07-24 Done Reformulating Commands Chapter](#2020-07-24-done-reformulating-commands-chapter)

### Postponed

#### 2019 Postponed

- [ ] ~ Maybe merge conceptual explanation with diagram notation explanation.
- [ ] ~ The split up into a conceptual explanation and then separately an article for the diagram notation, might have been easy for writing the docs, but could be merged into a single article again for readability.

#### 2020-08-21 Postponed Commands Chapter

- [ ] ~ Moving or removing marked out texts.
- [ ] ~ An additional reformulation phase might be appropriate.

#### 2020-05-18 Postponed Content Changes for Commands Chapter

- [ ] ~ Part done: What if you might just remove most of the rules imposed onto commands compared to regular objects? It seems that maybe no disasters might happen. I might like to evaluate which rules can be lived without so the idea might be presented in a simpler way.
- [ ] ~ It seems to me that I wanted to evaluate back then:
- [ ] ~ What concepts from other programming languages could look like in the diagram notation.
- [ ] ~ What each diagram notation situation could mean in terms of other programming languages like C#.
- [ ] ~ What might happen if you try to draw a parallel between objects and commands. Where things overlap, what the implications of being a command is, compared to an object.
- [ ] ~ That.
- [ ] ~ But it may have resulted in a bit of an overwhelming set of situations being shed light on.
- [ ] ~ Not sure to what extent this is a problem.
- [ ] ~ It's more of a content issue, rather than a formatting issue. I was focusing on formatting issues for now, so maybe postpone this.
- [ ] ~ The rules seem simpler in Encircle than in e.g. C#. It seems that derived from basics, several construct from e.g. C# might have a corresponding expression in Encircle using more basic rules. I seem to go through an effort to describe how supposedly more familiar constructs might be represented in Encircle. It seems quite an effort to explain something that might be simpler, in terms that might be more complicated. But it might have a purpose as to build a bridge between what a reader might already be familiar with, to a different idea, that the reader is attempted to be introduced to. I have some doubt about whether the story could be simpler. Maybe it could be simpler by adding something: first the basic rules with no edge cases, then an admission of it e.g.: "Familiar constructs from other programming languages might be expressed using these basic building blocks from Encircle. Each of those familiar constructs seems to be a specific use-case of basic building blocks in Encircle."
- [ ] ~ "Changing Inactive to Executable" section:
    - Seems quite Encircle Broader View-ish. Use-cases of how you might use it in a less conventional setting. What it might be like if the internet was a single computer that everyone was programming and using at the same time, with more parts changeable and accessible to multiple people at the same time.
- [ ] ~ The 'many rules' around commands seem circumstantial: practical behavior that might be found in other programming languages. At the other end of the spectrum might be a hypothetical system, in which no control is imposed with rules as such, which may only cause possibly inconveniences of e.g. concurrency issues like reading out half-written objects and such. The 'rule richness' might already be in place if the notation were to be used in an existing system or a new system might be developed that uses the notation and the programmers might use their own heads on how to make it practical. The 'rule free' variation might also be an experimentally funny thing to develop. It might still function as a coherent base for programming, be it there could be concurrency issues for instance. I really wonder if the rules might have to be embedded in the text. I might be more comfortable to extract these rules as a separate article that just aims to expose a system of rules that a programming environment might impose onto command objects, to make it more practically workable and evasive of troublesome situations. Some programming environments just support this behavior out of the box. "Local variables and parameters are automatically thread-safe" is one of those rules that I come to rely on when programming concurrent systems. (I personally find concurrency one of the more difficult issues to deal with in programming.) If rules are not imposed in Encircle, that thread safety could fall to pieces in a way. I just think a description of the notation does not need to rely on the existence of those rules. If I want to go into it, I might want to separate that from the main article, because it might make the idea easier to absorb. The rules I state were maybe just my attempt to prove to myself what might it take for objects and commands to be exchangeable and what rules does it take to make object behave like commands in an orderly fashion and does this notation work at all for the many command-oriented constructs that exist in programming languages today. Now I am more confident that it works, the main explanation might not have to be a stack-up of 'proof', just an exposition of the main point.
- [ ] ~ Where I use parameter notation with connectors, I might want to be honest to for now ignore what those connectors mean, just accept that it makes them public and makes them parameters.
- [ ] ~ I see an analogy between the lifecycle of running a command and an object's creation, constructor, initial setting of required values, and running of active commands directly in it.
- [ ] ~ Outtakes, perhaps for Encircle Broader View:
    - [ ] ~ It seems it might be possible to make combinations of symbols that might not have an equivalent in another language.

### Done

#### 2020-05-18 Done Content Changes for Commands Chapter

- [x] Commands Main Concepts article:
    - [x] A lot seems to be hung up on definition of words and expression of concepts from other languages.
    - [x] But I think just the concepts and notation could become more centric.
    - [x] From those concepts and notation might follow how existing constructs in the world might have a (unique?) expression in Encircle.
    - [x] I might want to take the reader along with *that* idea. A smaller set of elements in Encircle might translate to a larger set of constructs known from other languages.
- [x] My main concern is that I do not like that much the main structure upon which the text is laid out.
    - [x] The current structure is based on constructs and rules from other languages.
    - [x] It is my opinion that that is not an impractical subdivision.
    - [x] But what seems to happen is lots of details covered that do not describe the core of what the notation might do.
    - [x] So perhaps it can be replaced with the raw diagram expression elements and their meaning.
    - [x] And then more of a sum op of how constructs fit into that, then lastly more detailed rules perhaps.
- [x] Possible new writing structure:
    - [x] Short definition of the concept of commands.
    - [x] The raw diagram expression elements and their meaning.
    - [x] A bridge saying constructs might be derived fom these basic elements.
    - [x] Then name and diagram expression for each construct. (Possibly use existing texts as inspiration.)
        - [x] Short definition of the construct?
        - [x] Less explanation?
        - [x] ~~A short sentence covering diagram elements' usages?~~
        - [x] Pseudo-code
            - [x] It might be vague to compare it to other programming language and not show some pseudo-code how it might look there. I know it sort of breaks my idea of not comparing to other languages that might, but here I explicitly decide to do it anyway, so I may as well 'own' it.)
    - [x] Synonyms as sum-ups. (Intended to be deprecated to a detail.)
    - [x] ~~Extracting rules and put them in the bottom?~~
    - [x] Add pictures
    - [x] Evaluate if remaining things are to be moved or removed.
- [x] Clauses:
    - [x] Inactive clause could also be a local function.
    - [x] Inactive clause could be the clauses of an if-statement for instance.
    - [x] Active clause could be a braced code block.
    - [x] I did seem to reinvent the word clause there. I wonder if that is necessary. It seems to raise the issue of perhaps you might use IT terminology more as known by the industry and not reassign and reinvent terminology.
    - [x] The structure choices indicate I might have sections specifically for local functions, clauses (e.g. if clauses and what have you), local code blocks.

#### 2020-08-07 Done Content Changes for Commands Chapter

- [x] The new beginning of the chapter
    - [x] Is supposed to be what it 'should become'.
    - [x] I might evaluate its state.
- [x] The other things may be:
    - [x] Topics that may have been already covered by the new beginning.
    - [x] Topics that might be details that had better be put in Encircle Broader View.
    - [x] Topics might be details that are unrequired, might cloud the main point. They might be removed.
    - [x] Details that might be kept in this chapter, but given more of a place at the bottom, rather than the top. Maybe even split it off as a separate chapter to keep this chapter 'clean'.
- [x] Stereotyping text fragments.
    - [x] And marking them grey for removal and orange for postponement.
    - [x] Already used stereotypes:
    - [x] << already covered >>
    - [x] << nice formulation >>
    - [x] << detail >>
    - [x] << details >>
    - [x] << move >>
    - [x] << synonym >>
    - [x] << repeated >>
    - [x] << explains other technology >> 
    - [x] << commands compared to objects >>
    - [x] << creation behavior of commands >>
    - [x] << broader perspective >>
    - [x] << parameters >>
- [x] I seem to be having difficulty judging how to stereotype pieces of texts. Perhaps reading over the 'main' again might help.
- [x] Clause issues:
    - [x] Clause might be displayed as a command reference. In-line command definitions is what it looks like now. You might not see the difference between code blocks other than a clause seems nameless, which is sort of not necessarily true. In Encircle it does not seem to matter much, but to compare it to other languages, distinction might be sort of important for the explanation.
    - [x] I could do the same correction to the Lambda Expression section.
    - [x] Maybe build up step by step in images might be better?
    - [x] I start doubting myself here and it is difficult for me now.
    - [x] I might want to grab the core of the doubt and express it honestly.

#### 2020-07-24 Done Reformulating Commands Chapter

I say Commands *chapter*, but previously I seemed to have started one detail level deeper: article-level rather than chapter-level. I wonder whether I might do that again. For that I might look at the articles and how large they are, a bit of the concrete content.

Steps:

- [x] Going through chapter' articles' content to see what the scope-status is of the issues.
- [x] Reading over the 'Postponed Content Changes' notes in this planning document.

Some of the chapters might be not main issues, but according to my opinion, they do decorate the topic making it come alive, though the optionality of the issues might be fact.

The Command Redirection article might have issues that may be moved to the Pointers chapter. Some single-step redirections might be a main thing, useful to inform at this level, but recursion might be questionable to belong there, and the 'Target' of redirections: those topics were earlier on moved to the Pointers chapter from the Objects chapter or Classes chapters for instance, so it might make sense to move the Command-related 'targets' topic there too.

This may be out of scope: but the parameters topics that are brushed over in the Commands chapter seem odd in place, because there is also a parameters chapter that follows later. Perhaps some details about parameters might be moved from the Commands chapter to the Parameters chapter, but perhaps there is just a mutual dependency between concepts (overlap) that a sharp separation might not be what to go for.

Misc Issues:

- [x] Parent Controls Its Sub-Executions section:
    - [x] might be a rule that might be scratched. It might have implications if this is not a rule, but the solution might be obvious, if you let go of purist ideas about how it works in 'regular' object oriented programming.
- [x] Command Referrers section:
    - [x] Might be moved to Pointers chapter or Relationships chapter, not sure. I moved 'Referrers' sections before to somewhere, whereas they were spread over different chapters before. I think Relationships chapter.
