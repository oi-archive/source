<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">（经典问题系列第二题）</span></p><p><em>sqrt_-1</em> 最爱玩一种益智游戏，不知道你爱不爱玩？</p><p>游戏可以描述为一个 <em>n</em> * <em>m</em> 的城堡群，初始时防御力皆为 0。每张经验卡可以选择一行或一列，这一行或列的每个城堡防御力可以增加 1。如果达到指定的状态，就可以获得奖励。</p><p>请你编程帮助他算算，他能否赢得奖励，如果能赢得，最少要几张经验卡？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为两个数 <em>n</em> 和 <em>m</em>，表示矩形房屋的行和列。</p><p>接下来 <em>n</em> 行，每行有 <em>m</em> 个数，表示目标状态的值。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>如果他不能赢得奖励，就输出 -1。<br/></p><p>否则，第一行输出最少使用的经验卡数目，然后分别列出。（见样例）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>input 1：</p><pre style="">3 5
2 2 2 3 2
0 0 0 1 0
1 1 1 2 1</pre><p>input 2：</p><pre style="">3 3
0 0 0
0 1 0
0 0 0</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>output 1：</p><pre style="">4
row 1
row 1
col 4
row 3</pre><p>output 2：</p><pre style="">-1</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据范围：</p><p style=""><span style="font-family: Merriweather, serif;">1 ≤ </span><em>n</em><span style="font-family: Merriweather, serif;">, </span><em>m<span style="font-family: Merriweather, serif;"> ≤ 20</span></em><span style="font-family: Merriweather, serif;">，目标状态的每个数不超过 500。</span></p>
</div>
</div>