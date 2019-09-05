# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
有一骑士在一个无限大的棋盘上移动。它每次的移动都用一个整数对来描述——整数对（a,b）表示骑士能从位置（x,y）跳到位置(x+a,y+b)或者(x-a,y-b)。每个骑士有一系列的已确定的整数对，描述这骑士能进行哪些移动。我们保证每个骑士能到达的位置不在同一直线上。
</p>
<p>
当两个骑士以位置（0，0）为始点能到达的所有位置完全相同时（可能做很多次移动），我们就说这两个骑士是等价的。可以证明对于每一个骑士，都存在一个只有两个整数对的等价骑士。
</p>
<p>
<span style="font-size:16px;">我们需要你找出一个骑士的等价骑士，要求等价骑士的只有两个整数对。</span> 
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
第一行是一个整数N(3&lt;=N&lt;=100)；
</p>
<p>
之后的N行，每行两个整数（ai，bi），描述骑士的一个移动，-100&lt;=ai,bi&lt;=100,
</p>
<h3>
【输出格式】
</h3>
<p>
第一行为点对(a,b),第二行为点对(c,d)，描述这个等价骑士的移动。(a,b,c,d的绝对值均小于900）
</p>
<h3>
【样例输入】
<pre>3
24 28
15 50
12 21
</pre>
【样例输出】
<pre>3 0</pre>
<pre>0 1</pre>
【提示】
</h3>
<p>
在此键入。
</p>
<h3>
【来源】
</h3>
<p>
http://www.oi.edu.pl/old/php/show.php?ac=e180702&amp;module=show&amp;file=zadania/oi12/sko
</p>