# 题目描述


<h3>
【题目描述】
</h3>
<p>
Alice和Bob正在玩如下的游戏。首先Alice画一个有N个顶点，M条边的有向图。然后Bob试着摧毁它。在一次操作中他可以找到图中的一个点，并且删除它所有的入边或所有的出边。
</p>
<p>
Alice给每个点定义了两个值：Wi+和Wi-。如果Bob删除了第i个点所有的入边他要给Alice付Wi+元，如果他删除了所有的出边就需要给Alice付Wi元。
</p>
<p>
找到Bob删除图中所有边需要的最小花费。
</p>
<h3>
【输入格式】
</h3>
<p>
输入数据描述了Alice画下的图。
</p>
<p>
输入文件的第一行有两个数N,M(1&lt;=N&lt;=100,1&lt;=M&lt;=5000)。第二行有N个整数，描述了N个点的Wi+，同样的第三行是这N个点的Wi-。所有的费用都是正数并且不超过10^6。接下来的M行每行有两个数，代表有向图中相应的一条边。
</p>
<h3>
【输出格式】
</h3>
<p>
输出一行一个整数，即Bob的最小花费。
</p>
<h3>
【样例输入】
</h3>
<p>
3 6
</p>
<p>
1 2 3
</p>
<p>
4 2 1
</p>
<p>
1 2
</p>
<p>
1 1
</p>
<p>
3 2
</p>
<p>
1 2
</p>
<p>
3 1
</p>
<p>
2 3
</p>
<h3>
【样例输出】<br/>
</h3>
<p>
5
</p>
<h3>
【提示】
</h3>
<p>
样例的一个方案是：删除点1，2所有的入边，删除点2所有的出边。
</p>
<p>
输出格式和原题有所不同。原题要求输出方案。
</p>
<h3>
【来源】
</h3>
<p>
Northeastern Europe 2003,Northern Subregion (NEERC 2003)
</p>
<p>
<a target="_blank" href="http://poj.org/problem?id=2125">POJ 2125 Destroying the Graph</a> 
</p>
