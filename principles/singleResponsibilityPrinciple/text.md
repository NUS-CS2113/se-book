<div id="title">

#### Single Responsibility Principle

</div>

<span id="prereqs"></span>

<span id="outcomes">{{glyphicon_flag}} Can explain single responsibility principle</span>

<div id="body">

<tip-box type="primary">

<include src="../../common/definitions.md#def-single-responsibility-principle" />

</tip-box>

If a class has only one responsibility, it needs to change only when there is a change to that responsibility.

<tip-box>

{{ icon_example }} Consider a `TextUi` class that does parsing of the user commands as well as interacting with the user. That class needs to change when the formatting of the UI changes as well as when the syntax of the user command changes. Hence, such a class does not follow the SRP.

</tip-box>

</div>

<div id="extras">

<include src="resources.md" />

</div>