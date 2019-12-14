<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Lamps-O-Matic公司装修很大的吊灯。吊灯由几层组成。（从下至上）第一层的水晶灯直接挂在环上。把环集起来以后再挂到上一层的环上面，依此类推。最后一层是一个挂满了灯和小环的大环（废话）。</p>
<p>现在由机器人来做挂灯的事。机器人身上有资源补给，挂灯的时候，它使用一个栈来存储灯和环。一开始，这个栈是空的。机器人执行一个指令集来运作。这个指令集是一个字符串。</p>
<p>举例说明：aaaaa3aaa2aaa45。a代表将小灯放入栈中。数字N代表将目前栈顶向下的N个资源取出，组成一个环，然后放回栈顶。整个栈的流程如下。</p>
<p>aaaaa→aa[aaa]→aa[aaa]aaa→aa[aaa]a[aa]→aa[aaa]a[aa]aaa→aa[aaa]a[[aa]aaa]→END</p>
<p>这样就需要栈空间的最大值为8，当其状态为aa[aaa]a[aa]aaa时就需要，注意：环和灯都算一个。</p>
<p>然而还有一个问题。机器人的栈不够大了（真是次品）。所以需要你编一个指令，使吊灯的设计不变，让指令所需的栈空间越小越好。所谓的设计不变，就是指：假设在同一层环原来有4个部件：i1，i2，i3，i4，现在可以改成i4，i3，i1，i2或是其他排列，但是不能有部件增加或者减少。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件每一行一个字符串，代表指令。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件为包含一行，代表需要的栈空间</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>aaaaa3aaa2aaa45</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>100%的数据字符串长度≤104</p>
</div>
</div>