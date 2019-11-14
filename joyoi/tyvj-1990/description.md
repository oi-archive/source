# 

 
 # 题目描述 
自从Freda城堡的密码被你轻松破解之后，Freda一直在思考着如何确定一个更难的密码&gt;.&lt;<br>找啊找啊找密码，找到一个好密码~<br>由于Fibonacci数的神奇性质，所以Freda自然而然想到了：Fibonacci数！<br>首先，我们约定Fibonacci[0]&nbsp;=&nbsp;1,&nbsp;Fibonacci[1]&nbsp;=&nbsp;1,&nbsp;Fibonacci[2]&nbsp;=&nbsp;2.<br>Fibonacci[n]&nbsp;=&nbsp;Fibonacci[n-1]&nbsp;+&nbsp;Fibonacci[n-2]&nbsp;(n&gt;=2)<br>这次，Freda的密码规则是这样的&gt;.&lt;<br>对于每扇门，给出一个数字A，如果数字A不是Fibonacci数字，那么这扇门的密码是"lala"（不含引号）。<br>否则，如果能够找到一个k使得A=Fibonacci[k]，这扇门的密码就是k.<br><br> 

 
 # 输入格式 
第一行一个整数T，表示Freda城堡的门的总数。<br>接下来T行每行一个整数A，表示每扇门上给出的数字。<br><br> 

 
 # 输出格式 
输出T行，对于每扇门给出的整数，输出这扇门对应的密码。<br><br> 

 
 # 提示 
A&nbsp;&lt;=&nbsp;10^30000<br>T&nbsp;&lt;=&nbsp;50<br>2&lt;=答案中所有数字&lt;=100000<br><br>This_poet原创&gt;_&lt;<br>Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<br>This_poet's&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com<br><br> 
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
4
3

</td><td>lala
3

</td></tr></table>
