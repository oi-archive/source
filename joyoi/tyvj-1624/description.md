# 

 
 # 题目描述 
有一种机器，只有两个寄存器X和Y。初始两个寄存器都是1。有两种操作（括号中的是操作名称）：<BR>[X]X:=X+Y<BR>[Y]Y:=X+Y<BR>可以看出，每种操作都是将两个寄存器相加存入其中一个。一个程序就是由X和Y组成的字符串，表示依次做这两种操作。现在给一个r表示你需要寻找一个最短的程序使得在程序结束时，X寄存器中存着r，Y寄存器中可以储存任意数。如果有多解，输出字典序最小的答案。<BR> 

 
 # 输入格式 
一个整数r。 

 
 # 输出格式 
一行字符串，表示最短的程序。 

 
 # 提示 
对于20%的数据，r&lt;=100。<BR>对于50%的数据，r&lt;=10000。<BR>对于100%的数据，2&lt;=r&lt;=1000000。 
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
<tr><td>//样例输入1
10
//样例输入2
20</td><td>样例输出1
XXYYX
样例输出2
XYYYYXX</td></tr></table>
