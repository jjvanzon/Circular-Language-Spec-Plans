Encircle Language Spec Plans | Construct Drafts
===============================================

Input Output | Language Design | Plan
-------------------------------------

*December, 2008*

### Goal

Work out the Input Output article group.

This may include an exact specification of the terms input and output. This might lead to the definition of how automatic execution order might be established. Also, there may be looked at, to which extent this might help solve concurrency issues.

### Product List

These may once correspond to articles or sub-sections of documentation.

- [ ] In, Out & Thru
- [ ] Input Output Parameter Passing
        *(Parameter passing types from other languages and from a previous attempt to document this language (the 'Symbol Language' documentation) but now put in the context of in/out/thru and input/output in general and extending to automatic execution order and some form of concurrency resolution).*
    - [ ] Parameters
    - [ ] Parameter Types
    - [ ] In Parameter
    - [ ] Out Parameter
    - [ ] Thru Parameter
    - [ ] By Value
    - [ ] By Reference
    - [ ] Value In
    - [ ] Value Out
    - [ ] Value Thru
    - [ ] Reference In
    - [ ] Reference Out
    - [ ] Reference Thru
    - [ ] Object Out
    - [ ] New Object Out
    - [ ] Existing Object Out
    - [ ] Three Parameter Passing Elements
    - [ ] Parameters of Calls Directly Tied Together
    - [ ] Strict about Parameter Passings
    - [ ] The Class of a Parameter
    - [ ] Sub-Commands are Never Output Objects
    - [ ] In, Out, Thru Parameters
    - [ ] Downput Parameter
    - [ ] Indirect Value Transmission
    - [ ] Data Direction
- [ ] Thruput Parameters | Affected, Used and Transformed
- [ ] Auto-Determine In, Out & Thru
- [ ] Automatic Execution Order
    - [ ] There may be an article about this where the sub-topics below may also be tucked away. 
    -----
    - [ ] Parameters of Calls Directly Tied Together
    - [ ] Parameters Tied Together
    - [ ] Parameters Tied to Objects
    - [ ] Outcome Dependency
    - [ ] Accessing Parameters’ Sub-Objects
    - [ ] Specific Data Unknown
    - [ ] Parameters & Input/Output
    - [ ] Compared Input/Output
- [ ] Sub-Commands’ Input/Output
- [ ] Command Input/Output
- [ ] Compared Input/Output
- [ ] Outcome Dependency
- [ ] Pre- & Post-Conditions
- [ ] Conditions
- [ ] User Commands
    - \> If executions are only executed by parent executions, then what is the parent execution of the parent execution of the parent execution? Well, the upper parent command is actually comes from a human being. A person can execute a command definition.
- [ ] Commands & Classes Loosely Coupled
- [ ] Input/Output not Always Values
- [ ] Scheduling & Waiting

### Brainstorm

At one point I realized that Parameters (that may be either in/out or thru) might not be what determines input output. I started to suspected input/output just would mean anything read vs anything written. Parameters can be part of that, but internally a procedure may as well write other stuff (e.g. to a data source). But that does not mean it would not be useful if the concept of input/output is also reflected onto parameters, because they often do have a lot to do with it. Also, functions that only read and write parameters, not read anything else, I think those are called pure functions or sometimes functions with no side-effects/ It's an existing concept. But were I to explain (to myself) how that compares to my ideas about Input/Output, I expose it in a theoretical framework how everything compares to each other, might help me. For instance, some parameters can be called input or output parameters. To realize that the parameters are potentially not the only input/output that a procedure has, would disentangle those concepts. Also: if you pass a reference to an object to a procedure, is it input or output? That question used to confuse me. But now I realize it can be both. Just look at the elements written and then elements read: those are the input and the output. So from the viewpoint of a command, the reference is input. If it uses that object reference to e.g. write properties, that is its output. What is also interesting, is something written by one procedure can be read by another, so whether something is input or output is also dependent on context. E.g. the object reference parameters: it is sort of output when a procedure caller writes the reference, I mean if you uphold the definition of output = writing, then it must be. But to the called procedure it is input, so the same piece of information switches role there, just because in that context it is only read, not written. The whole thing can be so confusing and intermixed in my view, that I think I found it a useful idea to maybe write about how all the concepts would work together precisely. To explain it to myself, maybe eventually useful for others too.