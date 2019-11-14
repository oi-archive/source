# 

 
 # 题目描述 
<p>
哥斯拉的梦想是成为怪兽中的人气天王！在N（1 <= N <= 10,000）只怪兽中，给出M（1 <= M <= 50,000）对关系（A，B），表示怪兽A认为怪兽B是受欢迎的。由于人气是传递的，如果A认为B是受欢迎的，B认为C是受欢迎的，那么A也会认为C是受欢迎的，即使没有给出关系（A，C）。你的任务是计算出受其他所有怪兽欢迎的人气怪兽的数量。 </p> 

 
 # 输入格式 
<p>
*第1行：两个空格分隔的整数 N 和 M。<br>*第2 .. 1 + M行：两个用空格分隔的数字A和B，这意味着，A 认为 B 是流行的。<br></p> 

 
 # 输出格式 
<p>
*第1行：一个整数，人气怪兽的数量。 </p> 

 
 # 提示 
<p>
3号怪兽是唯一的人气怪兽。</p> 
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
<tr><td>3 3
1 2
2 1
2 3
</td><td>1</td></tr></table>
