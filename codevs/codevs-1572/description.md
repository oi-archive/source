<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一个不同的值的升序排序数列指的是一个从左到右元素依次增大的序列，例如，一个有序的数列<span style="font-family: Times New Roman;">A,B,C,D </span><span style="">表示</span><span style="font-family: Times New Roman;">A&lt;B,B&lt;C,C&lt;D</span><span style="">。在这道题中，我们将给你一系列形如</span><span style="font-family: Times New Roman;">A&lt;B</span><span style="">的关系，并要求你判断是否能够根据这些关系确定这个数列的顺序。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有两个整数<span style="font-family: Times New Roman;">n,m</span><span style="">，</span><span style="font-family: Times New Roman;">n</span><span style="">表示需要排序的元素数量，</span><span style="font-family: Times New Roman;">2&lt;=n&lt;=26</span><span style="">，第</span><span style="font-family: Times New Roman;">1</span><span style="">到</span><span style="font-family: Times New Roman;">n</span><span style="">个元素将用大写的</span><span style="font-family: Times New Roman;">A,B,C,D....</span><span style="">表示。</span><span style="font-family: Times New Roman;">m</span><span style="">表示将给出的形如</span><span style="font-family: Times New Roman;">A&lt;B</span><span style="">的关系的数量。</span></p>
<p>接下来有<span style="font-family: Times New Roman;">m</span><span style="">行，每行有</span><span style="font-family: Times New Roman;">3</span><span style="">个字符，分别为一个大写字母，一个</span><span style="font-family: Times New Roman;">&lt;</span><span style="">符号，一个大写字母，表示两个元素之间的关系。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">若根据前<span style="font-family: Times New Roman;">x</span><span style="font-family: 宋体;">个关系即可确定这</span><span style="font-family: Times New Roman;">n</span><span style="font-family: 宋体;">个元素的顺序</span><span style="font-family: Times New Roman;">yyy..y</span><span style="font-family: 宋体;">（如</span><span style="font-family: Times New Roman;">ABC</span><span style="font-family: 宋体;">），输出</span></p>
<p class="p0">Sorted&nbsp;sequence&nbsp;determined&nbsp;after&nbsp;xxx&nbsp;relations:&nbsp;yyy...y.&nbsp;</p>
<p class="p0">若根据前<span style="font-family: Times New Roman;">x</span><span style="font-family: 宋体;">个关系即发现存在矛盾（如</span><span style="font-family: Times New Roman;">A&lt;B,B&lt;C,C&lt;A</span><span style="font-family: 宋体;">），输出</span></p>
<p class="p0">Inconsistency&nbsp;found&nbsp;after&nbsp;2&nbsp;relations.</p>
<p class="p0">若根据这<span style="font-family: Times New Roman;">m</span><span style="font-family: 宋体;">个关系无法确定这</span><span style="font-family: Times New Roman;">n</span><span style="font-family: 宋体;">个元素的顺序，输出</span></p>
<p class="p0">Sorted&nbsp;sequence&nbsp;cannot&nbsp;be&nbsp;determined.&nbsp;</p>
<p class="p0">（提示：确定<span style="font-family: Times New Roman;">n</span><span style="font-family: 宋体;">个元素的顺序后即可结束程序，可以不用考虑确定顺序之后出现矛盾的情况）</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1:</p>
<p>4 6</p>
<p>A&lt;B</p>
<p>A&lt;C</p>
<p>B&lt;C</p>
<p>C&lt;D</p>
<p>B&lt;D</p>
<p>A&lt;B</p>
<p> </p>
<p>2:</p>
<p>3 2</p>
<p>A&lt;B</p>
<p>B&lt;A</p>
<p> </p>
<p>3:</p>
<p>26 1</p>
<p>A&lt;Z</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div>
<p>1:</p>
<p>Sorted sequence determined after 4 relations: ABCD.</p>
<p>2:</p>
<p>Inconsistency found after 2 relations.</p>
<p>3:</p>
<p>Sorted sequence cannot be determined.</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>