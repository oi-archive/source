# 题目描述


<h3>
【题目描述】
</h3>
<p>
  在大多数专业的体育赛事中，拉拉队总是对观众的娱乐起着相当大的作用(尤其是在休息时，并开始玩之前)世界杯足球也不例外。通常情况下，拉拉队员们组成一个小组，并在场地中央表演，有时她们中有些人被置于边缘以便更接近观众。组织者希望确保每个边至少有一名拉拉队员。对于这个问题，我们将场地建模为一个M* N个矩形网格，共有k名队员。用于放置拉拉队的限制说明如下：
</p>
<p>
<br/>
</p>
<p>
--4条边上每条边至少有一名拉拉队员。需要注意的是，放置一个拉拉队员在一个角落里的网格中相当于同时涵盖两条边。
</p>
<p>
--一个网格中最多有一名队员。
</p>
<p>
--所有可用的啦啦队必须被分配给一个网格。也就是说，没有队员可以被排除在外(处于闲置状态)。
</p>
<p>
<img src="/upload/image/20140109/20140109012341_47916.jpg" alt=""/> 
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
输入第一行为数据组数T(T≤50)，每组数据包含3个整数m ,n , k(2≤m,n≤20,k≤500).
</p>
<h3>
【输出格式】
</h3>
<p>
对于每组数据，输出总方案数除以1 000 007的余数。
</p>
<h3>
【样例输入】
</h3>
<pre>2
2 2 1
2 3 2
</pre>
<h3>
【样例输出】
</h3>
<pre>Case 1: 0
Case 2: 2
</pre>
<h3>
【提示】
</h3>
<p>
相当于：
</p>
<p>
在一个m行n列的矩形网格里放k个石子，问有多少种放法？每个格子里最多放一个石子，所有石子都要用完，并且第一行，最后一行，第一列，最后一列都得有石子。
</p>
<h3>
【来源】
</h3>
<p>
UVa 11806 Cheerleaders.
</p>
<p>
刘汝佳，《算法竞赛入门经典训练指南》表2.2
</p>