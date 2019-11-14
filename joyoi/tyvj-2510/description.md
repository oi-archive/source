# 

 
 # 题目描述 
<p>
Oh those picky N (1 <= N <= 50,000) cows! They are so picky that<br>each one will only be milked over some precise time interval A..B<br>(1 <= A <= B <= 1,000,000), which includes both times A and B.  Obviously,<br>FJ must create a reservation<br>system to determine which stall each cow can be assigned for her<br>milking time. Of course, no cow will share such a private moment<br>with other cows.<br><br>Help FJ by determining:<br>* The minimum number of stalls required in the barn so that each<br>  cow can have her private milking period<br>* An assignment of cows to these stalls over time<br><br>有N头牛,每头牛有个喝水时间,这段时间它将专用一个Stall<br>现在给出每头牛的喝水时间段,问至少要多少个Stall才能满足它们的要求</p> 

 
 # 输入格式 
<p>
* Line 1: A single integer, N<br><br>* Lines 2..N+1: Line i+1 describes cow i's milking interval with two<br>        space-separated integers.<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: The minimum number of stalls the barn must have.<br><br>* Lines 2..N+1: Line i+1 describes the stall to which cow i will be<br>        assigned for her milking period.<br><br></p> 

 
 # 提示 
<p>
不妨试下这个数据,对于按结束点SORT,再GREEDY的做法<br>1 3<br>5 7<br>6 9<br>10 11<br>8 12<br>4 13<br>正确的输出应该是3</p> 
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
<tr><td>5
1 10
2 4
3 6
5 8
4 7
</td><td>4


OUTPUT DETAILS:

Here's a graphical schedule for this output:

Time     1  2  3  4  5  6  7  8  9 10
Stall 1 c1>>>>>>>>>>>>>>>>>>>>>>>>>>>
Stall 2 .. c2>>>>>> c4>>>>>>>>> .. ..
Stall 3 .. .. c3>>>>>>>>> .. .. .. ..
Stall 4 .. .. .. c5>>>>>>>>> .. .. ..

Other outputs using the same number of stalls are possible.</td></tr></table>
