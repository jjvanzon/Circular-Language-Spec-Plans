Encircle Language Spec Plans
============================

Source Control Migration | 2019-08 | Notes
------------------------------------------

- Converting 'version folders' to source control history.
- Isolating Encircle language content in separate git repositories.

__Contents__

- [Rough Plan](#rough-plan)
- [Done](#done)
    - [2019-08-04 Done Notes Converting Version Folders to Source Control History](#2019-08-04-done-notes-converting-version-folders-to-source-control-history)
    - [2019-08-05 Done Version Control](#2019-08-05-done-version-control)
    - [2019-08-10 Done Brainstorm Complexity Preserving Rename History](#2019-08-10-done-brainstorm-complexity-preserving-rename-history)
    - [2019-08-11 Done Basic Math Version Folder to Source Control History?](#2019-08-11-done-basic-math-version-folder-to-source-control-history)
    - [2019-08-11 Done Controls Concepts Version Folders to Source Control History](#2019-08-11-done-controls-concepts-version-folders-to-source-control-history)
    - [2020-02-03 Done Notes Planning Docs Git Migration](#2020-02-03-done-notes-planning-docs-git-migration)
    - [2020-02-03 Done Planning Docs Git Migration](#2020-02-03-done-planning-docs-git-migration)
    - [2020-12-03 Done Git Migration: Removing "Creator"](#2020-12-03-done-git-migration-removing-creator)
    - [2021-01-16 Done Git Migration](#2021-01-16-done-git-migration)
    - [2021-01-16 Done Git Migrations](#2021-01-16-done-git-migrations)
    - [2021-01-16 Done Brainstorm Git Migration](#2021-01-16-done-brainstorm-git-migration)
    - [2021-01-23 Done Git Migration Corrections](#2021-01-23-done-git-migration-corrections)
    - [2021-01-24 Done Git Migration Corrections](#2021-01-24-done-git-migration-corrections)
    - [2021-02-02 Done Git Migration Corrections](#2021-02-02-done-git-migration-corrections)

### Rough Plan

- [x] Converted Encircle Docs version folders to source control history.
- [x] Converted Planning Docs version folders to source control history.
- [x] Splitting off Encircle language docs into a separate git repository.
- [x] Splitting off Planning Docs for Encircle language into a separate git 

### Done

#### 2019-08-04 Done Notes Converting Version Folders to Source Control History

This is a lot of work.

- [x] Exp: Search for XXXX in the folder "Encircle Docs\1. Language".
- [x] Obs: 54 matches.
- [x] Hyp: 54x a version folder structure to convert to source control history.
- [x] Less than I thought and probably doable.
- [x] Maybe rename all commits, putting the version number in front, so it is more apparent that it is alternative source control history.

#### 2019-08-05 Done Version Control

There is a folder 'Previous Versions' that might make you think you forgot to put those at the beginning of the conversion from version folders source control history. But they are not necessarily previous versions of documentation, but more like previous versions of systems.

#### 2019-08-10 Done Brainstorm Complexity Preserving Rename History

The version folders I have left to convert to source control history are complex, if you also try to get a rename mapping in check. Even if you ignore the rename mapping, you have quite some work to do.

It was not expected that there might be such complexity in preserving rename history, but noticing that there is, makes me re-evaluate my plans.

To get overview of the amount of version folders still to cover: The version folders are visible on the 'root' level per chapter. The amount of version control on *sub-*topics is limited to just one (24. Creation Behavior Of Calls). Its about the *main* topics: Commands, Parameters, Module, Execution Control, Black Boxing, Interfaces, Events and    Inheritance. One of those topics has intensely many version folders (Black Boxing). About 3 topics have a 'normal' amount of version folders. The others have a quite small amount of version folders. If you ignore trying to preserve rename history, then you might be done today. If you try to preserve rename history, it might take you probably many days, like 4 or something. And I think the motivation might recede if I do that.

So I have already made my choice. I might not make effort to preserve rename history. I might just methodically convert the version folders to source control commits.

#### 2019-08-11 Done Basic Math Version Folder to Source Control History?

The 2 versions' contents:

2005-01-06 00 Former Documentation:

> Any programming topic about math I had at the time is thrown into one document here:
>
> - JMath 0.9 docs in Dutch
> - Simple Math operators
> - Ideas about 'regulated systems'
> - Number Bases
> - Brainstorm: Some alternative wordings and loose ideas written down.
> 
> The XXX version is only Simple math operators and how they can be implemented as objects.

Idea bout converting version folder to source control history:

> So they are not mutually exclusive at all.  
> I have doubt whether I should even do the conversion from version folders to source control history here.
> Using my rules, I'd put the older docs in archive, but neither 'version' is more deprecated than the other. They are both old, and they are both the latest version of things.  
>
> The math as objects does have a link to how math can be made not intrinsic to the language, but an extension library, which can still be compiled to good old CPU instructions. That concept is interesting for the idea of Encircle. But... none of this documentation is well worded to support that concept...

#### 2019-08-11 Done Controls Concepts Version Folders to Source Control History

- [x] I can convert the version folders to source control history the regular way, because each successive version does seem to replace the former version.
- [x] Where is that navigation model brainstorm?
    - [x] It is in the control concepts' root folder. It has a doc in it directly, which I overlooked.

#### 2020-02-03 Done Notes Planning Docs Git Migration

- [x] Isolating a git repository with just the Encircle Docs planning out of a git repository with planning docs of misc subjects.
- [x] Combining parts into 1 script,
- [x] Rerunning scripts on the very latest version.
- [x] Do checks by sampling.
    - [x] KDiff lists of files in history of previous and new run.
        - [x] I see newer files appear in the new list.
    - [x] Checking out some commits and KDiff working folder of Encircle-Language-Spec-Plan and JJs-Planning-Docs.
    - [x] Use Visual Studio checking 'by hand' the histories of some files compared between Encircle-Language-Spec-Plan and JJs-Planning-Docs.
- [x] Archived things in JJs-Planning-Doc.
- [x] Organizing Encircle-Language-Spec-Plan (e.g. moving lost topics to an appropriate spot).

#### 2020-02-03 Done Planning Docs Git Migration

- Folders in current version:
    - \Encircle Language Spec Plan
    - \Other\2. Future\Postponed\1. Encircle Language Spec (Out of Scope)
    - \Other\3. Done\2008 - 2008 Encircle Language Spec (Out of Scope)
- [x] Might try to strip a git repository's major parts that are out of scope, just as a start.
    - [x] Scripted
    - [x] Ran
    - [x] Checked diff of lists of files in full history.
- [x] Might weed out major blocks with exceptional cases in it.
- [x] May check document contents for that to make decisions.
- [x] Checking: KDiff full lists of files in history of before and after.
- [x] Corrected script
- [x] Rerun
- [x] Checking:
    - [x] KDiff lists of files in history of previous and new run.
    - [x] Use Visual Studio checking 'by hand' the histories of each files compared between Encircle-Language-Spec-Plan and JJs-Planning-Docs.
    - [x] Checking out some commits and KDiff working folder of Encircle-Language-Spec-Plan and JJs-Planning-Docs.
- [x] ~~Try removing content with my brother's first name in it.~~

#### 2020-12-03 Done Git Migration: Removing "Creator"

- [x] Considering removal of experiments 0.4 and 0.9 from Encircle-Docs.
- [x] Removing more seems doable with a smaller additional run at the end.
- [x] I am quite unsure about involving the "Creator" topics. I once thought I might merge Creator and Encircle Language into one. But now I think Creator might be much about framework (code generation, aspects, generated user interfaces). Framework was deemed out of scope. I am unsure, because the topics of Creator and Encircle Language seems to overlap.
- [x] Experiments 0.4, 0.9 and 2.0 may partially be about programming language, but a lot might be considered better solvable by a framework/library solution. So this seems ambiguous.
- [x] Experiments 0.4 and 0.9 might be code generator / aspects / framework, while experiment 2.0 looks more like a bit a programming language. It has a text code and a parser and everything. But I guess a totally different programming language than Encircle. Perhaps experiments 0.4 and 0.9 should be moved to framework , ~~while experiment 2.0 is actually more in scope as a programming language.~~
- [x] Reading the Creator documentation I start having doubts. How might relational / aspect oriented look in Encircle? If Encircle could harbor constructs that make it possible to program things as was dreamed about with Creator, then might the goal Symbol = Creator be reached? And how might it look? I think I might have a way to define aspects in a general sense. I do not seem to know how yet precisely. Nor do I seem to have the time / priority / ability to work it out. ~~So in the meantime it seems Creator should still be part of this.~~
- [x] I believe I saw in plans and documentation that comparing Creator with Encircle actually seems to have enriched Encircle the language. Concretely with multiplicity, creation/destruction/new/annul/null, a notation for bidirectional relations, reflection and extension ideas. Also some ideas that might only have complicated things a bit, that I was not quite able to work out (perhaps less recognizable ideas like: "automatic containment" and "flat & structure interchange"). I believe that the future Creator ideas could inspire more enrichment of the Encircle language. Perhaps with aspect oriented and more system extensions features, I was once thinking about. I just cannot picture it yet. I think it might be best to leave that an open question and keep the Creator documentation involved in this repository, perhaps for future inspiration. > I might see it more like one system being inspiration for another. The planning also excluded experiment 2.0, so perhaps the product documentation should too. I think the article Symbol = Creator might introduce that idea. So I may leave that in there.

#### 2021-01-16 Done Git Migration

- [x] Checkout a more recent commit and compare in KDiff the whole folder of Encircle-Docs and Software-System-Docs.
- [x] Moving around things in Encircle-Docs
- [x] Archiving things in Software-System-Docs

#### 2021-01-16 Done Git Migrations

- [x] Finishing analysis of things to remove.
- [x] Changing the scripting with corrected removals
- [x] Rerunning the script
- [x] More practical checks?
    - [x] Using KDiff to compare this run and previous run's lists of all files in history.
    - [x] ~~The 'preparation' Excel, for the pictures.~~ > Diff between two runs might say enough.
    - [x] ~~Viewing all pictures in master.~~ > Diff between two runs might say enough.
    - [x] Comparing *master's* lists of files (using KDiff and/or JJ Utilities)
    - [x] Checking out some commits and looking at the checked out file tree?
        - [x] I was insecure about the first few commits. History does not seem to map back easily to those first few commits. ("Version 2008-07-13 XX: Before ordering it more by how you read it" seems the 'terminator' quite frequently.)
- [x] More laborious checks?
    - [x] Checking each remaining file for completeness of history
        - [x] 1.1. Encircle Language Spec
        - [x] 1.2. Encircle Constructs Drafts
        - [x] 1.3. Encircle Broader View
        - [x] 2. Framework
        - [x] 3. Operating System
        - [x] 5. Archive
    - [x] Comparing lists of all files in history.
    - [x] ~~Do over inspections of file trees of each commit?~~
    - [x] ~~Inspecting what more might be erroneously removed from the first 'large' commits?~~
    - [x] ~~Incremental commits may harbor things to remove too.~~
- [x] Possible plan for next run:
    - [x] Scripting with new corrections.
    - [x] Running new script.
    - [x] Random sampling some check-outs (+ folder diffs between Encircle-Docs and Software-System-Docs).
    - [x] Random sampling of history of single files.
    - [x] Comparing 'before' and 'after' file lists.

#### 2021-01-16 Done Brainstorm Git Migration

I seemed to have removed "Operating System" topics. With that the version history of internet as a single computer.

I might have been focusing on what remains, less on what was removed.

Brainstorm:

There seem to be 3 categories of commits:

1) large version folders at the beginning
2) smaller version folders in the middle
3) incremental commits at the end

For the large ones I seem to have mostly inspected the file trees.  
For the middle one I seem to have mostly inspected the commit's (file) list.  
The last incremental one I do not seem to have inspected yet.  
I also do not seem to have inspected the total file list from history yet.

#### 2021-01-23 Done Git Migration Corrections

- [x] Collapsing individual picture file removals into more whole folder removals.
- [x] Keeping index pages:
    - [x] In the area of 'broader view' perhaps.
    - [x] With the general idea how it might work in Encircle.
- [x] "Integration" / "Legacy" (index pages)
    - [x] For instance: "2. Framework\0. Language\2. Integration\Integration.doc"
    - [x] Gathering paths.
    - [x] Commenting out paths to keep.
    - [x] ~~Collapsing some things to whole folders.~~
- [x] "Expression" (index pages)
    - [x] For instance: "2. Framework\0. Language\1. Language\6. Expression\Expression.doc"
    - [x] Seems already there, except a *copy* placed under "Framework".
- [x] "More Text Codes" / "Legacy Text Codes" / "Additional Text Codes" (index pages)
    - [x] For instance: "2. Framework\0. Language\1. Language\6. Expression\6. More Text Codes\More Text Codes.doc"
    - [x] Gathering paths.
    - [x] Commenting out paths to keep.
    - [x] Collapsing some things to whole folders.
- [x] "Protocols" (index pages)
    - [x] For instance: "2. Framework\0. Language\2. Integration\7. Protocols\Protocols.doc"
    - [x] Gathering paths.
    - [x] Commenting out paths to keep.
    - [x] ~~Collapsing some things to whole folders.~~
    - [x] ~Stripping subsequent removals.
- [x] "Framework" (index pages)
    - [x] Framework seems deleted as a whole somewhere. Trying to be more selective.
- [x] "Libraries" (index pages)
    - [x] For instance: "2. Framework\0. Language\3. Libraries\Libraries.doc"
    - [x] Gathering paths.
    - [x] Commenting out paths to keep.
    - [x] Collapsing some things to whole folders.
    - [x] Stripping subsequent removals.
- [x] "Object Storage" (index pages)
    - [x] For instance: "3. Operating System\4. Storage\1. Object Storage\Object Storage.doc"
    - [x] Gathering paths.
    - [x] Commenting out paths to keep.
    - [x] Collapsing some things to whole folders.
    - [x] Stripping subsequent removals.

#### 2021-01-24 Done Git Migration Corrections

- [x] Did the analysis it wrong? Sort of? The reasons this is so intense, might be that I am comparing full file lists in history now instead of master file lists.
- [x] Kept a few extra pictures that seemed harmless.
- [x] Should probably keep:
- [x] "3. Operating System/4. Storage/1. Object Storage/Object Storage.doc"
- [x] "17. Storage/1. Object Storage/Object Storage.doc"
- [x] Might remove:
    - [x] "01. Code/5. Data Concepts/1.1. Registration Lists/Registration Lists.doc"
    - [x] "01. Code/5. Data Concepts/1.2. Item Remove/Item Remove.doc"
    - [x] "01. Code/5. Data Concepts/2.0. Undouble/2.1. Undouble/empty.txt"
    - [x] "01. Code/5. Data Concepts/2.0. Undouble/2.2. Undoubled Relations/Undoubled Relations.doc"
    - [x] "01. Code/5. Data Concepts/3.0. Collection/3.1. Filters, Sorts, Searches, Joins & Indexes/Filters, Sorts, Searches, Joins & Indexes.doc"
    - [x] "01. Code/5. Data Concepts/3.0. Collection/3.2. Collection/Collection.doc"
    - [x] "01. Code/5. Data Concepts/3.0. Collection/3.3. SQL & Tables/SQL & Table Approach.doc"
    - [x] "01. Code/5. Data Concepts/3.0. Collection/Collection.doc"
    - [x] "01. Code/5. Data Concepts/4.0. Search/4.1. Find/empty.txt"
    - [x] "01. Code/5. Data Concepts/4.0. Search/4.2. Find Or Add/empty.txt"
    - [x] "01. Code/5. Data Concepts/4.0. Search/4.3. Wildcards/Wildcards.doc"
    - [x] "01. Code/5. Data Concepts/5.0. Import & Export/5.1. Import & Export/Import & Export.doc"
    - [x] "01. Code/5. Data Concepts/5.0. Import & Export/5.2. XML/XML.doc"
    - [x] "01. Code/5. Data Concepts/6.0. Persistance Delay/6.1. Locking/Locking.doc"
    - [x] "01. Code/5. Data Concepts/6.0. Persistance Delay/6.2. Transactions/Transactions.doc"
    - [x] "01. Code/5. Data Concepts/6.0. Persistance Delay/6.3. Apply, Ok, Cancel/Apply, Ok, Cancel.doc"
    - [x] "01. Code/5. Data Concepts/6.0. Persistance Delay/6.4. Streaming Access/Streaming Access.doc"
- [x] Might like to keep:
    - [x] "2. Framework/1. Code Concepts Extended/2. Circularity/1. Circularities/empty.txt"
    - [x] "2. Framework/1. Code Concepts Extended/2. Circularity/2. Circularity Handling/empty.txt"
    - [x] "2. Framework/1. Code Concepts Extended/2. Circularity/3. Pointer Circularity/Pointer Circularity.doc"
    - [x] "2. Framework/1. Code Concepts Extended/2. Circularity/Circularity.doc"
    - [x] "2. Framework/1. Code Concepts Extended/Code Concepts Extended.doc"
- [x] Might keep:
    - [x] "04. Security & Safety/1. Access Control/Access Control.doc"
    - [x] "16. Security & Safety/1. Access Control/Access Control Ideas.doc"
    - [x] "16. Security & Safety/1. Access Control/Access Control.doc"
    - [x] "18. Security & Safety/Access Control/Access Control.doc"
    - [x] "3. Operating System/3. Security & Safety/1. Access Control/Access Control Ideas.doc"

#### 2021-02-02 Done Git Migration Corrections

- [x] Could keep:
    - [x] "0. Introduction/2007-09-23 00    0.9a/Interesting Old Introduction To J Data.doc"
    - [x] "0. Introduction/Interesting Old Introduction To J Data.doc"
    - [x] "00. General/00. 2007-09-23 00    0.9a/Interesting Old Introduction To J Data.doc"
    - [x] "00. Introduction/2007-09-23 00    0.9a/Interesting Old Introduction To J Data.doc"
    - [x] "01. Introduction/2007-09-23 00    0.9a/Interesting Old Introduction To J Data.doc"
    - [x] "01. Code/4. Coding Concepts/03.01. Default Values/Default Values.doc"
    - [x] "02. Code/3. Data Concepts/10.01. Defaults/12.01. Default Values/Default Values.doc"
    - [x] "02. Code/4. Data Concepts/10.01. Defaults/12.01. Default Values/Default Values.doc"
    - [x] "03. Code/04. Concepts/Coding Concepts/4.1. Default Values/Default Values.doc"
    - [x] "2. Framework/2. Data Concepts/10.01. Defaults/12.01. Default Values/Default Values.doc"
    - [x] "01. Code/5. Data Concepts/6.0. Persistance Delay/6.1. Locking/Locking.doc"
    - [x] "01. Code/5. Data Concepts/6.0. Persistance Delay/6.2. Transactions/Transactions.doc"
    - [x] "02. Code/3. Data Concepts/6.0. Persistance Delay/6.1. Locking/Locking.doc"
    - [x] "02. Code/3. Data Concepts/6.0. Persistance Delay/6.2. Transactions/Transactions.doc"
    - [x] "02. Code/4. Data Concepts/6.0. Persistence Delay/6.1. Locking/Locking.doc"
    - [x] "02. Code/4. Data Concepts/6.0. Persistence Delay/6.2. Transactions/Transactions.doc"
    - [x] "03. Code/04. Concepts/Data Concepts/6.0. Persistance Delay/6.1. Locking/empty.txt"
    - [x] "03. Code/04. Concepts/Data Concepts/6.0. Persistance Delay/6.2. Transactions/Transactions.doc"
    - [x] "2. Framework/2. Data Concepts/6.0. Persistence Delay/6.1. Locking/Locking.doc"
    - [x] "2. Framework/2. Data Concepts/6.0. Persistence Delay/6.2. Transactions/Transactions.doc"
- [x] Can remove:
    - [x] "1. Language/1. Language/7. Other Topics/1. Utilities/5.2. Text Statistics.doc"
    - [x] "10. Encircle Constructs Drafts/7. Other Topics/1. Utilities/5.2. Text Statistics.doc"
    - [x] "1. Language/1. Language/2. Fundamental Principles/3. Achievability/5.0. C++.doc"
    - [x] "02. Code/3. Coding Concepts/05. System Objects/XXXX-XX-XX XX/60. Connectors/~WRL3057.tmp"
    - [x] "02. Code/3. Coding Concepts/11. Interfaces/2010-05-07 XX    0.95/1. Introduction/~WRL1420.tmp"
    - [x] "1. Language/1. Language/3. Code Concepts/05. System Objects/XXXX-XX-XX XX/60. Connectors/~WRL3057.tmp"
    - [x] "1. Language/1. Language/3. Code Concepts/11. Interfaces/2010-05-07 XX    0.95/1. Introduction/~WRL1420.tmp"