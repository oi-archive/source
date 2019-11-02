# 

 
 # 题目背景 
NOIP&nbsp;2012&nbsp;普及组&nbsp;题3 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;小明的花店新开张，为了吸引顾客，他想在花店的门口摆上一排花，共&nbsp;m&nbsp;盆。通过调&nbsp;查顾客的喜好，小明列出了顾客最喜欢的&nbsp;n&nbsp;种花，从&nbsp;1&nbsp;到&nbsp;n&nbsp;标号。为了在门口展出更多种花，&nbsp;规定第&nbsp;i&nbsp;种花不能超过&nbsp;ai&nbsp;盆，摆花时同一种花放在一起，且不同种类的花需按标号的从小到&nbsp;大的顺序依次摆列。<br><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;试编程计算，一共有多少种不同的摆花方案。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第一行包含两个正整数&nbsp;n&nbsp;和&nbsp;m，中间用一个空格隔开。<br><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第二行有&nbsp;n&nbsp;个整数，每两个整数之间用一个空格隔开，依次表示&nbsp;a1、a2、……an。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输出只有一行，一个整数，表示有多少种方案。注意：因为方案数可能很多，请输出&nbsp;方案数对&nbsp;1000007&nbsp;取模的结果。 

 
 # 提示 
【输入输出样例说明】<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;有&nbsp;2&nbsp;种摆花的方案，分别是(1，1，1，2)，&nbsp;(1，1，2，2)。括号里的&nbsp;1&nbsp;和&nbsp;2&nbsp;表示两种花，比如第一个方案是前三个位置摆第一种花，第四个位置摆第二种花。<br><br>【数据范围】<br><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;对于&nbsp;20%数据，有&nbsp;0&lt;n≤8，0&lt;m≤8，0≤ai≤8；&nbsp;对于&nbsp;50%数据，有&nbsp;0&lt;n≤20，0&lt;m≤20，0≤ai≤20；<br><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;对于&nbsp;100%数据，有&nbsp;0&lt;n≤100，0&lt;m≤100，0≤&nbsp;ai≤100。NOIP&nbsp;2012 
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
<tr><td>2 4
3 2</td><td>2</td></tr></table>
