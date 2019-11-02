# 
Description
请考虑一个由1到N（N=3, 4, 5 ... 9）的数字组成的递增数列：1 2 3 ... N。 现在请在数列中插入“+”表示加，或者“-”表示减，抑或是“ ”表示空白(例如1-2 3就等于1-23)，来将每一对数字组合在一起（请不在第一个数字前插入符号）。 计算该表达式的结果并注意你是否得到了和为零。 请你写一个程序找出所有产生和为零的长度为N的数列。
 
Input
单独的一行表示整数N (3 <= N <= 9)。

Output
按照ASCII码的顺序，输出所有在每对数字间插入“+”, “-”, 或 “ ”后能得到和为零的数列。# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>7</td><td>1+2-3+4-5-6+7
1+2-3-4+5+6-7
1-2 3+4+5+6+7
1-2 3-4 5+6 7
1-2+3+4-5+6-7
1-2-3-4-5+6+7
</td></tr></table>
