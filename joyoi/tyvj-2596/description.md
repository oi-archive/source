# 

 
 # 题目描述 
<p>
  给一个p*q*r的立方体，它由p*q*r个1*1*1的小立方体构成。每个立方体要么被虫蛀，要么不被。现在郑爽要选出一个a*a*b的立方体，使得它没有被虫蛀过，并且4*a*b最大。<br><br></p> 

 
 # 输入格式 
<p>
  第一行是p,q,r <= 150。<br>  以下p*q行，每行r个字符。(x,y,z)这个格子，出现在输入的第1 + (y * p + x - p)行的第z个字符。 N代表未被虫蛀，P代表被虫蛀了。<br></p> 

 
 # 输出格式 
<p>
  仅一行，代表郑爽需要的最大的4ab<br><br></p> 
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
<tr><td>
3 2 5
PNNNN
PNNNN
NPPNP
PNNNP
NNNNP
PPNNP
</td><td>24</td></tr></table>
