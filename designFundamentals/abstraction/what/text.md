<div id="title">

#### What

</div>

<span id="prereqs"></span>

<span id="outcomes">{{glyphicon_flag}} Can explain abstraction</span>

<div id="body">

<tip-box type="definition">
<include src="../../../common/definitions.md#def-abstraction" />
</tip-box>

Most programs are written to solve complex problems involving large amounts of intricate details. It is impossible to deal with all these details at the same time.  The guiding principle of abstraction stipulates that we capture only details that are relevant to the current perspective or the task at hand. 

**Ignoring lower level data items and thinking in terms of bigger entities is called _data abstraction_.**

<tip-box> 

{{ icon_example }} Within a certain software component, we might deal with a _user_ data type, while ignoring the details contained in the user data item such as _name_, and _date of birth_. These details have been ‘abstracted away’ as they do not affect the task of that software component.

</tip-box>

**_Control abstraction_ abstracts away details of the actual control flow to focus on tasks at a simplified level.**
 
<tip-box> 

{{ icon_example }} `print(“Hello”)` is an abstraction of the actual output mechanism within the computer.

</tip-box> 

**Abstraction can be applied repeatedly to obtain progressively _higher levels of abstractions_.** 

<tip-box> 

{{ icon_example }} An example of different levels of data abstraction: a `File` is a data item that is at a higher level than an array and an array is at a higher level than a bit. 

{{ icon_example }} An example of different levels of control abstraction: `execute(Game)` is at a higher level than `print(Char)` which is at a higher than an Assembly language instruction `MOV`.

</tip-box>

</div>

<div id="extras">
</div>