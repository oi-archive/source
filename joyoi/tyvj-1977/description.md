# 

 
 # 题目背景 
　　　Freda：对了Rainbow，我给乃带了一块蛋糕呢~<br>　　　Rainbow：Thx~<br>　　　Freda：不客气lala~<br>　　　Rainbow：不过蛋糕好大的说~<br>　　　Freda：那就分些给Resodo和Shuriken它们吧~ 

 
 # 题目描述 
Rainbow得到了一块蛋糕，它想分给大家一起享用。如图所示，Rainbow把蛋糕分成了同样大小的N份，即D1,D2,...,Dn-1,Dn。根据Freda提出的建议，相邻的两块蛋糕不能分给同一个人。我们认为：对于1&lt;i&lt;n，Di是与Di+1和Di-1相邻的；Dn与Dn-1和D1相邻；D1与D2和Dn相邻。<br>今天，一共有k只Freda和Rainbow的好友来Rainbow的城堡里玩了，当然，这k只小猫里包括了Freda和Rainbow。每个朋友可以分给任意多份蛋糕（包括0份&gt;_&lt;）这样，爱好数学的Rainbow就很想知道：一共有多少种方案来分这一大块蛋糕呢？两种方案不同当且仅当存在1&lt;=i&lt;=N，Di被分给了两位不同的好友。Rainbow请你帮忙计算~<br><img src="/source/joyoi/tyvj-1977/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTk3Ny9odHRwOi8vZmlsZXMuYmxvZ2NuLmNvbS93cDAxL00wMC8wOC9BQS93S2dLQzFCbFl3WUFBQUFBQUFHaVBpbUcydjAwNjMuanBn.jpg" border=0 align=middle> 

 
 # 输入格式 
一行两个整数N,k，分别表示蛋糕被分成的份数和朋友的数目。 

 
 # 输出格式 
一行一个整数Ans，表示合法的方案数。由于这个数可能很大，所以你只需要输出它mod&nbsp;10000007的值。如果没有合法方案，输出0即可。 

 
 # 提示 
样例解释:<br>6种方案如下(每个方案中第i数字表示Di分给的人的序号）:<br>1&nbsp;2&nbsp;3，&nbsp;2&nbsp;3&nbsp;1，&nbsp;1&nbsp;3&nbsp;2，&nbsp;2&nbsp;1&nbsp;3，&nbsp;3&nbsp;1&nbsp;2，&nbsp;3&nbsp;2&nbsp;1.<br>数据范围与约定:<br>对于50%的数据n,k&lt;=1000.<br>对于70%的数据，n,k&lt;=10^6.<br>对于100%的数据，0&lt;n,k&lt;=10^9,&nbsp;且n&gt;=3.From&nbsp;-&nbsp;This_poet<br>Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<br>This_poet's&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com 
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
<tr><td>3 3</td><td>6
</td></tr></table>
