# 

 
 # 题目描述 
<p>
每一头牛的愿望就是变成一头最受欢迎的牛。现在有N头牛，给你M对整数(A,B)，表示牛A认为牛B受欢迎。<br>这种关系是具有传递性的，如果A认为B受欢迎，B认为C受欢迎，那么牛A也认为牛C受欢迎。你的任务是求出有多少头牛被所有的牛认为是受欢迎的。<br><br></p> 

 
 # 输入格式 
<p>
第一行两个数N,M。<br>接下来M行，每行两个数A,B，意思是A认为B是受欢迎的（给出的信息有可能重复，即有可能出现多个A,B）<br></p> 

 
 # 输出格式 
<p>
一个数，即有多少头牛被所有的牛认为是受欢迎的。<br><br></p> 
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
<tr><td>3 3
1 2
2 1
2 3
</td><td>1

【数据范围】
10%的数据N<=20, M<=50
30%的数据N<=1000,M<=20000
70%的数据N<=5000,M<=50000
100%的数据N<=10000,M<=50000</td></tr></table>
