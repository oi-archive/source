# 

 
 # 题目描述 
<p>
初始时滑冰俱乐部有1到n号的溜冰鞋各k双。已知x号脚的人可以穿x到x+d的溜冰鞋。<br><br>有m次操作，每次包含两个数ri，xi代表来了xi个ri号脚的人。xi为负，则代表走了这么多人。<br><br>对于每次操作，输出溜冰鞋是否足够。<br><br> <br><br></p> 

 
 # 输入格式 
<p>
n m k d    (  1≤n≤200,000  ， 1≤m≤500,000  ，  1≤k≤109  ， 0≤d≤n  )<br><br>ri xi     （ 1≤i≤m， 1≤ri≤n-d ，  |xi|≤109  ）<br><br> <br><br></p> 

 
 # 输出格式 
<p>
对于每个操作，输出一行，TAK表示够 NIE表示不够。<br><br><br></p> 
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
<tr><td>4 4 2 1

1 3

2 3

3 3

2 -1
</td><td>
TAK

TAK

NIE

TAK
</td></tr></table>
