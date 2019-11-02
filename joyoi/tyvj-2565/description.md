# 

 
 # 题目描述 
<p>
<br>Farmer Ron in Colorado is building a ski resort for his cows (though<br>budget constraints dictate construction of just one ski lift). The<br>lift will be constructed as a monorail and will connect a concrete<br>support at the starting location to the support at the ending<br>location via some number of intermediate supports, each of height<br>0 above its land. A straight-line segment of steel connects every<br>pair of adjacent supports. For obvious reasons, each section of<br>straight steel must lie above the ground at all points.<br><br>Always frugal, FR wants to minimize the number of supports that he<br>must build. He has surveyed the N (2 <= N <= 5,000) equal-sized<br>plots of land the lift will traverse and recorded the integral<br>height H (0 <= H <= 1,000,000,000) of each plot. Safety regulations<br>require FR to build adjacent supports no more than K (1 <= K <= N<br>- 1) units apart. The steel between each pair of supports is rigid<br>and forms a straight line from one support to the next.<br><br>Help FR compute the smallest number of supports required such that:<br>each segment of steel lies entirely above (or just tangent to) each<br>piece of ground, no two consecutive supports are more than K units<br>apart horizontally, and a support resides both on the first plot<br>of land and on the last plot of land.<br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separate integers, N and K<br><br>* Lines 2..N+1: Line i+1 contains a single integer that is the height<br>        of plot i.<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: A single integer equal to the fewest number of lift towers<br>        FR needs to  build subject to the above constraints<br></p> 
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
13 4
0
1
0
2
4
6
8
6
8
8
9
11
12</td><td>
5

OUTPUT DETAILS:

FR builds five supports (at locations 1, 5, 7, 9, and 13). The steel
is tangent to the ground at four locations: 1-5, 5-7, 7-9, and
12-13.

If FR only builds supports at the four locations 1, 5, 9, and 13,
then the steel would be below ground from 5-9. If FR built supports
at 1, 7, and 13, then -- although the steel is always above ground
-- supports 7 and 13 are more than 4 units apart horizontally. There
is no solution using fewer than 5 supports such that no two consecutive
supports are more than 4 units apart horizontally.</td></tr></table>
