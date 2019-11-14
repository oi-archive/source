# 

 
 # 题目描述 
<p>
Farmer John已经决定把水灌到他的n(1<=n<=300)块农田，农田被数字1到n标记。把一块土地进行灌水有两种方法，从其他农田饮水，或者这块土地建造水库。<br><br>建造一个水库需要花费wi(1<=wi<=100000),连接两块土地需要花费Pij(1<=pij<=100000,pij=pji,pii=0).<br><br>计算Farmer John所需的最少代价。<br><br></p> 

 
 # 输入格式 
<p>
*第一行：一个数n<br><br>*第二行到第n+1行：第i+1行含有一个数wi<br><br>*第n+2行到第2n+1行：第n+1+i行有n个被空格分开的数，第j个数代表pij。<br><br></p> 

 
 # 输出格式 
<p>
*第一行：一个单独的数代表最小代价.<br><br></p> 
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
<tr><td>4
5
4
4
3
0 2 2 2
2 0 3 3
2 3 0 4
2 3 4 0
</td><td>9


输出详解：

Farmer John在第四块土地上建立水库，然后把其他的都连向那一个，这样就要花费3+2+2+2=9</td></tr></table>
