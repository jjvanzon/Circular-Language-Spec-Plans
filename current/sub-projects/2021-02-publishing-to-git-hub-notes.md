Circular Language Spec Plans
============================

Publishing to GitHub | 2020-02 | Notes
--------------------------------------

__Contents__

- [Publishing to GitHub | 2020-02 | Notes](#publishing-to-github--2020-02--notes)
    - [TODO](#todo)
        - [2023-11-10 TODO SEO](#2023-11-10-todo-seo)
        - [2022-01-22 TODO Publishing GitHub Pages](#2022-01-22-todo-publishing-github-pages)
        - [2022-01-22 TODO Publishing Articles to GitHub Pages](#2022-01-22-todo-publishing-articles-to-github-pages)
    - [Postponed](#postponed)
        - [2021-04-06 Postponed Publishing Details](#2021-04-06-postponed-publishing-details)
    - [Done](#done)
        - [2021-04-22 Done Brainstorm New Name](#2021-04-22-done-brainstorm-new-name)
        - [2019-08-05 Done Open Source Brainstorm](#2019-08-05-done-open-source-brainstorm)
        - [2021-02-09 Done Publishing](#2021-02-09-done-publishing)
        - [2021-02-08 Done Publishing: My Brother's First Name](#2021-02-08-done-publishing-my-brothers-first-name)

### TODO

#### 2023-11-10 TODO SEO

- [x] Introduction SEO
- [x] Objects SEO
- [x] Classes SEO
- [x] Commands SEO
- [ ] Execution Flow SEO
- [ ] ...

#### 2022-01-22 TODO Publishing GitHub Pages

Publishing to GitHub pages, selectively.  
Step by step, article by article carefully for now.

- [x] Renaming README's to have lower case extension .md
- [ ] Links
    - [x] Automatic links do not seem to work. Using the syntax `[Description](https:\\my-url)` may help.
    - [x] Back links
        - [x] Adding `[back](./)` in a document
        - [x] And `[back](..)` in a folder or README.md.
    - [ ] External links to open in new tab using `<a>` tags.
- [x] Headings:
    - [x] Removing Circular Language Spec headings?
    - [x] MarkDown TOC level settings not appropriate anymore?
    - [x] ~~Reconsider headings having only one pipeline character.~~
- [x] Adding author name and date to articles when published.
- [x] "Preliminary documentation": Annotated just below article heading.
- [ ] ~ More images at top of pages.
- [ ] `-----`
- [ ] Possible formatting solutions:
    - [ ] Images better sized using `<img>` tags.
    - [ ] Horizontal lines:
        - [ ] Grid rows with only dashes in it seemed to not render.
        - [ ] Horizontal line `-----` seems interpreted as headings in bullet pointed lists.
        - [ ] `<br/><br/>` seems an alternative for horizontal space in lists.
        - [ ] `-----` formatted as inline code seems to help inside table rows.
    - [ ] Table layout seems applied inappropriately when using `|` in a bullet point's text. Replaced with commas `,`.
    - [ ] MarkDown (tables) nested in HTML tables showed the MarkDown literally inside the rendered page.
        - [ ] Trying a trick `<td markdown="1">` from <a href="https://stackoverflow.com/questions/15917463/embedding-markdown-in-jekyll-html" target="_blank">here</a> helped.

#### 2022-01-22 TODO Publishing Articles to GitHub Pages

- [ ] ~ Classes: Might nicify formatting.

### Postponed

#### 2021-04-06 Postponed Publishing Details

- [x] Emoji in commit messages: https://github.com/yzhang-gh/vscode-markdown
- [x] May rename "Encircle" => "Circular"
- [x] Adjusting image sizes: https://stackoverflow.com/questions/14675913/changing-image-size-in-markdown
- [ ] Tips to get noticed on GitHub: https://codarium.substack.com/p/my-secret-sauce-to-make-github-repositories
- [ ] Demo video?
    - [ ] Just clicking and scrolling through content.
    - [ ] On YouTube linking to GitHub.
    - [ ] On GitHub linked a YouTube movie.

### Done

#### 2021-04-22 Done Brainstorm New Name

Circle was taken:
https://www.circle-lang.org

-----

"Symbol" also taken:
https://feaforall.com/introduction-symbol-language-onscale-analyst-script/

By a niche tool?
OnScale Analyst

https://support.onscale.com/hc/en-us/articles/360002427698-Introduction-to-Analyst:
Quote: "Note: Strictly speaking "Symbol" refers just to those commands listed in the Symbol Command section of the Command Reference. That being said, here at OnScale we sometimes loosely use "Symbol" to refer to anything written in Analyst."

https://onscale.com/blog/how-to-build-a-model-in-just-11-lines-of-code/

-----

C°
Centigrade?

-----

"Circular"
Seems available.
I think I like that better than Encircle.

#### 2019-08-05 Done Open Source Brainstorm

- [x] How do you even license documentation?
    - [x] I wanted to throw an MIT license against it, but that is for code... hmm...
    - [x] Here is some information: <https://dreamsongs.com/IHE/IHE-50.html> 
    - [x] This might be something: FreeBSD Documentation License
    - [x] It basically seems an MIT license, but then for documentation.
- [x] ~~Is it really such a good plan to open source it? Am I really not just throwing away money? Maybe it is better to wait with that decision, after I know where things are heading with work and income? > Think I might do it anyway.~~
- [x] There is an '... IPC Parse.doc' text in the source control history. It should be deleted. I guess I might search for intellectual property problems. This in docs that are so intellectual property sensitive. Before open sourcing it, you need to do this intellectual property check.
- [x] 2004-00-00 XX    Symbol Language\Symbol Pictures (Keep Packed, Paths Too Long).zip has intellectual property problems in Pictures\Diagram Examples.
- [x] ~~Is the summary of the C and C++ in Summaries of Other Languages an intellectual property problem? I summarized the languages using MSDN as source information. Hmm... If I didn't mention the source information it might not look like an intellectual property problem. Just I read stuff about a programming language and wrote stuff down... not sure. > It think this is an unreasonable doubt.~~
- [x] "Relational Structure"
    - [x] Might mention a relationship example which might not be kept in there. It also may reference a company name.
    - [x] I think I might be better off removing that document from the Circular-Language-Spec repository.
- [x] Renaming Circular-Language-Spec-Plan to Circular-Language-Spec-Plans (plural).
- [x] Reorganizing Broader View and Construct Drafts knowing they might also be published?

#### 2021-02-09 Done Publishing

- [x] Readme's?
- [x] Just publishing it?
- [x] Durable links:
    - [x] Renumbering the sections, the URL's might not stay constant. A not-numbered file name and an index/contents page with links might be an alternative.
- [x] Replacing swear words
- [x] The name "Circle" is used by a similar product. Should I rename? And to what?
    - [x] "Encircle"
    - [x] ~~Considered alternatives: "Symbol" / "JJ's Computer Language" / "JJ's Visual Language" / "This Computer Language".~~
    - [x] In main repo:
        - [x] Replacing "Circle" with "Encircle" in content
        - [x] Replacing "circle" with "encircle" in doc file names (and links to them)
        - [X] Correcting heading layout
        - [x] Replacing "Encircle 3" and with "Circle 3"
        - [x] Double-checking occurrences of "Encircle"
        - [x] Correcting articles ("a" / "an"): Correcting "a Encircle" to "an Encircle" (and "a *Encircle*" as well)
    - [x] In planning docs repo:
        - [x] Replacing "Circle" with "Encircle" in content
        - [x] Replacing "circle" with "encircle" in doc file names
        - [x] Correcting heading layout
        - [x] Correcting articles ("a" / "an"): Correcting "a Encircle" to "an Encircle" (and "a *Encircle*" as well)
        - [x] ~ Double-checking occurrences of "Encircle"
    - [x] Renaming the repo's
    - [x] Merging changes

#### 2021-02-08 Done Publishing: My Brother's First Name

- [x] Is in some sub-project planning doc.
- [x] I can take it out of the current version.
- [x] Should I ask him if he is OK with it staying in the source control history or if he wants it out of there?
- [x] Also in "2009-06 01 Circular Language Spec Plan Part B, Sub-Projects" his first name is mentioned.
- [x] I may be better off removing some items of history from Circular-Language-Spec-Plan completely for this purpose.
- [x] There is also a split up between a doc for 'in-scope' and one for 'out-of-scope'.
- [x] It is even in this document. This is really difficult to unravel. I think I can't without harming the integrity of the change history.
- [x] I think I am better off asking my brother. If there was an easy option to take it out without harming the change history...
- [x] > Waiting on brother's response. > He's fine with it.
