# 

 
 # 题目背景 
　　　Rainbow：对了Freda，乃城堡的密码被我轻松破解~你也来试试看我城堡的密码吧~<br>　　　Freda：T_T，我蒟蒻……<br>　　　Rainbow：卖萌要自粽的说&gt;.&lt;~<br>　　　Freda：本来就是嘛T_T！…… 

 
 # 题目描述 
　　　Freda城堡的密码简直弱爆了有木有！大家来试试破解Rainbow城堡的密码吧！<br>　　　Rainbow城堡的大门上写着一个大数字N，城堡第i扇门上都有两个数字Ti，Qi。Ti表示密码的类型，Qi是一个常数。Ti只有三种可能的情况：1,2,3.	<br>　　　Ti=1时，第i扇门的密码是同时为N和Qi的约数的数的个数。<br>　　　Ti=2时，第i扇门的密码是同时为N的约数和Qi的倍数的数的个数。<br>　　　Ti=3时，第i扇门的密码是N的约数当中不能被Qi整除的数的个数。<br>　　　Rainbow的城堡实在是太复杂了，有P扇门之多……Freda想请你帮忙破解Rainbow城堡每扇门的密码~ 

 
 # 输入格式 
　　　第一行两个整数N，P.分别表示Rainbow城堡大门上的数字以及城堡当中门的数目。<br>　　　接下来P行每行两个整数，第i+1行两个整数Ti，Qi，Ti表示第i扇门的密码类型，Qi表示第i扇门上的数字。 

 
 # 输出格式 
输出P行，每行一个整数，第i行的整数表示第i扇门的密码。 

 
 # 提示 
对于30%的数据，N&lt;=10^3,&nbsp;P&lt;=1000,&nbsp;Qi&lt;=10^3<br>对于50%的数据，N&lt;=10^9,&nbsp;P&lt;=20000,&nbsp;Qi&lt;=10^9<br>对于100%的数据，N&lt;=10^15,&nbsp;P&lt;=200000,&nbsp;Qi&lt;=10^15,&nbsp;Ti=1,2or3.From&nbsp;-&nbsp;This_poet<br>Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<br>This_poet's&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com 
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
<tr><td>12 6
1 6
1 14
2 4
2 3
3 12
3 14</td><td>4
2
2
3
5
6</td></tr></table>
