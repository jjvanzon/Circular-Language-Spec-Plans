Encircle Language Spec Plans
============================

Assignment | Content Changes
----------------------------

__Contents__

- [Postponed](#postponed)
    - [2008-09-29 Postponed](#2008-09-29-postponed)
    - [2020-05-18 Postponed Content Changes for Assignment Article](#2020-05-18-postponed-content-changes-for-assignment-article)
- [Done](#done)
    - [2020-05-18 Done Content Changes for Assignment Article](#2020-05-18-done-content-changes-for-assignment-article)

### Postponed

#### 2008-09-29 Postponed

- [ ] ~ The assignment articles have extra ideas, that have not been worked out. Maybe work those out. That might tidy things up.

#### 2020-05-18 Postponed Content Changes for Assignment Article

- [ ] ~ What about getting the class and assigning it as a class? Would it be strange to call that cross aspect assignment? Maybe mention it. How would it look? I would say explicitly using the system interface? O here it is mentioned: "3. System Command Call Notations" just before the section "Explicit Get & Set Notation". I think it might be worth reconsidering that notation, and mentioning it in the main Assignments article.
- [ ] ~ The implicit notation for cross-aspect assignment might be let go of? Might I just use the system interface notation? Ambiguity seems to arise a bit, for class to object assignment vs 'normal' class assignment (Get Object, Use as Class).
- [ ] ~ Evaluate what the access connector for the Data access would look like compared to an imaginary assignment notation for the Data aspect and if direction indicators seem consistent and intuitive once gotten used to the way described in the Assignment article.

### Done

#### 2020-05-18 Done Content Changes for Assignment Article

- [x] I might want to be ok that changing the notation, I might leave the other documents untouched. In that light, it might be worth mentioning some idea changes, maybe at the bottom, just in case.
- [x] Consider whether to switch the direction sign, so assignment call looks more like the result of the assignment.
- [x] Assignment notation might raises an issue. An assignment almost looks like the result of an assignment, except for a diamond that crosses the line and the direction is flipped. Assignment:

![](images/2019-08%20Circle%20Language%20Spec%20Revamp%20Notes.001.png)

Would result in:

![](images/2019-08%20Circle%20Language%20Spec%20Revamp%20Notes.002.png)

It may be worth to reconsider. Maybe the indicated direction in the assignment notation might be better off being the direction of the result, rather than of the direction of the assignment. But maybe it is not as simple as that.

- [x] Show a value in the object where value assignment is demonstrated?
- [x] How this assignment/result direction flip problem came to be might be that at first there might only have been value assignment notation where it seemed to make sense. Then e.g. object assignment may have been derived from that, which may have introduced this assignment/result direction flip problem. Did I introduce a new problem working backwards? Does assignment notation direction not make sense for the value assignment notation, or is it just something I might be used to? Especially when I replace it with an actual arrow? My attempt here is to introduce more consistency. Formerly I think I tried to introduce intuitiveness over consistency, which might be a contradiction. Consistency might lead to more intuitiveness.
- [x] Consider not making an exception for the value aspect, that the call symbol might not be shown. The main reason that it might still be an idea to not show the diamond in a value assignment, might be because if value correspondence would have a direction, what else could it be but a value assignment. I might just not entirely agree that a value line should always mean assignment, because then you lose something: the possibility to differently express value assignment from value correspondence.
- [x] Perhaps show the result of an assignment next to the assignment call.
- [x] "Because assignments might be so common, they might be given an implicit, simplified notation in Encircle."
- [x] Using the words 'source' and 'target' might not lead to an intuitive story.
- [x] Once I invert the assignment direction notation cross-aspect assignment notation seems to fall apart? > No still has some intuitiveness to it, is my opinion.