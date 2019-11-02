# 

 
 # 题目描述 
<p>
某日精灵王在精灵学校上课的时候布置了如下作业：<br>在所有不大于30000的自然数范围内讨论一个问题：已知n条线段，把端点依次输入给你，然后有m(≤30000 )个询问，每个询问输入一个点，要求这个点在多少条线段上出现过。<br>你也做一下吧！<br></p> 

 
 # 输入格式 
<p>
第1行：两个整数N（1≤n≤100000 ），表示线段数量；M(≤30000)，表示询问的次数。 <br>第2..N+1行：每条线段的起始位置S和结束位置T（1≤S,T≤100000 ）。<br>第N+2行：包括M个整数，每个整数间用空格隔开，表示每次询问点的位置。<br></p> 

 
 # 输出格式 
<p>
第1…M+1行：每行一个整数，对应每个询问点在所有线段中出现的次数。</p> 
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
2 5
4 6
1 7
2 4 7
</td><td>2
3
1</td></tr></table>
