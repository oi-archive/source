<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>学生在我们USACO的竞赛中的得分越多我们越高兴。</p>
<p>我们试着设计我们的竞赛以便人们能尽可能的多得分,这需要你的帮助。</p>
<p>我们可以从几个种类中选取竞赛的题目,这里的一个"种类"是指一个竞赛题目的集合,解决集合中的题目需要相同多的时间并且能得到相同的分数。 你的任务是写一个程序来告诉USACO的职员,应该从每一个种类中选取多少题目,使得解决题目的总耗时在竞赛规定的时间里并且总分最大。 输入包括竞赛的时间,M(1 &lt;= M &lt;= 10,000)(不要担心,你要到了训练营中才会有长时间的比赛)和N,"种类"的数目1 &lt;= N &lt;= 10,000。 后面的每一行将包括两个整数来描述一个"种类":</p>
<p>第一个整数说明解决这种题目能得的分数(1 &lt;= points &lt;= 10000),第二整数说明解决这种题目所需的时间(1 &lt;= minutes &lt;= 10000)。 你的程序应该确定我们应该从每个"种类"中选多少道题目使得能在竞赛的时间中得到最大的分数。</p>
<p>来自任意的"种类"的题目数目可能是任何非负数(0或更多)。</p>
<p>计算可能得到的最大分数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第 1 行: M, N--竞赛的时间和题目"种类"的数目。</p>
<p>第 2-N+1 行: 两个整数:每个"种类"题目的分数和耗时。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>单独的一行包括那个在给定的限制里可能得到的最大的分数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>300 4
100 60
250 120
120 100
35 20</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>605</pre>
<pre> </pre>
<pre>{从第2个"种类"中选两题第4个"种类"中选三题}</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见描述</p>
</div>
</div>