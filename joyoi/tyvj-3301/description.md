# 

 
 # 题目描述 
<p>
Problem 3 : minval<br>最小函数值<br><br>问题描述：<br>　　有n个函数，分别为F1,F2,...,Fn。定义Fi(x)=Ai*x^2+Bi*x+Ci(x∈N*)。给定这些Ai、Bi和Ci，请求出所有函数的所有函数值中最小的m个（如有重复的要输出多个）。<br><br></p> 

 
 # 输入格式 
<p>
　　第一行输入两个正整数n和m。（数据范围：n , m < = 10000）<br>　　以下n行每行三个正整数，其中第i行的三个数分别位Ai、Bi和Ci。输入数据保证Ai <= 10，Bi <= 100，Ci <= 10 000。<br><br></p> 

 
 # 输出格式 
<p>
　　输出将这n个函数所有可以生成的函数值排序后的前m个元素。<br>　　这m个数应该输出到一行，用空格隔开。<br><br></p> 
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
<tr><td>样例输入
3 10
4 5 3
3 4 5
1 7 1

</td><td>样例输出
9 12 12 19 25 29 31 44 45 54
</td></tr></table>
