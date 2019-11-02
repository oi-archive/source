<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>春春幼儿园举办了一年一度的“积木大赛”。今年比赛的内容是搭建一座宽度为 n 的大厦，大厦可以看成由 n 块宽度为1的积木组成，第i块积木的最终高度需要是hi。<br>在搭建开始之前，没有任何积木（可以看成 n 块高度为 0 的积木）。接下来每次操作，小朋友们可以选择一段连续区间[L,R]，然后将第 L 块到第 R 块之间（含第 L 块和第 R 块）所有积木的高度分别增加1。<br>小 M 是个聪明的小朋友，她很快想出了建造大厦的最佳策略，使得建造所需的操作次数最少。但她不是一个勤于动手的孩子，所以想请你帮忙实现这个策略，并求出最少的操作次数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入包含两行，第一行包含一个整数 n，表示大厦的宽度。<br>第二行包含 n 个整数，第i个整数为hi。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行，即建造所需的最少操作数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5<br>2 3 4 1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>其中一种可行的最佳方案,依次选择 [1,5] [1,3] [2,3] [3,3] [5,5]<br>对于 30%的数据，有1 ≤ n ≤ 10;<br>对于 70%的数据，有1 ≤ n ≤ 1000;<br>对于 100%的数据，有1 ≤ n ≤ 100000，0 ≤ hi ≤ 10000。</p>
<p> </p>
</div>
</div>