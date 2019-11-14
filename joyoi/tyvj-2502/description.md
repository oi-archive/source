# 

 
 # 题目描述 
<p>
贝茜是一只非常努力工作的奶牛，她总是专注于提高自己的产量。为了产更多的奶，她预计好了接下来的N (1 ≤ N ≤ 1,000,000)个小时，标记为0..N-1。 <br><br>Farmer John 计划好了 M (1 ≤ M ≤ 1,000) 个可以挤奶的时间段。每个时间段有一个开始时间(0 ≤ 开始时间 ≤ N), 和一个结束时间 (开始时间 < 结束时间 ≤ N), 和一个产量 (1 ≤ 产量 ≤ 1,000,000) 表示可以从贝茜挤奶的数量。Farmer John 从分别从开始时间挤奶，到结束时间为止。每次挤奶必须使用整个时间段。 <br><br>但即使是贝茜也有她的产量限制。每次挤奶以后，她必须休息 R (1 ≤ R ≤ N) 个小时才能下次挤奶。给定Farmer John 计划的时间段，请你算出在 N 个小时内，最大的挤奶的量。 <br><br></p> 

 
 # 输入格式 
<p>
第 1 行: 三个整数 N, M, R <br>第 2..M+1 行: 第 i+1 行 每行三个整数，为 <br></p> 

 
 # 输出格式 
<p>
第 1 行:一个整数 在 N 个小时内，最大的挤奶的量Farmer John放入挤奶计划，开始时间，结束时间，产量。 <br></p> 

 
 # 提示 
<p>
注意：结束时间不挤奶</p> 
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
<tr><td>12 4 2
1 2 8
10 12 19
3 6 24
7 10 31
</td><td>43</td></tr></table>
