# 

 
 # 题目描述 
<p>
 在一个虚拟网络中传输一个n比特非负整数.各比特从左到右传输,第i个比特的发送时间为i.每个比特的网络延迟总是为1到d+1之间的实数（因此从左到右第i个比特的到达时间为i+1到i+d+1之间）.若同时有个多个比特到达,实际收到的顺序任意.求实际收到的整数有多少种,以及第K大的那个数是多少</p> 

 
 # 输入格式 
<p>
第一行输入 n , d , k<br>第二行输入那个N位的数字,用二进制表示<br></p> 

 
 # 输出格式 
<p>
输出 分别输出受到整数的种数(将结果Mod 100,000,000)，和这些整数第K小的那个</p> 
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
<tr><td>4 1 3
0110
</td><td>4
1001</td></tr></table>
