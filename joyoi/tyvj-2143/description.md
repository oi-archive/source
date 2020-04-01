# 

 
 # 题目描述 
<p>有向图&nbsp;G&nbsp;有&nbsp;n&nbsp;个顶点&nbsp;1,&nbsp;2,&nbsp;&hellip;,&nbsp;n，点&nbsp;i&nbsp;的权值为&nbsp;w(i)。现在有一只蚂蚁，从给定的起点&nbsp;v0&nbsp;出发，沿着图&nbsp;G&nbsp;的边爬行。开始时，它的体力为&nbsp;1。每爬过一条边，它的体力都会下降为原来的&nbsp;p&nbsp;倍，其中&nbsp;p&nbsp;是一个给定的小于&nbsp;1&nbsp;的正常数。而蚂蚁爬到某个顶点时的幸福度，是它当时的体力与该点权值的乘积。&nbsp;</p>

<p><span style="line-height: 1.6em;">我们把蚂蚁在爬行路径上幸福度的总和记为&nbsp;H。很显然，对于不同的爬行路径，H&nbsp;的值也可能不同。小&nbsp;Z&nbsp;对&nbsp;H&nbsp;值的最大可能值很感兴趣，你能帮助他计算吗？<u>注意，蚂蚁爬行的路径长度可能是无穷的。</u></span></p> 

 
 # 输入格式 
<p>文件的每一行中两个数之间用一个空格隔开。&nbsp;</p>

<p>输入文件第一行包含两个正整数&nbsp;n,&nbsp;m，分别表示&nbsp;G&nbsp;中顶点的个数和边的条数。&nbsp;</p>

<p>第二行包含&nbsp;n&nbsp;个非负实数，依次表示&nbsp;n&nbsp;个顶点权值&nbsp;w(1),&nbsp;w(2),&nbsp;&hellip;,&nbsp;w(n)。</p>

<p>第三行包含一个正整数&nbsp;v0，表示给定的起点。&nbsp;</p>

<p>第四行包含一个实数&nbsp;p，表示给定的小于&nbsp;1&nbsp;的正常数。&nbsp;</p>

<p>接下来&nbsp;m&nbsp;行，每行两个正整数&nbsp;x,&nbsp;y，表示&lt;x,&nbsp;y&gt;是&nbsp;G&nbsp;的一条有向边。<u>可能有自环，但不会有重边。</u>&nbsp;</p> 

 
 # 输出格式 
<p>仅包含一个实数，即&nbsp;H&nbsp;值的最大可能值，四舍五入到小数点后一位。&nbsp;</p> 

 
 # 提示 
<h3>样例说明</h3>

<p>当蚂蚁的爬行路径为&nbsp;1&rarr;2&rarr;3&rarr;4&rarr;2&rarr;3&rarr;4&rarr;&hellip;&rarr;2&rarr;3&rarr;4&rarr;&hellip;时，<span style="line-height: 1.6em;">H</span><span style="line-height: 1.6em;">=</span><span style="line-height: 1.6em;">10.0</span><span style="line-height: 1.6em;">+8.0*0.5+8.0*0.5<sup>2</sup>+⋯。可以证明，这个无穷序列的总和为&nbsp;18.0，且这就是&nbsp;H&nbsp;的最大值。</span></p>

<p><a href="http://cexou.img48.wal8.com/img48/543212_20160415183019/146311881869.png"><img alt="" src="/source/joyoi/tyvj-2143/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjE0My9odHRwOi8vY2V4b3UuaW1nNDgud2FsOC5jb20vaW1nNDgvNTQzMjEyXzIwMTYwNDE1MTgzMDE5L3MvMTQ2MzExODgxODY5X21lZGl1bS5wbmc=.png" style="width: 427px; height: 247px;" /></a></p>

<p>另外，若本样例中&nbsp;w(5)改为&nbsp;17.0，其余数据不变，则当路径为&nbsp;1&rarr;2&rarr;3&rarr;4&rarr;5&nbsp;时，H=18.0625。可以证明，这就是此时&nbsp;H&nbsp;的最大值。</p>

<h3>数据规模</h3>

<p>对于&nbsp;20%的数据，p&nbsp;&le;0.5；&nbsp;</p>

<p>另有&nbsp;20%的数据，保证&nbsp;H&nbsp;的最大值在有限路径上取到；</p>

<p>对于&nbsp;100%的数据，n&nbsp;&le;&nbsp;100，m&nbsp;&le;&nbsp;1000，p&nbsp;&le;&nbsp;1&nbsp;&ndash;&nbsp;10-6，w(i)&nbsp;&le;&nbsp;100&nbsp;(i&nbsp;=&nbsp;1,&nbsp;2,&nbsp;&hellip;,&nbsp;n)。</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>5 5
10.0 8.0 8.0 8.0 15.0
1
0.5
1 2
2 3
3 4
4 2
4 5
</td><td>18.0</td></tr></table>
