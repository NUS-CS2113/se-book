<panel header="{{ icon_Q_A }} Suitable as class-level variables">

Which of these are suitable as class-level variables?

- [ ] a. system: multi-player Pac Man game, Class: `Player`,  variable: `totalScore`
- [ ] b. system: eLearning system, class: `Course`, variable: `totalStudents`
- [ ] c. system: ToDo manager, class: `Task`, variable: `totalPendingTasks`
- [ ] d. system: any, class: `ArrayList`, variable: `total` (i.e., total items in a given `ArrayList` object)


<panel type="seamless" header="{{ icon_A }} Answer" minimized>

(c)

Explanation: `totalPendingTasks` should not be managed by individual `Task` objects and is therefore suitable to be maintained as a class-level variable. The other variables should be managed at instance level as their value varies from instance to instance. e.g., `totalStudents` for one `Course` object will differ from `totalStudents` of another.

</panel>
</panel>
