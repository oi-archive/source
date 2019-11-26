# 

 
 # 题目描述 
<p>
FGD正在破解一段密码，他需要回答很多类似的问题：对于给定的整数a,b和d，有多少正整数对x,y，满足x<=a，y<=b，并且gcd(x,y)=d。<br>作为FGD的同学，FGD希望得到你的帮助。<br><br></p> 

 
 # 输入格式 
<p>
第一行包含一个正整数n，表示一共有n组询问。（1<=n<=	50000）<br>接下来n行，每行表示一个询问，每行三个正整数，分别为a,b,d。（1<=d<=a,b<=50000）<br><br></p> 

 
 # 输出格式 
<p>
对于每组询问，输出到输出文件zap.out一个正整数，表示满足条件的整数对数。<br><br></p> 

 
 # 提示 
<p>
对于第一组询问，满足条件的整数对有(2,2)，（2,4），（4，2）。<br>对于第二组询问，满足条件的整数对有（6,3），（3,3）。<br></p> 
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
4 5 2
6 4 3

</td><td>3
2
</td></tr></table>
