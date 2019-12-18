<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一个 n × m 的矩形表格，其中有一些位置有障碍。现在要在这个表格内放一些 1 × 2 或者 2 × 1 的多米诺骨牌，使得任何两个多米诺骨牌没有重叠部分，任何一个骨牌不能放到障碍上。并且满足任何相邻两行之间都有至少一个骨牌横跨，任何相邻两列之间也都至少有一个骨牌横跨。求有多少种不同的放置方法，注意你并不需要放满所有没有障碍的格子。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数 n;m。接下来 n 行，每行 m 个字符，表示这个矩形表格。<br>其中字符 “x” 表示这个位置有障碍，字符 “.” 表示没有障碍。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行一个整数，表示不同的放置方法数 mod 19901013 的值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3<br>...<br>...<br>...</p>

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

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 40% 的数据，满足 1 ≤ n;m ≤ 8。<br>对于 90% 的数据，满足 1 ≤ n;m ≤ 14。<br>对于 100% 的数据，满足 1 ≤ n;m ≤ 15。</p>
</div>
</div>