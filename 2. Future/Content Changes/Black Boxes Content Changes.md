Encircle Language Spec Plans
============================

Black Boxes | Content Changes
-----------------------------

### Postponed

#### 2020-05-20 Postponed Content Changes for Black Boxes

Black box is a notation I have reservations about. It works, but it might not be not elegant. Also, if you take C# as a source, rules about private/public are set, and some things just don't have to be denoted, because they are implied. A method contained by a a class can access all the other private members of that class. In my efforts to generalize and make things interchangeable, this 'had to be' explicitly denoted...

There are topics, I probably want to move away from the Encircle Language Spec at one point and go for something simpler. The whole friend notation is something I scratch my head about. I am not sure, if I like it or not.  
I am not sure if the topics I dislike can be left in separate articles or something.

- [ ] ~ Obs: One of the first few headings is that 'friends' idea in the 'Black Box Main Concepts' article.
- [ ] ~ I think it might be hard to keep that separated from the rest.
- [ ] ~ Maybe I should forget about trying and go for just longer articles, less articles.
- [ ] ~ 'special reference:
    - [ ] ~ When I think of a reference with a wavy line instead of a straight line, and all I think is 'special reference' then it clicks. I think I can just read the wavy lines then without much problem.
- [ ] ~ I am still quite convinced I might want to introduce some general notation for more conventional member access control situations, perhaps derived from the 'full blown' system and with certain rules just implied, like 'a class's method has access to the private members of the class'.
- [ ] ~ Half-way this one I start finding it difficult: Public & Friend Connections.
- [ ] ~ From there on there are a few parts that I cannot easily read. I am not sure why. I just do not understand some of it, or the notation for some reason starts to become boggling to me, while earlier it was clear. I wonder whether it has anything to do with the way I explained it, or the idea itself is complicated or something. Maybe something in between.
- [ ] ~ I do not worry as much though. I think it is appropriate to introduce a simpler scheme for the most common cases and do that at the beginning. Perhaps saying next, that it is based on a more elaborate notation covered after that, which explicitly denotes things that are just given in certain other languages, or a possibly broader range of access controlling possibilities than offered in other languages.
- [ ] ~ I also feel that there could be more than one way to denote public and private with or without connectors. Not showing connectors at all might denote that something is private. Or not showing the members at all might imply things are private. Or showing a connector with a cross might say 'private', but that would imply the ones without a connector would be public? Is it bothersome to show public access connectors for everything public while all you are showing is the public members? Not sure. Maybe not.
- [ ] ~ Maybe this detail is not even that important if you just present the options and leave the rest up to the imagination. My goal might not be to use this literally as described. I would be glad if anyone would even use bits and pieces, if at all.
- [ ] ~ In the document Encircle Language Spec Strategy one of the 'guidelines' for 'writing efficiently' was to not try to compare it to other systems too much. I am beginning to think that it might be useful to do the opposite when it comes to the Black Box principles. I think a demonstration of common cases in other programming languages might be more useful to start with, and then maybe later go into a systematic approach of maybe a broader view on what access modifiers actually do. That last bit might even be more something for Encircle Construct Drafts, but I am beginning to think, that access modifiers from other programming languages, could be specific cases, of an underlying more general pattern and perhaps richer set of options. Why I now push that in the foreground in my story, is because I possibly would like to base notations of specific cases on this more general underlying pattern. The friend access thing... I might want to demote that to a special case, or specialized idea of special situations that might occur in other languages (friend access modifier in C++) for instance, and the philosophical idea of consequences of drawing a complete parallel between commands and objects. Maybe that idea might even be too alienating for Encircle Language Spec. Maybe Encircle Construct Drafts might be where you want to move that over to. But maybe if you just save it for last, and introduce it as the role I think it could have (not necessarily a big one), it might be OK to leave it in there.
- [ ] ~ It's just that the Black Box story might be the chapter I am least satisfied with. Not sure yet.
- [ ] ~ Note that the Events chapter has an item 'Black Boxed Events' in it.

#### 2010 Unfinished Misc Issues

- [ ] ~ Inclusion
- [ ] ~ Deeper Exclusion
- [ ] ~ Protected
- [ ] ~ Internal
- [ ] ~ Objects Take Over Class Access Control
- [ ] ~ Private Names
- [ ] ~ Black Boxing and User Access Control
- [ ] ~ Programmers and Users
- [ ] ~ Topics in "Black Boxes Unfinished"
