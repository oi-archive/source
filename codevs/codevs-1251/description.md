<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>计算乘法时，我们可以添加括号，来改变相乘的顺序，比如计算X1, X2, X3, X4, …, XN的积，可以</p>
<p>(X1(X2(X3(X4(...(XN-1*XN)...)))))</p>
<p>:::</p>
<p>:::</p>
<p>(((...(((X1*X2)X3)X4)...)XN-1)XN)</p>
<p>你的任务是编程求出所有这样的添括号的方案。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行是一个数<span style="font-family: 'Times New Roman';">n</span><span style="">（</span><span style="font-family: 'Times New Roman';">1&lt;=n&lt;=10</span><span style="">），表示有</span><span style="font-family: 'Times New Roman';">n</span><span style="">个变量，之后</span><span style="font-family: 'Times New Roman';">N</span><span style="">行每行一个变量的名字。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出所有的添加括号的方案。注意：单个字符不要加括号，两个字符相乘中间要有乘号。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>North </p>
<p>South </p>
<p>East </p>
<p>West</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>(North(South(East*West)))</p>
<p>(North((South*East)West))</p>
<p>((North*South)(East*West))</p>
<p>((North(South*East))West)</p>
<p>(((North*South)East)West)</p>

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