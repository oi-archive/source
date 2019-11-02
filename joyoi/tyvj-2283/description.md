# 

 
 # 题目描述 
<p>
n个灯围成一个圈。<br>每个灯可以打开或者关闭。<br>对于第i个灯，如果第i+1个灯是打开的，则它在下一秒该变其状态。对于第 n个灯的话，则看第 1个灯的状态<br>给出这些灯最开始的状态，求第M秒后的状态.</p> 

 
 # 输入格式 
<p>
第一行给出 N,M。（0<N<=10^6,0<=M<=10^9）<br>下面 n个数，非0即 1,其中 1代表是打开的 。</p> 

 
 # 输出格式 
<p>
输出 N 个数，代表M秒后每个灯的状态</p> 
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
<tr><td>3 1
0
0
1</td><td>0
1
1</td></tr></table>
