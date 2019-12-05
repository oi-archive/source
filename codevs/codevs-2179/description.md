<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>题目很简单，给出N个数字，不改变它们的相对位置，在中间加入K个乘号和N-K-1个加号，（括号随便加）使最终结果尽量大。因为乘号和加号一共就是N-1个了，所以恰好每两个相邻数字之间都有一个符号。例如：<br>N=5, K=2，5个数字分别为1、2、3、4、5，可以加成：<br>1*2*(3+4+5)=24<br>1*(2+3)*(4+5)=45<br>(1*2+3)*(4+5)=45<br>……</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件共有二行，第一行为两个有空格隔开的整数，表示N和K，其中(2&lt;=N&lt;=15, 0&lt;=K&lt;=N-1)。第二行为 N个用空格隔开的数字（每个数字在0到9之间）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件仅一行包含一个整数，表示要求的最大的结果<br />最后的结果&lt;=maxlongint</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 2<br>1 2 3 4 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>120</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，N&lt;= 10；<br>对于全部的数据，N &lt;= 100。</p>
</div>
</div>