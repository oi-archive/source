# 题目描述


<h3>
【题目描述】
</h3>
<p>
Kreso最近找了份送外卖的兼职工作。
</p>
<p>
在A市有N家餐馆，编号为1 ~ N。它们由恰好N-1条路相连，使得任意两家餐馆相互可达。每天，Kreso首先要花费M单位时间从这些餐馆取外卖。
</p>
<p>
Kreso最初位于1号餐馆。每1单位时间，他要么从所在餐馆取出外卖；要么移动到一个相邻的餐馆。注意，经过一个餐馆并不会取外卖，取外卖要单独花费1单位时间。
</p>
<p>
设N家餐馆的外卖价值分别是A1到AN。请问在这次取外卖的过程中，Kreso取得的所有外卖的价值之和最大是多少？
</p>
<h3>
【输入格式】
</h3>
<p>
第一行，两个正整数N, M。
</p>
<p>
第二行，N个用空格隔开的正整数A1, …, AN。
</p>
<p>
接下来N-1行，每行两个整数U, V，表示有一条路连接U号餐馆和V号餐馆。
</p>
<h3>
【输出格式】
</h3>
<p>
输出一行，一个整数，表示答案。
</p>
<h3>
【样例输入】
</h3>
<pre>3 5
9 2 5
1 2
1 3
</pre>
<h3>
【样例输出】
</h3>
<pre>14
</pre>
<h3>
【提示】
</h3>
<p>
对于30%的数据，1 ≤ N, M ≤ 100.
</p>
<p>
对于100%的数据，1 ≤ N, M ≤ 500, 1 ≤ U, V ≤ N, 1 ≤ Ai ≤ 10e6.
</p>
<p>
(由于数据水，O(n^4)能过！)
</p>