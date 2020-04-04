System Objects Spec Update Ideas
================================
*JJ van Zon, The Netherlands, 2008*

The System Objects article group may need extensions in the future.
It would be revisited to make complete the set of system aspects and system commands and cross out remaining ideas and topics.

Somewhere I wrote down the idea that Getters & Setters should be a sub-topic inside System Objects, but I am not sure why. It seems that is already coverted by the content?


Getters & Setters
-----------------
I have to look over the system objects chapter to see what my ideas about getters and setters were. The idea was that system commands were the replacement for getters and setters. This seems logical, because the system commands are the getters and setters, only they seem to always have the default implementation and if you want to define your own getter and setter code, you would have to define an override or implement the override event or implement the pre- or post-extension events. If you really want it to look like getters and setters, you would just want the property, the object, to have system commands in them, inside of which you see the alternative implementation. That is the solution.

To get a getter and setter experience that is neater than overriding or implementing specialization events, you would want next to the normal representation to see part of the system representation in which the getter and setter system commands are visible, which have a custom implementation.

Problem solved.
