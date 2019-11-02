# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;一个编码方案把每个字符对应到一个&nbsp;01&nbsp;串。例如{1,1010,01,10101}就是一<BR>个编码方案，它把四个字符（假设它们为a,b,c,d）分别对应到串1、1010，01，<BR>10101。字符串的编码为各字符编码的连接。例如，在刚才的编码方案中，字符<BR>串cac的编码为01101，dcb的编码为10101011010。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;进一步分析发现，刚才的编码是相当劣质的，因为字符串&nbsp;ba,&nbsp;&nbsp;acc&nbsp;和&nbsp;d&nbsp;的编<BR>码都是10101。对于一个编码方案，你的任务是找出三个不同的字符串，使得它<BR>们的编码全相同。换句话说，找一个&nbsp;01&nbsp;编码串，使得它至少有三种解码方式。<BR>如果有多组解，这个编码串应当尽量短。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行包含一个整数n，即符号的个数。以下n行每行为一个长度不超过50<BR>的01串（可能为空串）&nbsp;，即各符号的编码 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;仅一行，包含一个整数，即最短编码的长度。如果无解，输出-1。 

 
 # 提示 
2&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;50SCOI2008&nbsp;day2&nbsp;T3 
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
<tr><td>样例1：
4 
1 
1010 
01 
10101 

样例2：

2 
0 
1

样例3：

7 
00011011 
000110 
11 
0001 
1011 
00 
011011</td><td>样例1：

5

样例2：

-1

样例3：

8</td></tr></table>
