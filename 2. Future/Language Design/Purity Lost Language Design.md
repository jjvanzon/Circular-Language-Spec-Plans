Encircle Language Spec Plans
============================

Purity Lost? | Language Design
------------------------------

*Has the language lost its purity with implicit notations?*

### 2019-12-29 Postponed Purity Lost?

- [ ] ~ I think that somewhere along the way, the language lost its purity. Hypothetically, I may have gotten carried away a few times. For instance, using the dashed line as a conceptual expression of the idea of 'classes' or 'types': I think I tend to introduce ideas about notations that might simplify things visually, but possibly introducing ambiguity. At first, the language was an attempt at the purest form that I could find, in which you could draw out an object oriented system with shapes and lines. What happened to that as I started to make, drawing something with dashed lines, something ambiguous? I am not sure: this might be a non-issue. But maybe I want to be wary of where I got carried away and not think in definites about the final form of the language. This also counts for e.g. System Command Call with Argument Notation: I introduce simplified, yet abused slightly ambiguous notation for something you probably will never see used. What if at some point I find use case for this simplified notation that also looks like something it's not? E.g. a call to an object getter:

![](images/2019-08%20Circle%20Language%20Spec%20Revamp%20Notes.003.png)

- [ ] ~ It's ambiguous, because it looks like the diamond, which is a command call to the getter, is a reference to the object. It reference-associates a command call and an object, which are two separate 'objects', but connecting them with solid lines would suggest they are the same object.
- [ ] ~ Maybe expressing doubt about it at the beginning is just as far as the solution might go.
- [ ] ~ The protected access mark / access modifier:

![](images/2019-08%20Circle%20Language%20Spec%20Revamp%20Notes.004.png)

I thought of this relatively early. To solve ambiguity problems, I introduced notations such as: a system command connector for the New command:

![](images/2019-08%20Circle%20Language%20Spec%20Revamp%20Notes.005.png)

Event connector:

![](images/2019-08%20Circle%20Language%20Spec%20Revamp%20Notes.006.png)

The concepts of its being *required* for a command to be executed:

![](images/2019-08%20Circle%20Language%20Spec%20Revamp%20Notes.007.png)

But the latter notations are there kind of because the simpler notation was already in use by the concept of the protected access modifier.  
I am having second thoughts about this. Maybe I would like to consider using a different symbol for Protected, so that these connectors, events and optional/required can get a less contrived notation.  
Another example where it is an issue: This expresses that the other end of the connection should be a triangle:

![](images/2019-08%20Circle%20Language%20Spec%20Revamp%20Notes.008.png)

But if you would accidentally bend the half triangle at the end the wrong way, it would look like a protected access modifier. Well... maybe that is not definitive proof that there's an issue, but it's an indication of something might be confusing.

- [ ] ~ A jagged line type for the Name aspect I would like.
- [ ] ~ Maybe choices for shapes with different line types could become less iffy. (See Basic Diagram Elements.)
- [ ] ~ Maybe less rules for line direction, even though an effort for this may already have been done in moving from the previous version Symbol Language.doc to the newer definition Encircle Language Spec.
- [ ] ~ The access marks may become arrows instead, after considering if that works out with the rest of the notation rules.
- [ ] ~ Maybe accept that the system interface may be visible more, while letting go of implicit notations to avoid them. Maybe not all the implicit notations for e.g. system commands calls would be scratched. Maybe the less usual ones, that seem to look the most ambiguous of all, if I may express it that black and white.
- [ ] ~ The line merge and symbol merge notations may be let go of. (See Basic Diagram Elements.) But maybe later it was let go of already, I cannot remember that clearly anymore. Those notations look quite ambiguous with more basic notation ideas. I think I introduced those, because my idea was to make bidirectional relationships more common, and I perhaps disliked how many symbols and lines you might use to express bidirectional relationships, because in my view they would be used everywhere. I let go of that idea of bidirectional relationships everywhere. Only in use case ideas I might have for aspect oriented programming ideas it may become handy. In general it may be handy: bidirectional relationships, but they do not seem to be used ubiquitously in technology, so... So long story, but just leaving the explicit 'forward' and 'backward' relationship references drawn out explicitly, might be a good idea. And I believe that I already came up with something somewhere, where I put a 'relational ring' around the two lines of a bidirectional relationship, to indicate they would be kept in sync automatically.
- 'Modifiers' (from C#) like protected, internal, static might be represented simpler by using 'condition' notation, by drawing through an connector line (or connection line too?) a triangle (for protected), a pentagon (for internal) and a dashed circle (for static)? Perhaps other modifiers too. This might prevent difficult theory of other more exact(?) (-ish) representations of the concepts.