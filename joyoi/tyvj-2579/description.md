# 

 
 # 题目描述 
<p>
Goneril is a very sleep-deprived cow. Her day is partitioned into<br>N (3 <= N <= 3,830) equal time periods but she can spend only B (2<br><= B < N) not necessarily contiguous periods in bed.  Due to her<br>bovine hormone levels, each period has its own utility U_i (0 <=<br>U_i <= 200,000), which is the amount of rest derived from sleeping<br>during that period.  These utility values are fixed and are independent<br>of what Goneril chooses to do, including when she decides to be in<br>bed.<br><br>With the help of her alarm clock, she can choose exactly which<br>periods to spend in bed and which periods to spend doing more<br>critical items such as writing papers or watching baseball. However,<br>she can only get in or out of bed on the boundaries of a period.<br><br>She wants to choose her sleeping periods to maximize the sum of the<br>utilities over the periods during which she is in bed.  Unfortunately,<br>every time she climbs in bed, she has to spend the first period<br>falling asleep and gets no sleep utility from that period.<br><br>The periods wrap around in a circle; if Goneril spends both periods<br>N and 1 in bed, then she does get sleep utility out of period 1.<br><br>What is the maximum total sleep utility Goneril can achieve?<br><br>一只牛想在N段相等的时间内选择B段睡觉。每一段时间的睡眠都会给这只牛不同程度的体力恢复。总的体力恢复值就是所有睡眠时间段的恢复值之和，但是每一次连续睡眠的第一段时间不会给牛带来任何体力恢复（它还没有睡着），而且所有N段时间形成一个环，即可以认为第(N+1)段时间就是第1段时间。 <br>给定N，B以及每段时间的体力恢复值ai，要求最大的总体力恢复值。 </p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: N and B<br><br>* Lines 2..N+1: Line i+1 contains a single integer, U_i, between 0 and<br>        200,000 inclusive<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: A single integer, the maximum total sleep utility Goneril<br>        can achieve.<br><br></p> 

 
 # 提示 
<p>
见国家队2005 Twb,ZgL作业</p> 
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
<tr><td>5 3
2
0
3
1
4

INPUT DETAILS:

The day is divided into 5 periods, with utilities 2, 0, 3, 1, 4 in that 
order. Goneril must pick 3 periods.

</td><td>6

OUTPUT DETAILS:

Goneril can get total utility 6 by being in bed during periods 4,
5, and 1, with utilities 0 [getting to sleep], 4, and 2
respectively.</td></tr></table>
