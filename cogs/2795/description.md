# 题目描述


<h3>
【题目描述】
</h3>
<div class="content">
<p>
windy学会了一种游戏。对于1到N这N个数字，都有唯一且不同的1到N的数字与之对应。最开始windy把数字按<br/>
顺序1，2，3，……，N写一排在纸上。然后再在这一排下面写上它们对应的数字。然后又在新的一排下面写上它们<br/>
对应的数字。如此反复，直到序列再次变为1，2，3，……，N。 <br/>
如： 1 2 3 4 5 6 对应的关系为 1-&gt;2 2-&gt;3 3-&gt;1 4-&gt;5 5-&gt;4 6-&gt;6 <br/>
windy的操作如下 <br/>
1 2 3 4 5 6 <br/>
2 3 1 5 4 6 <br/>
3 1 2 4 5 6 <br/>
1 2 3 5 4 6 <br/>
2 3 1 4 5 6 <br/>
3 1 2 5 4 6 <br/>
1 2 3 4 5 6 <br/>
这时，我们就有若干排1到N的排列，上例中有7排。现在windy想知道，对于所有可能的对应关系，有多少种可<br/>
能的排数。
</p>
</div>
<h3>
【输入格式】
</h3>
<div class="content">
<p>
多组数据，多个整数N,1 &lt;= N &lt;= 1000
</p>
</div>
<h3>
【输出格式】
</h3>
<div class="content">
<p>
每行一个整数，可能的排数。
</p>
</div>
<h3>
【样例输入】
</h3>
<pre>【输入样例一】
  3
  【输入样例二】
  3 10</pre>
<h3>
【样例输出】
</h3>
<pre>【输出样例一】
  3
  【输出样例二】
 3 16</pre>
<h3>
【提示】
</h3>
<p>
233
</p>
<div class="content">
</div>
<h3>
【来源】
</h3>
<div class="content">
<p>
<a href="problemset.php?search="></a> 
</p>
</div>
<h3>
【题目来源】
</h3>
<a href="http://www.lydsy.com/JudgeOnline/problem.php?id=1025">耒阳大世界（衡阳八中） OJ 1025</a>
