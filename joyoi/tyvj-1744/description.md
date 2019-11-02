# 

 
 # 题目背景 
BY&nbsp;绝恋Love枫<BR>其实还有加强版的！！<BR> 

 
 # 题目描述 
给定一个数字序列，求它的逆序对数，之后m条询问，格式为“A&nbsp;B”，表示假如把A位置的数改成B，逆序对数又是多少。注意是“假如”，也就是说，在处理完一条询问后，序列又恢复初始序列。<BR> 

 
 # 输入格式 
第一行两个正整数m，n。<BR>第二行有n个正整数，用空格隔开。<BR>第三行到第m+2行，每行两个整数A,B,用空格隔开。<BR> 

 
 # 输出格式 
共m+1行，第一行为初始序列的逆序对数，接下来的m行分别对应每一条询问的新逆序对数。 

 
 # 提示 
n&lt;=100000<BR>m&lt;=100000<BR>序列的每一元素&lt;=500000<BR>保证询问合法。<BR> 
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
<tr><td>5 2
1 2 3 4 5
1 5
4 2

</td><td>0
3
1
</td></tr></table>
