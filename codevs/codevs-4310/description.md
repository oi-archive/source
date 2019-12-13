<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>现在要把m本有顺序的书分给k个人复制(抄写),每一个人的抄写速度都一样,一本书不允许给两个(或以上)的人抄写,分给每一个人的书,必须是连续的,比如不能把第一、第三和第四本书给同一个人抄写。</p><p>现在请你设计一种方案,使得复制时间最短。复制时间为抄写页数最多的人用去的时间。<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数m,k;(k≤m≤500)，     <br></p><p>第二行m个整数,第i个整数表示第i本书的页数。  </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共k行,每行两个整数,第i行表示第i个人抄写的书的起始编号和终止编号。k行的起始编号应该从小到大排列,如果有多解,则尽可能让前面的人少抄写。<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>9  3</p><p>1  2  3  4  5  6  7  8  9<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 5</p><p>6 7</p><p>8 9<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>k≤m≤500<br></p>
</div>
</div>