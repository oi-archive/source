# 

 
 # 题目描述 
给定一列正整数a1,&nbsp;a2,&nbsp;a3,&nbsp;…,&nbsp;an，每一个数都在0&nbsp;至&nbsp;p&nbsp;–&nbsp;1之间。可以对这列数进行两种操作：<BR>添加操作：向序列后添加一个数，序列长度变成n&nbsp;+&nbsp;1。<BR>询问操作：询问这个序列中最后L个数中最大的数是多少。<BR>	程序运行的最开始，整数序列为空。写一个程序，读入操作的序列，并输出询问操作的答案。 

 
 # 输入格式 
输入文件maxnumber.in的第一行有两个正整数，m&nbsp;(1&nbsp;≤&nbsp;m&nbsp;≤&nbsp;200000&nbsp;&nbsp;)和p&nbsp;(1&nbsp;≤&nbsp;p&nbsp;≤&nbsp;2&nbsp;*&nbsp;10^9)。<BR>	在接下来的m行中，每一行表示一个操作。如果该行的内容是Q&nbsp;L，则表示这个操作是询问序列中最后L个数的最大数是多少；如果是A&nbsp;t&nbsp;(0&nbsp;≤&nbsp;t&nbsp;&lt;&nbsp;p)，则表示向序列后面加一个数，加入的数是(t&nbsp;+&nbsp;a)除以p的余数。其中，t是输入的参数，a是在这个添加操作之前最后一个询问操作的答案（如果之前没有询问操作，则a&nbsp;=&nbsp;0）。<BR>	第一个操作一定是添加操作。对于询问操作，L&nbsp;&gt;&nbsp;0且不超过当前序列的长度。 

 
 # 输出格式 
请将输出写入文件maxnumber.out。对于每一个询问操作，输出一行。该行只有一个数，即序列中最后L个数的最大数。 

 
 # 提示 
最后的序列是97、14、60、96。 
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
<tr><td>10 100
A 97
Q 1
Q 1
A 17
Q 2
A 63
Q 1
Q 1
Q 3
A 99</td><td>97
97
97
60
60
97</td></tr></table>
