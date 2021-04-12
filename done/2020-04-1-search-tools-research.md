Encircle Language Spec Plans
============================

Search Tools Research | 2020-04 | Notes
---------------------------------------

### 2020-04-09 Done Explore (Content) Search Options

- [x] Exp: Visual Studio Find in Files
- [x] Obs~ Some paths are too long...
- [x] The file had a path of 260, which I think is the max for Windows 7, but some API's use 255 as a max.
- [x] Exp: Shorten to 255. Find in Files again
- [x] Obs~ Error is gone.
- [x] Exp: Get rid of an intermediate folder to shorten the path and still keep descriptive names.
- [x] Obs~ Visual Studio Find in Files might not search doc contents.
- [x] Hyp:    Windows 7 File Explorer might not find whole words. For some things that's relevant for other things it is not. (I thought I saw it).
- [x] Exp: search "*.doc"
- [x] Obs: Now it does not match "*.docx".
- [x] Hyp: I thought I saw that some times.
- [x] Exp: Windows 7 File Explorer. "D:\Source\JJs Software\Project Docs\Encircle Language Spec Plan". Search "content:Joost".
- [x] Obs~ It shows 2 files, if I open them (docx's) and search for Joost in Microsoft Word, I get no result. Odd.
- [x] Hyp: File properties?