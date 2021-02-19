Circle Language Spec Plans | System Objects Spec Update Ideas
=============================================================

The System Objects article group may need extensions in the future. It could be revisited to make complete the set of system aspects and system commands and cross out remaining ideas and topics.

Somewhere wrotten down is the idea that Getters & Setters should be a sub-topic inside System Objects, but I am not sure why. It seems that is already covered by the content? Maybe just to compare it to getters and setters and how those look in Circle Language, just in case there was any doubt.


Getters & Setters Brainstorm
----------------------------

The system objects chapter might be looked over to see what the ideas about getters and setters were. The idea seemed that system commands were the replacement for getters and setters. This seems logical, because the system commands are the getters and setters, only they seem to always have the default implementation. If you want to define your own getter and setter code, you might define an override or implement the override event or implement the pre- or post-extension events. If you really want it to look like getters and setters, you might want the property, the object, to have system commands in them, inside of which you see the alternative implementation. That seems the solution.

To get a getter and setter experience, that is neater than overriding or implementing specialization events, you might want next to the normal representation of the object, to see part of the system representation in which the getter and setter system commands are visible, which have a custom implementation.

That seems to solve the problem.
