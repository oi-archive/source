<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>   小<span style="font-family: 'Times New Roman';">H</span><span style="">在学习“集合与图论”的时候遇到了一个问题，他思考了很久依然无法很好完成这个问题。于是他只好来求助你了，给出</span><span style="font-family: 'Times New Roman';">n</span><span style="">个点</span><span style="font-family: 'Times New Roman';">m</span><span style="">条边的带权无向图（即每条无向边上都有一个权值），有</span><span style="font-family: 'Times New Roman';">3</span><span style="">个集合</span><span style="font-family: 'Times New Roman';">A</span><span style="">、</span><span style="font-family: 'Times New Roman';">B</span><span style="">、</span><span style="font-family: 'Times New Roman';">C</span><span style="">。一开始无向图中所有点都属于</span><span style="font-family: 'Times New Roman';">A</span><span style="">集合，有如下</span><span style="font-family: 'Times New Roman';">9</span><span style="">种操作：</span></p>
<p>MoveA x<span style="">：表示将第</span><span style="font-family: 'Times New Roman';">x</span><span style="">个点从所在集合中删除，并加入至</span><span style="font-family: 'Times New Roman';">A</span><span style="">集合。</span></p>
<p>MoveB x<span style="">：表示将第</span><span style="font-family: 'Times New Roman';">x</span><span style="">个点从所在集合中删除，并加入至</span><span style="font-family: 'Times New Roman';">B</span><span style="">集合。</span></p>
<p>MoveC x<span style="">：表示将第</span><span style="font-family: 'Times New Roman';">x</span><span style="">个点从所在集合中删除，并加入至</span><span style="font-family: 'Times New Roman';">C</span><span style="">集合。</span></p>
<p>AskAA<span style="">：询问两个端点都属于</span><span style="font-family: 'Times New Roman';">A</span><span style="">集合的所有边中最小的权值是多少。</span></p>
<p>AskAB<span style="">：询问两个端点分别属于</span><span style="font-family: 'Times New Roman';">A</span><span style="">集合和</span><span style="font-family: 'Times New Roman';">B</span><span style="">集合的所有边中最小的权值是多少。</span></p>
<p>AskAC<span style="">：询问两个端点分别属于</span><span style="font-family: 'Times New Roman';">A</span><span style="">集合和</span><span style="font-family: 'Times New Roman';">C</span><span style="">集合的所有边中最小的权值是多少。</span></p>
<p>AskBB<span style="">：询问两个端点都属于</span><span style="font-family: 'Times New Roman';">B</span><span style="">集合的所有边中最小的权值是多少。</span></p>
<p>AskBC<span style="">：询问两个端点分别属于</span><span style="font-family: 'Times New Roman';">B</span><span style="">集合和</span><span style="font-family: 'Times New Roman';">C</span><span style="">集合的所有边中最小的权值是多少。</span></p>
<p>AskCC<span style="">：询问两个端点都属于</span><span style="font-family: 'Times New Roman';">C</span><span style="">集合的所有边中最小的权值是多少。</span></p>
<p>   你能帮助他解决这个问题吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>   输入的第<span style="font-family: 'Times New Roman';">1</span><span style="">行有两个正整数，分别表示</span><span style="font-family: 'Times New Roman';">n</span><span style="">和</span><span style="font-family: 'Times New Roman';">m</span><span style="">。</span></p>
<p>   在第<span style="font-family: 'Times New Roman';">2</span><span style="">行至第</span><span style="font-family: 'Times New Roman';">m+1</span><span style="">行中，每行有三个正整数，分别为</span><span style="font-family: 'Times New Roman';">u</span><span style="">、</span><span style="font-family: 'Times New Roman';">v</span><span style="">、</span><span style="font-family: 'Times New Roman';">w</span><span style="">。表示这条无向边的两个端点分别为</span><span style="font-family: 'Times New Roman';">u</span><span style="">和</span><span style="font-family: 'Times New Roman';">v(u != v)</span><span style="">，且这个边的权值为</span><span style="font-family: 'Times New Roman';">w(w&lt;=10^9)</span><span style="">。</span></p>
<p>   第<span style="font-family: 'Times New Roman';">m+2</span><span style="">行有一个正整数</span><span style="font-family: 'Times New Roman';">q</span><span style="">，表示有</span><span style="font-family: 'Times New Roman';">q</span><span style="">个询问。</span></p>
<p>   在第<span style="font-family: 'Times New Roman';">m+3</span><span style="">行至第</span><span style="font-family: 'Times New Roman';">m+q+2</span><span style="">行中，每行的输入方式为题目描述里</span><span style="font-family: 'Times New Roman';">9</span><span style="">种操作中的一种。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">&nbsp;&nbsp;&nbsp;对于所有的<span style="font-family: 'Times New Roman';">Ask</span><span style="font-family: 宋体;">操作输出最小的权值，如果不存在则输出&ldquo;</span><span style="font-family: 'Times New Roman';">No&nbsp;Found!</span><span style="font-family: 宋体;">&rdquo;。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 3</p>
<p>1 2 1 </p>
<p>2 3 2</p>
<p>3 1 3</p>
<p>5</p>
<p>AskAA</p>
<p>AskAB</p>
<p>MoveB 2</p>
<p>AskAA</p>
<p>AskAB</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>No Found!</p>
<p>3</p>
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>对于其中<span style="font-family: 'Times New Roman';">20%</span><span style="">的数据，满足</span><span style="font-family: 'Times New Roman';">n&lt;=50, m&lt;=2500, q&lt;=2500</span><span style="">。</span></p>
<p>对于另外<span style="font-family: 'Times New Roman';">30%</span><span style="">的数据，满足</span><span style="font-family: 'Times New Roman';">n&lt;=100, m&lt;=10000, q&lt;=20000</span><span style="">。</span></p>
<p>对于另外<span style="font-family: 'Times New Roman';">50%</span><span style="">的数据，满足</span><span style="font-family: 'Times New Roman';">n&lt;=100000,m&lt;=500000,q&lt;=100000</span><span style="">。且无向图上任意两个点之间至多能选出</span><span style="font-family: 'Times New Roman';">3</span><span style="">条不相交的路径。</span></p>
</div>
</div>
</div>