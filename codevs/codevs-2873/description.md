<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>      在2012年的夏天，有四个队伍参加ACM的暑期培训，时间为n天。四个队伍的名字分别为Akiba, BiliBili, CIA, Double(标为队伍A, B, C, D).，每天有一支队伍负责出题。作为培训班的老师，你可以决定每天由那支队伍出题。但是有一些事项要注意：</p>
<p>      1.没有队伍能够连续两天出题</p>
<p>      2.在培训的其中m天中，负责出题的队伍事先已经确定（例如：Akiba负责出第1天的题，BiliBili负责出第6天的题，这两天的出题队伍就不能再被改变）</p>
<p>      一共有多少种安排方案？输出结果（结果要对1000000007求余）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数n，m (1 ≤ <em>n</em> ≤ 10000000, 0 ≤ <em>m</em> ≤ 10),n表示暑期培训的天数，m表示已经安排好的天数。接下来的m行表示对应天负责出题的队伍</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>所有的方案数（结果要对1000000007求余）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 2</p>
<p>1 A</p>
<p>3 C</p>
<p> </p>
<p>2 1</p>
<p>1 D</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>例子 1:</p>
<p>2种方案: ABC, ADC.</p>
<p>例子 2:</p>
<p>3 种方案: DA, DB, DC.</p>
</div>
</div>