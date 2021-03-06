# 题目描述


<h3>
【题目描述】
</h3>
<p>
每天早晨醒来，FJ穿过农场从他家的谷仓。该农场有N个场（1≤n≤250），由M条双向通路的连接（1≤M＜＝25000），每一条通路都有一个长度。FJ的房子是在1场，谷仓在N场，两个场之间没有冗余通路，按一个适当的顺序沿路径走，可以前往任何场。当从一个场到另一个，FJ总是选择组成的路径序列的总长度最小通路通过。农夫约翰的奶牛，总是没有好起来，决定妨碍他的早上行程。他们计划建造一堆干草捆在一个农场上的通路上，这样会使其长度加倍。奶牛要选择，使他们的工作能最大限度地增加FJ从家里到谷仓的途径的距离。请帮助奶牛决定如何能延长FJ的路线。
</p>
<h3>
【输入格式】
</h3>
<p>
第1行有2个整数：N,M；
</p>
<p>
接下来有M行，也就是第2--M+1行，行j+1描述了三个用空格隔开的整数,表示双向通路：a_j b_j
</p>
<p>
l_j，在a_j和b_j是指数范围在1—n表示的通路，和l_j的路径长度（范围在1……1000000）。
</p>
<h3>
【输出格式】
</h3>
<p>
第1行，有一个数，表示最大限度地增加量的值，加倍的单一通道的长度可能影响在计算最短路径的总长度
</p>
<h3>
【样例输入】
</h3>
<pre>5 7
2 1 5
1 3 1
3 2 8
3 5 7
3 4 3
2 4 7
4 5 2
</pre>
<h3>
【样例输出】
</h3>
<pre>2
</pre>
<h3>
【提示】
</h3>
<p>
输出解释：
</p>
<p>
有5个场和7个途径。目前，从家的最短路径（1场）到谷仓（5场）是1-3-4-5总长度1 + 3 + 2 =
</p>
<p>
6。如果奶牛修改双长度的是3场到4场（其长度从3增加到6），然后FJ的最短路径是现在1-3-5，总长度1 + 7 =
</p>
<p>
8，比以前的最短路径长度更大，增加值为2。
</p>
