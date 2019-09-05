# 题目描述


<h3>
【题目描述】
</h3>
<p>
Great Dodgers公司最近开发了一种全新的游戏机。
</p>
<p>
游戏机的玩法是：你向机器内放一枚硬币，拉动手柄。然后它会随机选一个整数。如果选中的整数是0你就赢了头奖。否则游戏机会用幸运数字p1,p2,...,pn分别去除选中的数。如果这n个余数中至少有一个是0，你也赢了。
</p>
<p>
Great Dodgers公司希望计算他们游戏机上玩家的获胜概率。他们尝试这么做，但失败了。因此Great Dodgers雇佣了你来写一个程序计算上面所说的概率。
</p>
<p>
一名数学家提示你，所求的概率可以用如下极限表示：
</p>
<p>
<br/>
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;, Times, serif;font-size:x-large;">lim</span><sub>k→∞</sub><span style="font-family:&#39;Times New Roman&#39;, Times, serif;font-size:x-large;">(S</span><sub>k</sub><span style="font-family:&#39;Times New Roman&#39;, Times, serif;font-size:x-large;">/2k+1).</span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;, Times, serif;font-size:x-large;"><br/>
</span> 
</p>
<p>
其中Sk是在-k到k之间且能被至少一个幸运数字整除的整数数量。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件的第一行有一个整数n（1&lt;=n&lt;=16），即幸运数字的数量。
</p>
<p>
接下来是n个幸运数字（1&lt;=pi&lt;=10^9）.
</p>
<h3>
【输出格式】
</h3>
<p>
显然所求的概率是一个有理数。用最简分数的形式输出它。
</p>
<p>
输出文件的第一行是获胜概率的分子，第二行是分母。分子和分母都不能有前导零。记住必须输出最简形式。
</p>
<h3>
【样例输入】
</h3>
<pre>2
4 6</pre>
<h3>
【样例输出】
</h3>
<pre>1
3</pre>
<h3>
【来源】
</h3>
<p>
Northeastern Europe(NEERC) 2004,Northern Subregion - Problem J.Jackpot
</p>
<p>
<a href="http://poj.org/problem?id=2103" target="_blank">POJ 2103 Jackpot</a> 
</p>
