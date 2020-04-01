# 

 
 # 题目描述 
<p>
一个串是有限个小写字符的序列,特别的,一个空序列也可以是一个串. 一个串P是串A的前缀, 当且仅当存在串B, 使得 A = PB. 如果 P A 并且 P 不是一个空串,那么我们说 P 是A的一个proper前缀. <br>定义Q 是A的周期, 当且仅当Q是A的一个proper 前缀并且A是QQ的前缀(不一定要是proper前缀). 比如串 abab 和 ababab 都是串abababa的周期. 串A的最大周期就是它最长的一个周期或者是一个空串(当A没有周期的时候), 比如说, ababab的最大周期是abab. 串abc的最大周期是空串. 给出一个串,求出它所有前缀的最大周期长度之和.<br></p> 

 
 # 输入格式 
<p>
第一行一个整数 k ( 1 k 1 000 000) 表示串的长度. 接下来一行表示给出的串. <br></p> 

 
 # 输出格式 
<p>
输出一个整数表示它所有前缀的最大周期长度之和. <br></p> 
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
</td><td>24</td></tr></table>
