# 

 
 # 题目描述 
<p>
给定一个长度为n的不下降（即第i个数字大于等于第i-1个数字）整数序列a1 , a2 , ... , an，以及若干询问。每个询问包含数字i和j=(1 ≤ i ≤ j ≤ n)。对于每个询问，请你回答在 ai , ... , aj 内出现最多的数字一共出现了多少次。</p> 

 
 # 输入格式 
<p>
输入数据有多组。<br>每组数据第一行为两个整数n和q(1 ≤ n, q ≤ 100000)。下一行是n个用空格分开的整数 a1 , ... , an (-100000 ≤ ai ≤ 100000, for each i ∈ {1, ..., n}) 。你可以假设 for each i ∈ {1, ..., n-1}: ai ≤ ai+1。接下来q行，每行包含两个整数i和j(1 ≤ i ≤ j ≤ n), 表示询问区间的两个边界。<br>最后一组数据只包含一个0。<br></p> 

 
 # 输出格式 
<p>
对于每个询问，输出一行，表示在给定区间范围内出现最多的整数出现的次数。</p> 
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
<tr><td>10 3
-1 -1 1 1 1 1 3 10 10 10
2 3
1 10
5 10
0</td><td>1
4
3</td></tr></table>
