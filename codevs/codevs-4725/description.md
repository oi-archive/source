<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 'microsoft yahei';">已知有n个元素,将要分成若干组,每组由一些连续的元素组成.</span><br></p><p><span style="font-family: 'microsoft yahei';">每个元素存在一个约束条件,需要满足它所在的元素组中元素数目大于等于c[i],小于等于d[i].<br>求在满足所有约束条件的情况下最多能够分成多少组(分组数量的最大值),及存在多少种方案能够使得分组数量达到最大.</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'microsoft yahei';">第一行一个正整数n,表示元素数目.</span></p><p><span style="font-family: microsoft yahei;"><span style="">接下来n行,每行两个数c[i],d[i]为约束条件中的最小值和最大值.</span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: &#39;microsoft yahei&#39;; font-size: 14px; line-height: 26px; background-color: rgb(255, 255, 255);">如果不存在同时满足所有约束条件的方案,仅输出一行NIE.&nbsp;</span><br style="box-sizing: border-box; font-family: &#39;microsoft yahei&#39;; font-size: 14px; line-height: 26px; white-space: normal; background-color: rgb(255, 255, 255);"/><span style="font-family: &#39;microsoft yahei&#39;; font-size: 14px; line-height: 26px; background-color: rgb(255, 255, 255);">否则两个整数最大值和方案数量,其中方案数对<span style="font-family: &#39;microsoft yahei&#39;; font-size: 14px; line-height: 26px; background-color: rgb(255, 255, 255);">10^9+7取模.</span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>样例1:
9
1 4
2 5
3 4
1 5
1 1
2 5
3 5
1 3
1 1</pre><p>样例2:</p><pre>2
1 1
2 2</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>样例1:
5 2
样例2:
NIE</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=10^6<br></p>
</div>
</div>