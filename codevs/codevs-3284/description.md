<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>黄大神十分喜欢吃馒头。兴奋之下他一下子买了N 个馒头请所有认识他的人吃。</p>
<p>但是黄大神不喜欢白色，喜欢红色、黄色、绿色等鲜艳的颜色。于是他把所有白色的馒头排成一列。然后进行M 次染色操作。每个染色操作都是用一个神奇的刷子把连续的多个馒头染成特定的某种颜色。一个馒头最终的颜色是最后一次染它的</p>
<p>颜色。如果一个馒头没有被染过色，那么它的颜色就是白色。现在CQF已经定好了染色计划：在第i次染色操作中，把第(i × p + q)mod N + 1个馒头和第(i × q + p)mod N + 1个馒头之间的馒头染成颜色i，其中p, q是特定的两个正整数。他想立即知道最后每个馒头的颜色。你能帮他吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行四个正整数<span style="font-family: Times New Roman;">N </span><span style="">，</span><span style="font-family: Times New Roman;">M </span><span style="">，</span><span style="font-family: Times New Roman;">p</span><span style="">，</span><span style="font-family: Times New Roman;">q</span><span style="">。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一共输出N&nbsp;行，第i行表示第i个馒头的最终颜色（如果最终颜色是白色就输出0）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 3 2 4</p>

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
<p>2</p>
<p>3</p>
<p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>在20%的数据中，1 ≤ N ≤ 1000<span style="">，</span><span style="font-family: CMR12;">1 </span>≤ M ≤ 10000</p>
<p>在40%的数据中，1 ≤ N ≤ 10000<span style="">，</span><span style="font-family: CMR12;">1 </span>≤ M ≤ 100000</p>
<p>在60%的数据中，1 ≤ N ≤ 50000<span style="">，</span><span style="font-family: CMR12;">1 </span>≤ M ≤ 500000</p>
<p>在80%的数据中，1 ≤ N ≤ 300000<span style="">，</span><span style="font-family: CMR12;">1 </span>≤ M ≤ 3000000</p>
<p>在100%的数据中，1 ≤ N ≤ 1000000<span style="">，</span><span style="font-family: CMR12;">1 </span>≤ M ≤ 10000000</p>
<p>保证所以输入数据中1 ≤ M ∗ p + q, M ∗ q + p ≤ 231 − 1。</p>
</div>
</div>