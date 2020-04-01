# 

 
 # 题目描述 
<p>
<br>A long, linear field has N (1 <= N <= 1,000) clumps of grass at<br>unique integer locations on what will be treated as a number line.<br>Think of the clumps as points on the number line.<br><br>Bessie starts at some specified integer location L on the number<br>line (1 <= L <= 1,000,000) and traverses the number line in the two<br>possible directions (sometimes reversing her direction) in order<br>to reach and eat all the clumps.  She moves at a constant speed<br>(one unit of distance in one unit of time), and eats a clump instantly<br>when she encounters it.<br><br>Clumps that aren't eaten for a while get stale.  We say the<br>``staleness'' of a clump is the amount of time that elapses from<br>when Bessie starts moving until she eats a clump.  Bessie wants to<br>minimize the total staleness of all the clumps she eats.<br><br>Find the minimum total staleness that Bessie can achieve while<br>eating all the clumps.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1 : Two space-separated integers: N and L.<br><br>* Lines 2..N+1: Each line contains a single integer giving the<br>        position P of a clump (1 <= P <= 1,000,000).<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: A single integer: the minimum total staleness Bessie can<br>        achieve while eating all the clumps.<br></p> 
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
4 10
1
9
11
19

INPUT DETAILS:

Four clumps: at 1, 9, 11, and 19. Bessie starts at location 10.
</td><td>
44

OUTPUT DETAILS:

Bessie can follow this route:

* start at position 10 at time 0
* move to position 9, arriving at time 1
* move to position 11, arriving at time 3
* move to position 19, arriving at time 11
* move to position 1, arriving at time 29

giving her a total staleness of 1+3+11+29 = 44.  There are other routes
with the same total staleness, but no route with a smaller one.</td></tr></table>
