# 

 
 # 题目背景 
N&nbsp;只小猫来到了Freda&nbsp;的城堡做客！Freda&nbsp;很高兴，拿出了蛋糕和饼干来招待它们，每一只小猫都可以吃到蛋糕或者饼干，当然，每只小猫具体拿到的是蛋糕还是饼干是由Freda&nbsp;决定的。<br> 

 
 # 题目描述 
小猫们看到蛋糕比饼干大之后，普遍认为蛋糕比饼干要好&gt;.&lt;。所以，如果Freda&nbsp;给了第i&nbsp;只小猫蛋糕且这个小猫是第一个吃到蛋糕的，那么就必须给第i+2,i+4,i+6......只小猫蛋糕。<br>也就是说，如果存在正整数i,满足：<br>1、对于所有的0&lt;j&lt;i,第j&nbsp;只小猫吃到的是饼干<br>2、第i&nbsp;只小猫吃到的是蛋糕<br>那么就必须有：<br>对于所有的i&lt;k&lt;=N,&nbsp;k&nbsp;mod&nbsp;2&nbsp;=&nbsp;i&nbsp;mod&nbsp;2,第k&nbsp;只小猫吃到的是蛋糕。<br>小猫的数目一多，Freda&nbsp;就忙不过来了。请你帮忙计算，Freda&nbsp;一共有多少种可能的方法来招待这N&nbsp;只小猫？<br> 

 
 # 输入格式 
一个整数N，表示小猫的数目。<br> 

 
 # 输出格式 
输出一个整数，表示freda招待这N&nbsp;只小猫的方法数。<br>由于这个数可能很大，你只需要输出它mod&nbsp;1000000007&nbsp;的值。<br> 

 
 # 提示 
对于30%的数据，N&lt;=20<br>对于60%的数据，N&lt;=100000<br>对于100%的数据，0&lt;N&lt;=10^9<br><br>样例解释<br>D&nbsp;表示蛋糕，B&nbsp;表示饼干，Freda&nbsp;共有如下10&nbsp;种可能的招待方法。<br>BBBB&nbsp;BBBD&nbsp;BBDB&nbsp;BBDD&nbsp;BDBD<br>BDDD&nbsp;DBDB&nbsp;DBDD&nbsp;DDDB&nbsp;DDDD<br> 
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
</td><td>10
</td></tr></table>
