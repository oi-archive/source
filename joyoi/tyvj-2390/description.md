# 

 
 # 题目描述 
<p>
一个串是有限个小写字符的序列,特别的,一个空序列也可以是一个串. 一个串P是串A的前缀, 当且仅当存在串B, 使得 A = PB. 如果 P A 并且 P 不是一个空串,那么我们说 P 是A的一个proper前缀. 

 
 # 输入格式 
<p>
第一行一个整数 k ( 1 k 1 000 000) 表示串的长度. 接下来一行表示给出的串. 

 
 # 输出格式 
<p>
输出一个整数表示它所有前缀的最大周期长度之和. 
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
<tr><td>8
babababa
</td><td>24