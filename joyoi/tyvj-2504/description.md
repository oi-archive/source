# 

 
 # 题目描述 
<p>
<br>考虑一个 N x N (1 <= N <= 100)的有1个个方格组成的正方形牧场。有些方格是奶牛们不能踏上的，它们被标记为了'x'。例如下图： <br><br>. . B x .<br>. x x A .<br>. . . x .<br>. x . . .<br>. . x . .<br>贝茜发现自己恰好在点A处，她想去B处的盐块舔盐。缓慢而且笨拙的动物，比如奶牛，十分讨厌转弯。尽管如此，当然在必要的时候她们还是会转弯的。对于一个给定的牧场，请你计算从A到B最少的转弯次数。开始的时候，贝茜可以使面对任意一个方向。贝茜知道她一定可以到达。 <br></p> 

 
 # 输入格式 
<p>
行 1: 一个整数 N <br>行 2..N + 1: 行 i+1 有 N 个字符 ('.', 'x', 'A', 'B')，表示每个点的状态。 <br></p> 

 
 # 输出格式 
<p>
行 1: 一个整数，最少的转弯次数。 <br></p> 
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
<tr><td>3
.xA
...
Bx.
</td><td>
2</td></tr></table>
