# 

 
 # 题目描述 
<p>
It's Bessie's birthday and time for party games! Bessie has instructed<br>the N (1 <= N <= 100,000) cows conveniently numbered 1..N to sit<br>in a circle (so that cow i [except at the ends] sits next to cows<br>i-1 and i+1; cow N sits next to cow 1). Meanwhile, Farmer John fills<br>a barrel with one billion slips of paper, each containing some<br>integer in the range 1..1,000,000.<br><br>Each cow i then draws a number A_i (1 <= A_i <= 1,000,000) (which<br>is not necessarily unique, of course) from the giant barrel.  Taking<br>turns, each cow i then takes a walk around the circle and pats the<br>heads of all other cows j such that her number A_i is exactly<br>divisible by cow j's number A_j; she then sits again back in her<br>original position.<br><br>The cows would like you to help them determine, for each cow, the<br>number of other cows she should pat.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: A single integer: N<br><br>* Lines 2..N+1: Line i+1 contains a single integer: A_i<br><br></p> 

 
 # 输出格式 
<p>
* Lines 1..N: On line i, print a single integer that is the number of<br>        other cows patted by cow i.<br><br></p> 
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
<tr><td>5  //有五个数,对于任一个数来说,其它的数有多少个是它的约数
2 
1
2
3
4

INPUT DETAILS:

The 5 cows are given the numbers 2, 1, 2, 3, and 4, respectively.

</td><td>2
0
2
1
3

OUTPUT DETAILS:

The first cow pats the second and third cows; the second cows pats no cows;
etc.</td></tr></table>
