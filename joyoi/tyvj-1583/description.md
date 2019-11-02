# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;农夫栋栋近年收入不景气，正在他发愁如何能多赚点钱时，他听到隔壁的小朋友在讨论兔子繁殖的问题。&nbsp;<BR>&nbsp;&nbsp;&nbsp;问题是这样的：第一个月初有一对刚出生的小兔子，经过两个月长大后，这对兔子从第三个月开始，每个月初生一对小兔子。新出生的小兔子生长两个月后又能每个月生出一对小兔子。问第n个月有多少只兔子？<BR>&nbsp;&nbsp;&nbsp;聪明的你可能已经发现，第n个月的兔子数正好是第n个Fibonacci(斐波那契)数。栋栋不懂什么是Fibonacci数，但他也发现了规律：第i+2个月的兔子数等于第i个月的兔子数加上第i+1个月的兔子数。前几个月的兔子数依次为：<BR>&nbsp;1&nbsp;1&nbsp;2&nbsp;3&nbsp;5&nbsp;8&nbsp;13&nbsp;21&nbsp;34&nbsp;…&nbsp;<BR>&nbsp;&nbsp;&nbsp;栋栋发现越到后面兔子数增长的越快，期待养兔子一定能赚大钱，于是栋栋在第一个月初买了一对小兔子开始饲养。&nbsp;<BR>&nbsp;&nbsp;&nbsp;每天，栋栋都要给兔子们喂食，兔子们吃食时非常特别，总是每k对兔子围成一圈，最后剩下的不足k对的围成一圈，由于兔子特别害怕孤独，从第三个月开始，如果吃食时围成某一个圈的只有一对兔子，这对兔子就会很快死掉。<BR>&nbsp;&nbsp;&nbsp;我们假设死去的总是刚出生的兔子，那么每个月的兔子数仍然是可以计算的。例如，当k=7时，前几个月的兔子数依次为：<BR>&nbsp;&nbsp;1&nbsp;1&nbsp;2&nbsp;3&nbsp;5&nbsp;7&nbsp;12&nbsp;19&nbsp;31&nbsp;49&nbsp;80&nbsp;…&nbsp;<BR>&nbsp;&nbsp;给定n，你能帮助栋栋计算第n个月他有多少对兔子么？由于答案可能非常大，你只需要告诉栋栋第n个月的兔子对数除p的余数即可。<BR> 

 
 # 输入格式 
输入一行，包含三个正整数n,&nbsp;k,&nbsp;p。 

 
 # 输出格式 
输出一行，包含一个整数，表示栋栋第n个月的兔子对数除p的余数。 
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
<tr><td>样例输入1
6 7 100

样例输入2
7 7 5
</td><td>样例输出1
7

样例输出2
2

</td></tr></table>
