# 

 
 # 题目描述 
<p>
一个长度为n的记账单，+表示存￥1，-表示取￥1。<br>现在发现记账单有问题。<br>一开始本来已经存了￥p，并且知道最后账户上还有￥q。<br>你要把记账单修改正确，使得<br>1：账户永远不会出现负数；<br>2：最后账户上还有￥q。<br>你有2种操作：<br>1：对某一位取反，耗时x；<br>2：把最后一位移到第一位，耗时y。<br></p> 

 
 # 输入格式 
<p>
The first line contains 5 integers n, p, q, x and y (1  n  1000000, 0  p;q  1000000, 1  x;y  1000),<br>separated by single spaces and denoting respectively: the number of transactions done by Byteasar, initial<br>and final account balance and the number of seconds needed to perform a single turn (change of sign) and<br>move of transaction to the beginning. The second line contains a sequence of n signs (each a plus or a minus),<br>with no spaces in-between.<br><br>1 ≤ n ≤ 1000000, 0 ≤ p ,q ≤ 1000000, 1 ≤x,y ≤ 1000)</p> 

 
 # 输出格式 
<p>
修改消耗的时间</p> 
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
<tr><td>9 2 3 2 1
---++++++</td><td>
3</td></tr></table>
