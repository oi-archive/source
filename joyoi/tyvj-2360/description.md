# 

 
 # 题目描述 
<p>
小Y发现，数学中有一个很有趣的式子： <br>X^Y mod Z = K <br>给出X、Y、Z，我们都知道如何很快的计算K。但是如果给出X、Z、K，你是否知道如何快速的计算Y呢？ <br><br><br></p> 

 
 # 输入格式 
<p>
本题由多组数据（不超过20组），每组测试数据包含一行三个整数X、Z、K（0 <= X, Z, K <= 109）。 <br>输入文件一行由三个空格隔开的0结尾。 <br></p> 

 
 # 输出格式 
<p>
对于每组数据：如果无解则输出一行No Solution，否则输出一行一个整数Y(0 <= Y < Z)，使得其满足XY mod Z = K，如果有多个解输出最小的一个Y。 <br></p> 
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
<tr><td>5 58 33
2 4 3
0 0 0
</td><td>9
No Solution</td></tr></table>
