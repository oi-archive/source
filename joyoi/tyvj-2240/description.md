# 

 
 # 题目描述 
<p>
一棵n个点的带权有根树，有p个询问，每次询问树中是否存在一条长度为Len的路径，如果是，输出Yes否输出No. <br></p> 

 
 # 输入格式 
<p>
第一行两个整数n, p分别表示点的个数和询问的个数． <br>接下来n-1行每行三个数x, y, c，表示有一条树边x→y，长度为c． <br>接下来p行每行一个数Len，表示询问树中是否存在一条长度为Len的路径． <br><br></p> 

 
 # 输出格式 
<p>
输出有p行，Yes或No. <br></p> 

 
 # 提示 
<p>
30%的数据，n≤100． <br>100%的数据，n≤10000，p≤100，长度≤1000000． <br><br>做完此题可看下POJ 3237 Tree</p> 
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
<tr><td>6 4 
1 2 5 
1 3 7 
1 4 1 
3 5 2 
3 6 3 
1 
8 
13 
14 
</td><td>
Yes 
Yes 
No 
Yes 


</td></tr></table>
