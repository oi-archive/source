# 

 
 # 题目描述 
<p>
<br>Every morning, Farmer John's N (1 <= N <= 25,000) cows all line up<br>for milking. In an effort to streamline the milking process, FJ has<br>designed a two-stage milking process where the line of cows progresses<br>through two barns in sequence, with milking taking part sequentially<br>in both barns. Farmer John milks cows one by one as they go through<br>the first barn, and his trusty sidekick Farmer Rob milks the cows<br>(in the same order) as they are released from the first barn and<br>enter the second barn.<br><br>Unfortunately, Farmer John's insistence that the cows walk through<br>both barns according to a single ordering leads to some inefficiencies.<br>For example, if Farmer John takes too long to milk a particular<br>cow, Farmer Rob might end up sitting idle with nothing to do for<br>some time. On the other hand, if Farmer John works too fast then<br>we might end up with a long queue of cows waiting to enter the<br>second barn.<br><br>Please help Farmer John decide on the best possible ordering of<br>cows to use for the milking, so that the last cow finishes milking<br>as early as possible. For each cow i we know the time A(i) required<br>for milking in the first barn and the time B(i) required for milking<br>in the second barn.  Both A(i) and B(i) are in the range 1...20,000.<br></p> 

 
 # 输入格式 
<p>
* Line 1: A single integer, N.<br><br>* Lines 2..1+N: Line i+1 contains two space-separated integers A(i)<br>        and B(i) for cow i.<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: The minimum possible time it takes to milk all the cows, if<br>        we order them optimally.<br><br></p> 
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
<tr><td>
3
2 2
7 4
3 5

INPUT DETAILS:

There are three cows.  Cow #1 takes 2 units of time in both barns,
cow #2 takes 7 units of time in the first barn and 4 in the second,
and cow #3 takes 3 units of time in the first barn and 5 in the
second.

</td><td>
16

OUTPUT DETAILS:

Ordering the cows in the order 3, 1, 2, will allow for milking to complete
within only 16 units of time.</td></tr></table>
