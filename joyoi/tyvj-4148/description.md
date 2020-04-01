# 

 
 # 题目背景 
<p>NOIP2014&nbsp;day2&nbsp;t2</p> 

 
 # 题目描述 
<p>在有向图&nbsp;G&nbsp;中，每条边的长度均为&nbsp;1，现给定起点和终点，请你在图中找一条从起点到<br />
终点的路径，该路径满足以下条件：&nbsp;<br />
1．路径上的所有点的出边所指向的点都直接或间接与终点连通。&nbsp;<br />
2．在满足条件&nbsp;1&nbsp;的情况下使路径最短。&nbsp;<br />
注意：图&nbsp;G&nbsp;中可能存在重边和自环，题目保证终点没有出边。&nbsp;<br />
请你输出符合条件的路径的长度。&nbsp;</p> 

 
 # 输入格式 
<p>第一行有两个用一个空格隔开的整数&nbsp;n&nbsp;和&nbsp;m，表示图有&nbsp;n&nbsp;个点和&nbsp;m&nbsp;条边。&nbsp;<br />
接下来的&nbsp;m&nbsp;行每行&nbsp;2&nbsp;个整数&nbsp;x、y，之间用一个空格隔开，表示有一条边从点&nbsp;x&nbsp;指向点<br />
y。&nbsp;<br />
最后一行有两个用一个空格隔开的整数&nbsp;s、t，表示起点为&nbsp;s，终点为&nbsp;t。</p>

<p>&nbsp;</p> 

 
 # 输出格式 
<p>输出只有一行，包含一个整数，表示满足题目᧿述的最短路径的长度。如果这样的路<br />
径不存在，输出-1。</p>

<p>&nbsp;</p> 

 
 # 提示 
<p>输入样例1</p>

<p>3&nbsp;2&nbsp;<br />
1&nbsp;2&nbsp;<br />
2&nbsp;1&nbsp;<br />
1&nbsp;3</p>

<p>输出样例1</p>

<p>-1</p>

<p>输入样例2</p>

<p>6&nbsp;6&nbsp;<br />
1&nbsp;2&nbsp;<br />
1&nbsp;3&nbsp;<br />
2&nbsp;6&nbsp;<br />
2&nbsp;5&nbsp;<br />
4&nbsp;5&nbsp;<br />
3&nbsp;4&nbsp;<br />
1&nbsp;5&nbsp;</p>

<p><span style="line-height: 1.6em;">输出样例2</span></p>

<p>3</p>

<p>数据说明<br />
对于30%的数据，0&lt;n&le;10，0&lt;m&le;20；&nbsp;<br />
对于60%的数据，0&lt;n&le;100，0&lt;m&le;2000；&nbsp;<br />
对于100%的数据，0&lt;n&le;10,000，0&lt;m&le;&nbsp;200,000,0&lt;x,y,s,t&le;n,x&ne;t。&nbsp;</p>

<p>&nbsp;</p> 
