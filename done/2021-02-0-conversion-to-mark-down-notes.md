Encircle Language Spec Plans
============================

Conversion to MarkDown | 2021-02 | Notes
-----------------------------------------

Converting Word documents to MarkDown.

__Contents__

- [Information](#information)
- [Done](#done)
    - [2021-02-09 Done MarkDown](#2021-02-09-done-markdown)
    - [2021-02-10 Image did not show in rendered MarkDown on GitHub](#2021-02-10-image-did-not-show-in-rendered-markdown-on-github)
    - [2020-04-19 Done Brainstorm Conversion to MD](#2020-04-19-done-brainstorm-conversion-to-md)

### Information

- For converting to Markdown:
    - Pandoc output markup seemed 'scrambly': <https://pandoc.org/index.html>
    - Aspose seems good: <https://products.aspose.app/words/conversion/word-to-md> 
    - <https://word2md.com> 

### Done

#### 2021-02-09 Done MarkDown

- [x] Trying MarkDown with images.
    - [x] URL's seem case sensitive on GitHub.
- [x] Converting things to MarkDown
- [x] Aspose seems good: (https://products.aspose.app/words/conversion/word-to-md)
- [x] Considering a phased bulk approach (for quicker results)
- [x] Converting
- [x] Unzipping
- [x] Committing
- [x] Moving images to sub-folder
- [x] Changing image markup to point at sub-folder
- [x] Prettifying headings serially: until "3. Creation Behavior Of Commands.md"
- [x] Switching to a phased bulk approach
- [x] Heading 1 double underline
- [x] Heading 2 single underline, 2 empty lines above, 1 below
- [X] Headings 3 and up: surround with enters (using find "##")
- [x] Headings 3 and up: removing bold/italic start tokens (using search and replace "## *" => "## ")
- [x] Headings 3 and up: removing ending tokens of bolds/italics (using find "##")
- [x] Replacing bold ** with __
- [x] Checking the italics (*)
- [x] Checking the bolds (__)
- [x] Prettifying bulleted lists
- [x] Removing excessive empty lines
- [x] Prettifying code blocks
- [x] Black backgrounds in "Broader View" and "Construct Drafts"
- [x] Prettifying tables
- [x] Try correcting < and > interpretation as XML/HTML by surrounding them with spaces
- [x] Correcting arrows replacing à and ß with `=>` or `<=`
- [x] Checking the headings.
- [x] Did these in one blow until "4. Command Redirection":
    - [x] Checking the pictures
          (words that may express things too strongly).  
          (Used red in Word. Using `inline code` in MarkDown.)
    - [x] Manually checking differences between rendered MarkDown and Word document.
    - [x] Last check if markup looks ok
    - [x] Removing Word documents
- [x] Switching to a more phased approach
- [x] Checking the pictures
- [x] Copying red markings of 'trigger words' 
      (words that may express things too strongly).  
      (Used red in Word. Using `inline code` in MarkDown.)
- [x] Limitation: Not coming up with new header texts
- [x] Limitation: Not solving errors in previous work.
- [x] Checking the markup for obvious improvements.
- [x] Manually checking differences between rendered MarkDown and Word document.
- [x] Last checks if markup looks ok.
- [x] Removing Word documents.
- [x] Making version history document titles more consistent.

#### 2021-02-10 Image did not show in rendered MarkDown on GitHub

- Image might not show in rendered MarkDown on GitHub.
- MarkDown: `![Image in Sub Folder](images/ImageInSubFolder2.jpg)`
- Folder itself is "Images" (starts with upper case letter).
- Resolved URL has "images" (starts with lower case letter): `https://github.com/jjvanzon/JJ.Demos.MarkDownTest/blob/master/Sub-Folder%20with%20MD's/images/ImageInSubFolder2.jpg`
- Changing resolved URL's "images" to "Images" leads to the (not raw) image page.
-----
- Exp: Changing image reference to starting with capital letter.
- Image might show in rendered MarkDown on GitHub.
- MarkDown: `![Image in Sub Folder](Images/ImageInSubFolder2.jpg)`
-----
- Hyp: precise casing matters in image URL's.
- Exp: I might stick to URL-friendlier notation: lower case letters, dashes between words.

#### 2020-04-19 Done Brainstorm Conversion to MD

- [x] I thought MD might be the way to go with this project compared to docx. But I have doubts if MD is the better way to go. I keep getting stressed out about those doubts. It makes my decisions on what to do with the documents (formatting) harder, because I just am so unsure about this. What I might like is to have a good MD editor. I just hope some of the difficulties editing MD compared to docx can be taken away by a good tool. Also: I think MD might be viewable and better indexable on the internet, but I have not really thoroughly seen that confirmed. The main problems with MD editing I have is navigating around headings and sections and viewing the outcome of my formattings better as I type the MD in. The doubts about indexing: I know GitHub can show the MD in nice formatting, but might a lot of MD's actually be nicely navigatable? Might those MD's actually be indexed, or might that only count for e.g. the `README.MD` in the root dir of a git repository? another doubt about MD is: can I be satisfied with some of the tools that convert docx to MD? Might that all be doable? It's so many articles. Can I do it in bulk? Might I merge more articles into one making converting one by one by hand better. How might it work with links but especially with images? All those doubts made me postpone decisions about converting things to MD, but that makes me burdened with formatting docx's making them look nice, which is not that useful if I am going to convert all of that to MD anyway. That last argument might not seem very strong to me. If I know that MD indexes well, that might already make some decisions to go for MD easier, when I decide e.g. about small documents.
- [x] So with all those doubts, I want to explore MD options a little.
- [x] Main points:
    - [x] MD editor
    - [x] Might MD show and index better on the internet?
- [x] Notes:
    - [x] Trying to research this puts a strain on me.
    - [x] I found out relative links to images work nicely in MD on github.
    - [x] I cannot find if Google might index the content well.
    - [x] I do know that clicking an MD in GitHub leads to nicely readable page. That's something you cannot say about docx's.
    - [x] That last point may actually convince me already to make MD's more often.
- [x] MD editors:
    - [x] Visual Studio code has a preview view and outline view: <https://code.visualstudio.com/Docs/languages/markdown> 
    - [x] <https://duckduckgo.com/?q=MD+editor&t=opera&ia=web>
    - [x] <https://marketplace.visualstudio.com/items?itemName=MadsKristensen.MarkdownEditor>
    - [x] There seem to be options.
- [x] Alternative: Convert the Future Sub-Project Summaries to MD.
    - [x] Pro: Those future docs are short and don't need much formatting.
    - [x] ~~Con: MD is harder to edit (?) > Needs research.~~
    - [x] Pro: MD is more accessible on the internet (?) > Needs test.
    - [x] I might like to have the arguments for and against better proven.
    - [x] But it is also not directly my goal right now.
    - [x] It might help me to know if MD really has those advantages. Otherwise I might keep being confused about whether or not I should convert to MD.
    - [x] But pragmatically: That was not what I was doing. It was formatting the docx's, what I was doing. But pragmatism is sometimes something I feel others have determined for me. Maybe knowing something for sure is more pragmatic for me, because the doubt causes me so much stress.
- [x] Concession: Do both. First format the 4 remaining Summary's. Then research MD more.
- [x] Conversion programs:
    - [x] ~~Pandoc: I did not like it. It was expecting a user interface, but I got a command line interface. Also, the output from docx to MD is not what I expected. I got quote markup > for just indentation and a dashed bulleted list got the dashes escaped or something. The check list style for GitHub that's kind a sorta already MD format, got escaped it seemed. I get not everything is unambiguously translatable, but this was too far removed of what I might type in myself. So sorry, pandoc. Moving on.~~
    - [x] ~~I might as well just copy paste to a text document and then do it myself.~~
    - [x] But I am going into research again, and that is not what I want to deeply into. I do not have the energy.
    - [x] Online Aspose conversion tool worked ok. I did spend a while dotting the i's though, metaphorically.

