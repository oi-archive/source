# 

 
 # 题目描述 
<p>
Farmer John有一个过时的打谷机（收割小麦），它需要带子来带动。发动机驱动轮1总是顺时针旋转的，用来带动转轮2，转轮2来带动转轮3，等等。一共有n（2<=n<=1000）个转轮（n-1条带子）。<br>上面的图解描述了转轮的两种连接方式，第一种方式使得两个轮子旋转的方向相同，第二种则相反。<br><br>给出一串带子的信息：<br><br>*Si—驱动轮<br><br>*Di—被动轮<br><br>*Ci—连接的类型（0=直接连接，1=交叉连接）<br><br>不幸的是，列出的信息是随即的。<br><br><br>作为样例，考虑上面的图解，n=4，转轮1是驱动轮，可以得知最后转轮4是逆时针旋转的。<br><br><br></p> 

 
 # 输入格式 
<p>
*第一行：一个数n<br><br>*第二行到第n行：每一行有三个被空格隔开的数：Si，Di，Ci<br><br></p> 

 
 # 输出格式 
<p>
*第一行：一个单独的数，表示第n个转轮的方向，0表示顺时针，1表示逆时针。<br></p> 
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
2 3 0
3 4 1
1 2 0

</td><td>1</td></tr></table>
