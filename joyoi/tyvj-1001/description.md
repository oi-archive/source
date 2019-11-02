# 

 
 # 题目背景 
成成第一次模拟赛&nbsp;第一道 

 
 # 题目描述 
给定一个长度为N(0&lt;n&lt;=10000)的序列，保证每一个序列中的数字a[i]是小于maxlongint的非负整数&nbsp;，编程要求求出整个序列中第k大的数字减去第k小的数字的值m，并判断m是否为质数。(0&lt;k&lt;=n) 

 
 # 输入格式 
输入格式：<BR>第一行为2个数n，k（含义如上题）<BR>第二行为n个数，表示这个序列<BR> 

 
 # 输出格式 
输出格式：<BR>如果m为质数则<BR>第一行为'YES'(没有引号）<BR>第二行为这个数m<BR>否则&nbsp;<BR>第一行为'NO'<BR>第二行为这个数m 

 
 # 提示 
对于第K大的详细解释:<BR>如果一个序列为1&nbsp;2&nbsp;2&nbsp;2&nbsp;2&nbsp;3<BR>第1大&nbsp;为3<BR>第2大&nbsp;为2<BR>第3大&nbsp;为2<BR>第4大&nbsp;为2<BR>第5大&nbsp;为1<BR>第K小与上例相反<BR><BR>另外需要注意的是<BR>最小的质数是2,如果小于2的话,请直接输出NO<BR><BR>原创…… 
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
1 2 3 4 5</td><td>YES
2</td></tr></table>
