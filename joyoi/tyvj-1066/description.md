# 

 
 # 题目背景 
NOIP2004&nbsp;提高组&nbsp;第二道 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;在一个果园里，多多已经将所有的果子打了下来，而且按果子的不同种类分成了不同的堆。多多决定把所有的果子合成一堆。&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;每一次合并，多多可以把两堆果子合并到一起，消耗的体力等于两堆果子的重量之和。可以看出，所有的果子经过n-1次合并之后，就只剩下一堆了。多多在合并果子时总共消耗的体力等于每次合并所耗体力之和。&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;因为还要花大力气把这些果子搬回家，所以多多在合并果子时要尽可能地节省体力。假定每个果子重量都为1，并且已知果子的种类数和每种果子的数目，你的任务是设计出合并的次序方案，使多多耗费的体力最少，并输出这个最小的体力耗费值。&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;例如有3种果子，数目依次为1，2，9。可以先将1、2堆合并，新堆数目为3，耗费体力为3。接着，将新堆与原先的第三堆合并，又得到新的堆，数目为12，耗费体力为12。所以多多总共耗费体力=3+12=15。可以证明15为最小的体力耗费值。&nbsp;<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入包括两行，第一行是一个整数n(1&lt;＝n&lt;=10000)，表示果子的种类数。第二行包含n个整数，用空格分隔，第i个整数ai(1&lt;＝ai&lt;=20000)是第i种果子的数目。&nbsp; 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出包括一行，这一行只包含一个整数，也就是最小的体力耗费值。输入数据保证这个值小于2^31。&nbsp;<BR><BR> 

 
 # 提示 
对于30％的数据，保证有n&lt;=1000：&nbsp;<BR>对于50％的数据，保证有n&lt;=5000；&nbsp;<BR>对于全部的数据，保证有n&lt;=10000。&nbsp; 
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
<tr><td>3 
1 2 9 
</td><td>15</td></tr></table>
