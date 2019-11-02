# 

 
 # 题目描述 
<p>
n列火车，每条有l节车厢。每节车厢有一种颜色（用小写字母表示）。<br>有m次车厢交换操作。<br>求：对于每列火车，在交换车厢的某个时刻，与其颜色完全相同的火车最多有多少。<br></p> 

 
 # 输入格式 
<p>
n l m (2 ≤ n ≤ 1000, 1 ≤ l ≤ 100, 0 ≤ m ≤ 100000)<br>n行字符串，长度为l<br>m行，每行4个数a b c d,a车的第b个字符与c车第d个字符交换。<br></p> 

 
 # 输出格式 
<p>
n个数，在交换车厢的某个时刻，与该车颜色完全相同的火车最多数目。</p> 
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
<tr><td>5 6 7
ababbd
abbbbd
aaabad
caabbd
cabaad
2 3 5 4
5 3 5 5
3 5 2 2
1 2 4 3
2 2 5 1
1 1 3 3
4 1 5 6
</td><td>
3
3
3
2
3
</td></tr></table>
