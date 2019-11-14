# 

 
 # 题目背景 
<p><span style="font-family: arial, 宋体, sans-serif; font-size: 14px; line-height: 24px; text-indent: 28px;">全国青少年信息学奥林匹克冬令营2011测试题</span></p> 

 
 # 题目描述 
<p><img alt="" src="/source/joyoi/tyvj-4444/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotNDQ0NC9odHRwOi8vY2V4b3UuaW1nNDcud2FsOC5jb20vaW1nNDcvNTQzMjEyXzIwMTYwNDE1MTgzMDE5LzE0NjE0MTA2ODU5Mi5wbmc=.png" style="width: 747px; height: 854px;" /></p> 

 
 # 输入格式 
<p>输入文件&nbsp;joy.in&nbsp;的第一行包含一个正整数&nbsp;T，表示测试数据的组数。<span style="line-height: 1.6em;">接下来为&nbsp;T&nbsp;组数据。</span></p>

<p><span style="line-height: 1.6em;">每一组数据的第一行包含两个整数&nbsp;n&nbsp;和&nbsp;q，分别表示&nbsp;U&nbsp;中的元素个数和事件个数。</span></p>

<p>接下来的一行，包含&nbsp;n&nbsp;个用一个空格隔开的正整数，第&nbsp;i&nbsp;个整数为初始的序列中第&nbsp;i&nbsp;个元素&nbsp;<em>u<sub>i</sub></em>。&nbsp;<br />
接下来&nbsp;q&nbsp;行，每行代表一个事件（按事件发生顺序输入）。每行的第一个数非&nbsp;0&nbsp;即&nbsp;1，表示这个事件的类型。&nbsp;</p>

<p>若为&nbsp;0&nbsp;：在&nbsp;0&nbsp;之后还有三个整数&nbsp;l，r&nbsp;和&nbsp;c（这四个数之间均有一个空格），<br />
表示小&nbsp;W&nbsp;将<em>u<sub>l,&nbsp;</sub></em><em style="line-height: 20.8px;">u<sub>l+1,&nbsp;...,</sub>u<sub><span style="font-size: 12px;">r</span></sub></em>增加&nbsp;c；&nbsp;<br />
若为&nbsp;1&nbsp;：表示两人进行了一次&ldquo;拼点游戏&rdquo;，你需要输出相应的结果。</p>

<p><u><strong>输入数据保证序列U&nbsp;中的所有元素总是正整数。</strong></u>&nbsp;</p> 

 
 # 输出格式 
<p>输出文件为&nbsp;joy.out。&nbsp;<br />
对于每一组测试数据，依次对每一次&ldquo;拼点游戏&rdquo;输出一行包含两个由一个空格隔开的整数&nbsp;D<sub>max</sub>&nbsp;和&nbsp;X，其中</p>

<p>D<sub>max</sub>&nbsp;为对于当前序列U，小&nbsp;W&nbsp;所能选出的最优下标序列所对应的点数；</p>

<p>X&nbsp;表示小&nbsp;Y&nbsp;最少需要进行几次修改操作才能获胜。如果小&nbsp;Y&nbsp;不论多少次操作都无法获胜，则输出-1。&nbsp;</p>

<p><strong><u>数据保证最优下标序列总是唯一的。</u></strong></p> 

 
 # 提示 
<h3>评分标准</h3>

<p>一个测试点包含多组测试数据，对于该测试点：<br />
如果所有的&nbsp;Dmax均正确但某个&nbsp;X&nbsp;不正确，则可以得到&nbsp;3&nbsp;分；&nbsp;如果所有的&nbsp;X&nbsp;均正确但某个&nbsp;Dmax不正确，则可以得到&nbsp;7&nbsp;分；&nbsp;如果所有回答均正确，则可以得到&nbsp;10&nbsp;分。&nbsp;</p>

<h3>数据规模</h3>

<p>对于&nbsp;10%的数据满足&nbsp;n，q&nbsp;&le;&nbsp;13；&nbsp;<br />
对于&nbsp;30%的数据满足&nbsp;n，q&nbsp;&le;&nbsp;1000；&nbsp;<br />
对于另外&nbsp;20%的数据满足&nbsp;T=1&nbsp;且&nbsp;n&nbsp;&le;&nbsp;40000；&nbsp;<br />
对于&nbsp;100%的数据满足&nbsp;T&nbsp;&le;&nbsp;3&nbsp;且&nbsp;n，q&nbsp;&le;&nbsp;10<sup>5</sup>，同时初始序列&nbsp;U&nbsp;满足&nbsp;0&nbsp;&lt;ui&lt;&nbsp;2<sup>31</sup>，|c|&lt;105。</p> 
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
<tr><td>2 
5 9 
9 10 7 6 8 
1 
0 4 5 2 
0 3 5 4 
1 
0 2 5 -2 
0 3 5 -3
0 4 5 -2
0 5 5 -4
1 
4 3 
2 4 3 5 
1 
0 3 3 3 
1 </td><td>3 1
5 -1
0 0
4 -1
4 -1


【样例解释】
输入数据包含两组测试数据。
在第一组测试数据中：
第一次“拼点游戏”时，最优下标序列为(1,2,4,5)，小 Y 只需要进行一次修改操作：选择 k=1，以及非负整数 z1=1，z2=0。这样经过修改操作之后下标序列将变为(1,3,4,5)，小 Y 获胜。 
第三次“拼点游戏”时，序列 U 为(9,8,6,5,3)，小W 所选择的最优下标序列为空序列，所产生的点数为 0。在这种情况下，小 Y 无法进行任何修改操作（也无需进行任何修改操作），此时小 Y 已经直接获胜。 </td></tr></table>
