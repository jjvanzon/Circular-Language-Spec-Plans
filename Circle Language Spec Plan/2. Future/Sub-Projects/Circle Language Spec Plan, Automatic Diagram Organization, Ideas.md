Circle Language Spec Plan, Automatic Diagram Organization, Ideas
=========================================
*JJ van Zon, The Netherlands, 2020-04*

Part of it could be documenting ideas about diagram metrics that are only in my head and ones derived from a prototype the of diagram drawing engine I made.

Topics are e.g.:

- Curved lines
- Bundling of lines

An option to ignore fixed logical residence would be welcome.
In that case the fixed logical residence might only be pointed out with an empty reference to the imaginary residence. That way automatic containment will work, but publically-accessible classes are still available with just the namespace qualifier. (-> Lower Contents)

Elements of different assemblies seem to intermix too much and parts of one assembly are shown as an intrinsic part of the an assembly that uses it. Things might be better off as better visible as being externally defined.

It is a problem that everything is displayed as composite aggregation, because in some places it works completely counter-intuitive (where you would expect objects to be sibblings, but they are nested instead?).

The need to display large amounts of items really comes to light now plus that something should be done about it.

Also the need for line bundling starts becoming more apparent.

Diagram Expression Cross Out:
After documenting diagram expression might go through the old Symbol documentation as a cross out list, and delete everything already covered, and to see what topics remain.

Other topics:
* Inward references
* Access marks (when to show them, when not to show them…)
* Lines exiting the diagram
* Fixed Logical Residence (might have a description somewhere?)


Fixed Logical Residence Brainstorm
----------------------------------
*This brainstorm was written in the context of efforts to program a prototype app 'Circle 3'. It might not be very readable.*

Fixed logical residence was supposed to be not thought through enough to be able to make the first version of Circle 3.

< Binding an object to a specific object reference gives an object a fixed logical residence.

What happens to other references, the unqualified references? 
Do they automatically become qualified? Maybe.

If the parent object has a fixed logical residence too, you need a double qualifier to get to the deeper object.

If something has a fixed logical residence, other references will first redirect outward to imaginary references and then redirect inward to the fixed logical residence again. If this inward redirection is out of sight, which it usually is, you have to see an outward directed line with the qualification textually expressed at the outer end of the line.

>

< Do note that fixed logical residence requires qualification, but that does not mean that qualification requires fixed logical residence. You can point to something with a qualifier, even when it does not have its fixed logical residence there. >


Lower Contents Brainstorm
-------------------------
*This brainstorm was written in the context of efforts to program a prototype app 'Circle 3'. It might not be very readable.*

If something is declared on a higher level than it should then it is one real reference there pointing  at an imaginary one at the same level with the contents in it, to which points one other imaginary  reference on a deeper level.
And in that case the contents should be moved from the imaginary reference on the higher level, to  the imaginary reference on the lower level, and the imaginary reference on the lower level should  point to the real reference on the higher level.
That last reference line would be a qualified reference line, but that will not be well visible yet.

To get this right you have to make the process visually debuggable. And while you are at it make processes separately debuggable.
