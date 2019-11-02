<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>老师在开学第一天就把所有作业都布置了，每个作业如果在规定的时间内交上来的话才有学分。每个作业的截止日期和学分可能是不同的。例如如果一个作业学分为10，要求在6天内交，那么要想拿到这10学分，就必须在第6天结束前交。<br>每个作业的完成时间都是只有一天。例如，假设有7次作业的学分和完成时间如下：<br>作业号 1 2 3 4 5 6 7 <br>期限 1 1 3 3 2 2 6 <br>学分 6 7 2 1 4 5 1 <br>最多可以获得15学分，其中一个完成作业的次序为2，6，3，1，7，5，4，注意可能还有其他方法。<br>你的任务就是找到一个完成作业的顺序获得最大学分。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数N，表示作业的数量。接下来N行，每行包括两个整数，第一个整数表示作业的完成期限，第二个数表示该作业的学分。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个整数表示可以获得的最大学分。保证答案不超过longint范围。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7<br>1 6<br>1 7<br>3 2<br>3 1<br>2 4<br>2 5<br>6 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>15</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据规模：<br>对于所有数据，N&lt;=1000000，作业的完成期限均小于700000。<br>对于部分数据，N&lt;=1000；<br>对于部分数据，N&lt;=10000；<br>对于部分数据，N&lt;=100000；<br>对于部分数据，作业的完成期限小于100；<br>对于部分数据，作业的完成期限小于1000；</p>
</div>
</div>