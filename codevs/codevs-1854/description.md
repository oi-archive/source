<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Y901高速公路是一条重要的交通纽带，政府部门建设初期的投入以及使用期间的养护费用都不低，因此政府在这条高速公路上设立了许多收费站。</p>
<p>Y901高速公路是一条由N-1段路以及N个收费站组成的东西向的链，我们按照由西向东的顺序将收费站依次编号为1~N，从收费站i行驶到i+1(或从i+1行驶到i)需要收取Vi的费用。高速路刚建成时所有的路段都是免费的。</p>
<p>政府部门根据实际情况，会不定期地对连续路段的收费标准进行调整，根据政策涨价或降价。</p>
<p>无聊的小A同学总喜欢研究一些稀奇古怪的问题，他开车在这条高速路上行驶时想到了这样一个问题:对于给定的l,r(l&lt;r),在第l个到第r个收费站里等概率随机取出两个不同的收费站a和b，那么从a行驶到b将期望花费多少费用呢?</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行2个正整数N,M，表示有N个收费站，M次调整或询问</p>
<p>接下来M行，每行将出现以下两种形式中的一种</p>
<p>C l r v 表示将第l个收费站到第r个收费站之间的所有道路的通行费全部增加v</p>
<p>Q l r   表示对于给定的l,r，要求回答小A的问题</p>
<p>所有C与Q操作中保证1&lt;=l&lt;r&lt;=N</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每次询问操作回答一行，输出一个既约分数</p>
<p>若答案为整数a，输出a/1</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre><span>4 5</span></pre>
<pre><span>C 1 4 2</span></pre>
<pre><span>C 1 2 -1</span></pre>
<pre><span>Q 1 2</span></pre>
<pre><span>Q 2 4</span></pre>
<pre><span>Q 1 4</span></pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1/1</p>
<p>8/3</p>
<p>17/6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>所有C操作中的v的绝对值不超过10000<strong></strong></p>
<p>在任何时刻任意道路的费用均为不超过10000的非负整数</p>
<p>所有测试点的详细情况如下表所示</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="43">
<p>Test</p>
</td>
<td valign="top" width="63">
<p>N</p>
</td>
<td valign="top" width="69">
<p>M</p>
</td>
</tr>
<tr>
<td valign="top" width="43">
<p>1</p>
</td>
<td valign="top" width="63">
<p>=10</p>
</td>
<td valign="top" width="69">
<p>=10</p>
</td>
</tr>
<tr>
<td valign="top" width="43">
<p>2</p>
</td>
<td valign="top" width="63">
<p>=100</p>
</td>
<td valign="top" width="69">
<p>=100</p>
</td>
</tr>
<tr>
<td valign="top" width="43">
<p>3</p>
</td>
<td valign="top" width="63">
<p>=1000</p>
</td>
<td valign="top" width="69">
<p>=1000</p>
</td>
</tr>
<tr>
<td valign="top" width="43">
<p>4</p>
</td>
<td valign="top" width="63">
<p>=10000</p>
</td>
<td valign="top" width="69">
<p>=10000</p>
</td>
</tr>
<tr>
<td valign="top" width="43">
<p>5</p>
</td>
<td valign="top" width="63">
<p>=50000</p>
</td>
<td valign="top" width="69">
<p>=50000</p>
</td>
</tr>
<tr>
<td valign="top" width="43">
<p>6</p>
</td>
<td valign="top" width="63">
<p>=60000</p>
</td>
<td valign="top" width="69">
<p>=60000</p>
</td>
</tr>
<tr>
<td valign="top" width="43">
<p>7</p>
</td>
<td valign="top" width="63">
<p>=70000</p>
</td>
<td valign="top" width="69">
<p>=70000</p>
</td>
</tr>
<tr>
<td valign="top" width="43">
<p>8</p>
</td>
<td valign="top" width="63">
<p>=80000</p>
</td>
<td valign="top" width="69">
<p>=80000</p>
</td>
</tr>
<tr>
<td valign="top" width="43">
<p>9</p>
</td>
<td valign="top" width="63">
<p>=90000</p>
</td>
<td valign="top" width="69">
<p>=90000</p>
</td>
</tr>
<tr>
<td valign="top" width="43">
<p>10</p>
</td>
<td valign="top" width="63">
<p>=100000</p>
</td>
<td valign="top" width="69">
<p>=100000</p>
</td>
</tr>
</tbody>
</table>
</div>
</div>