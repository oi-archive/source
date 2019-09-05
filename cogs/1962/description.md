# 题目描述


<h3>
【题目描述】
</h3>
<p>
有一棵点数为N的树，树边有边权。给你一个在0~N之内的正整数K，你要在这棵树中选择K个点，将其染成黑色，并将其他的N-K个点染成白色。将所有点染色后，你会获得黑点两两之间的距离加上白点两两之间距离的和的收益。问收益最大值是多少。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行两个整数N,K。
</p>
<p>
接下来N-1行每行三个正整数fr,to,dis，表示该树中存在一条长度为dis的边(fr,to)。输入保证所有点之间是联通的。
</p>
<h3>
【输出格式】
</h3>
<p>
输出一个正整数，表示收益的最大值。
</p>
<h3>
【输入样例1】
</h3>
<p>
3 1
</p>
<p>
1 2 1
</p>
<p>
1 3 2
</p>
<h3>
【输出样例1】
</h3>
<p>
3
</p>
<h3>
【输入样例2】
</h3>
<p>
5 2
</p>
<p>
1 2 3
</p>
<p>
1 5 1
</p>
<p>
2 3 1
</p>
<p>
2 4 2
</p>
<h3>
【输出样例2】
</h3>
<p>
17
</p>
<h3>
【样例解释】
</h3>
<p>
在第二个样例中，将点1,2染黑就能获得最大收益。
</p>
<h3>
【数据范围】
</h3>
<p>
对于30%的数据，N&lt;=20
</p>
<p>
对于50%的数据，N&lt;=100
</p>
<p>
对于100%的数据，N&lt;=2000,0&lt;=K&lt;=N
</p>