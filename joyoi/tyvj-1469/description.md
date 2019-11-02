# 

 
 # 题目背景 
&nbsp;&nbsp;为了能够赶在Candy生日这天送给她一个特制的礼物，飘飘乎居士最近一直躲在家中研究自己发明的飘飘乎数独<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;飘飘乎数独每行的数字都由1~m自然数填满（每行中每个数字用且只能用一次），但相邻的自然数（5&nbsp;4与4&nbsp;5都认为相邻）却不会出现在相邻的方格中（包括左右相邻和上下相邻），对于这样的一个飘飘乎数独，当然有许许多多的填法。但是，飘飘乎数独每一列都有一个得分规则：第i列的得分为第i列所有自然数的总和*i，最后的总分即为m列得分之和。飘飘乎居士当然希望给Candy的礼物是一个总分最大的飘飘乎数独 

 
 # 输入格式 
&nbsp;第一行，两个正整数n&nbsp;m，表示一个n*m飘飘乎数独<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接下来一个矩阵，矩阵的每一行数为一个非负数，0表示飘飘乎居士需要用1~m其中一个自然数填充的方格，非0自然数代表已经填充过的方格（即不能够更改的方格）<BR> 

 
 # 输出格式 
一行，最后的总分 

 
 # 提示 
最优的飘飘乎数独为(并且只存在这一种方案)<BR>1&nbsp;3&nbsp;5&nbsp;2&nbsp;4<BR>4&nbsp;1&nbsp;3&nbsp;5&nbsp;2<BR>规定横竖都不能有相邻的自然数，但可以有相等的自然数<BR>得分为第一列&nbsp;1*(1+4)=5<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第二列&nbsp;2*（3+1）=8<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第三列&nbsp;3*（5+3）=24<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第四列&nbsp;4*（2+5）=28<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第五列&nbsp;5*（4+2）=30<BR>总分为95，也就是最后的答案<BR>对于30%的数据，&nbsp;保证&nbsp;3&lt;=n&nbsp;m&lt;=5，0的个数&lt;=10个<BR>对于100%的数据，保证&nbsp;3&lt;=n&nbsp;m&lt;=7&nbsp;&nbsp;0的个数&lt;=n*m<BR>数据保证至少存在一个解。<BR> 
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
<tr><td>2 5
1 3 0 2 0
4 0 3 5 2
</td><td>95
</td></tr></table>
