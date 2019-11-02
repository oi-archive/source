# 

 
 # 题目背景 
<p>疯狂繁衍的人类很快便发展出了新的国度和文明。为了防止世界大战再次发生，机器人国王Q将定期在国度间巡游，发表关于世界和平的演讲&hellip;&hellip;</p>

<p>&nbsp;</p> 

 
 # 题目描述 
<p>这座星球由n个国家组成，某些国家之间有单向的道路相连（为了&ldquo;国家稳定&ldquo;，限制单向进出是必要的）。国王Q在1号国家，现在他将沿着这些道路到各个国家发表演讲，然后回到1号国家。当然，作为国王，Q受到全世界人类的爱戴，所以在他的巡游中，最多可以逆着道路方向行走一次（但只能逆行一次&mdash;&mdash;哪怕以后经过同一条道路，他都不能再逆行）。现在Q想知道，在这次巡游中他最多可以到达多少个国家发表演讲。（Q可以多次经过同一个国家和同一条路，但国家数只算一次）</p>

<p>&nbsp;</p> 

 
 # 输入格式 
<p>第一行两个整数n,m，表示国家数和单向道路数。接下来m行每行两个整数a,b，表示有一条从a到b的单向道路（保证没有重边）。</p> 

 
 # 输出格式 
<p>一行一个整数，为Q最多可以到达的国家数量（包括1号国家）。</p> 

 
 # 提示 
<p>样例解释：<br />
&nbsp;&nbsp;&nbsp;&nbsp;Q的一种巡游路线为1-&gt;2-&gt;4-&gt;7-&gt;2-&gt;5-&gt;3-&gt;1，其中在3-&gt;5这条边上逆行了一次。</p>

<p>数据范围<br />
&nbsp;&nbsp;&nbsp;&nbsp;对于100%的数据，1&lt;=n,m&lt;=100000。</p> 
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
<tr><td>7 10
1 2
3 1
2 5
2 4
3 7
3 5
3 6
6 5
7 2
4 7
</td><td>6
</td></tr></table>
