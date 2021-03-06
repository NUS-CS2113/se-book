<div id="title">

#### Activity Diagrams

</div>

<span id="prereqs"></span>

<span id="outcomes">{{glyphicon_flag}} Can use activity diagrams</span>

<div id="body">

**Software projects often involve _workflows_.** Workflows define the <tooltip content="a connected sequence of steps"></tooltip>flow in which a process or a set of tasks is executed.

<tip-box> 

Some examples in which a certain workflow is relevant to software project:

{{ icon_example }} A software that automates the work of an insurance company needs to take into account the workflow of processing an insurance claim.

{{ icon_example }} The algorithm of a price of code represents the workflow (i.e. the execution flow) of the code.

</tip-box>

Understanding such workflows is important for the success of the software project. **<trigger trigger="click" for="modal:modelingAd-uml">UML</trigger> _&nbsp;activity diagrams_ (AD) can model workflows.&nbsp;** %%_Flow charts_ is another type of diagrams that can model workflows. Activity diagrams are the UML equivalent of flow charts.%%

<modal title="**Unified Modeling Language (UML)**" id="modal:modelingAd-uml">
  <include src="../../../common/definitions.md#def-uml" />
</modal>

<tip-box> 

{{ icon_example }} An example activity diagram <sub>[[source:wikipeida](https://en.wikipedia.org/wiki/Activity_diagram)]</sub>:

<img src="https://upload.wikimedia.org/wikipedia/commons/e/e7/Activity_conducting.svg" width="430">

</tip-box>

The most basic activity diagram is simply a linear sequence of actions.

<panel src="../../../uml/activityDiagrams/basicNotations/linearPaths/unit-inElsewhere-asFlat.md" boilerplate header="{{ icon_prereq }} UML → Activity Diagrams → Basic Notations → Linear Paths" expanded />

Some workflows have alternate paths where only one of the alternate paths is taken based on some condition.

<panel src="../../../uml/activityDiagrams/basicNotations/alternatePaths/unit-inElsewhere-asFlat.md" boilerplate header="{{ icon_prereq }} UML → Activity Diagrams → Basic Notations → Alternative Paths" expanded />

In some workflows, multiple paths happen in parallel. 

<panel src="../../../uml/activityDiagrams/basicNotations/parallelPaths/unit-inElsewhere-asFlat.md" boilerplate header="{{ icon_prereq }} UML → Activity Diagrams → Basic Notations → Parallel Paths" expanded />

</div>

<div id="extras">
  <include src="exercises.md" />
</div>