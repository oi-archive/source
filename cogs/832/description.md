# 题目描述


<p>
usaco/Score Inflation
</p>
<div>
<div>
<div>
<p>
译 by timgreen
</p>
描述
</div>
<div>
<p>
学生在我们USACO的竞赛中的得分越多我们越高兴。<br/>
我们试着设计我们的竞赛以便人们能尽可能的多得分,这需要你的帮助。<br/>
我们可以从几个种类中选取竞赛的题目,这里的一个&#34;种类&#34;是指一个竞赛题目的集合,解决集合中的题目需要相同多的时间并且能得到相同的分数。<br/>
你的任务是写一个程序来告诉USACO的职员,应该从每一个种类中选取多少题目,使得解决题目的总耗时在竞赛规定的时间里并且总分最大。<br/>
输入包括竞赛的时间,M(1 &lt;= M &lt;= 10,000)(不要担心,你要到了训练营中才会有长时间的比赛)和N,&#34;种类&#34;的数目1 &lt;= N &lt;= 10,000。<br/>
后面的每一行将包括两个整数来描述一个&#34;种类&#34;:<br/>
第一个整数说明解决这种题目能得的分数(1 &lt;= points &lt;= 10000),第二整数说明解决这种题目所需的时间(1 &lt;= minutes &lt;= 10000)。<br/>
你的程序应该确定我们应该从每个&#34;种类&#34;中选多少道题目使得能在竞赛的时间中得到最大的分数。<br/>
来自任意的&#34;种类&#34;的题目数目可能任何非负数(0或更多)。<br/>
计算可能得到的最大分数。
</p>
</div>
<div>
</div>
<div>
<div>
格式
</div>
<div>
PROGRAM NAME: inflate
</div>
<div>
INPUT FORMAT:(file inflate.in)
</div>
<div>
</div>
<div>
<table border="1">
<tbody>
<tr>
<td>
第 1 行:
</td>
<td>
M, N--竞赛的时间和题目&#34;种类&#34;的数目。
</td>
</tr>
<tr>
<td>
第 2-N+1 行:
</td>
<td>
两个整数:每个&#34;种类&#34;题目的分数和耗时。
</td>
</tr>
</tbody>
</table>
 
</div>
<div>
OUTPUT FORMAT:(file inflate.out)
</div>
<div>
<p>
单独的一行包括那个在给定的限制里可能得到的最大的分数。
</p>
</div>
<div>
SAMPLE INPUT
<div>
(file inflate.in)
</div>
</div>
<div>
<p>
300 4<br/>
100 60<br/>
250 120<br/>
120 100<br/>
35 20
</p>
</div>
<div>
SAMPLE OUTPUT
<div>
(file inflate.out)
</div>
</div>
<div>
<p>
605<br/>
{从第2个&#34;种类&#34;中选两题第4个&#34;种类&#34;中选三题}
</p>
</div>
</div>
</div>
</div>
