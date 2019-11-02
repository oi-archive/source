# 

 
 # 题目描述 
<p>
<br>A group of cows grabbed a truck and ventured on an expedition deep<br>into the jungle.  Being rather poor drivers, the cows unfortunately<br>managed to run over a rock and puncture the truck's fuel tank.  The<br>truck now leaks one unit of fuel every unit of distance it travels.<br><br>To repair the truck, the cows need to drive to the nearest town (no<br>more than 1,000,000 units distant) down a long, winding road.  On<br>this road, between the town and the current location of the truck,<br>there are N (1 <= N <= 10,000) fuel stops where the cows can stop<br>to acquire additional fuel (1..100 units at each stop).<br><br>The jungle is a dangerous place for humans and is especially dangerous<br>for cows. Therefore, the cows want to make the minimum possible<br>number of stops for fuel on the way to the town. Fortunately, the<br>capacity of the fuel tank on their truck is so large that there is<br>effectively no limit to the amount of fuel it can hold. The truck<br>is currently L units away from the town and has P units of fuel (1<br><= P <= 1,000,000).<br><br>Determine the minimum number of stops needed to reach the town, or<br>if the cows cannot reach the town at all.<br><br></p> 

 
 # 输入格式 
<p>
<br>* Line 1: A single integer, N<br><br>* Lines 2..N+1: Each line contains two space-separated integers<br>        describing a fuel stop: The first integer is the distance from<br>        the town to the stop; the second is the amount of fuel<br>        available at that stop.<br><br>* Line N+2: Two space-separated integers, L and P<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: A single integer giving the minimum number of fuel stops<br>        necessary to reach the town.  If it is not possible to reach<br>        the town, output -1.<br><br></p> 
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
4
4 4
5 2
11 5
15 10
25 10

INPUT DETAILS:

The truck is 25 units away from the town; the truck has 10 units
of fuel.  Along the road, there are 4 fuel stops at distances 4,
5, 11, and 15 from the town (so these are initially at distances
21, 20, 14, and 10 from the truck).  These fuel stops can supply
up to 4, 2, 5, and 10 units of fuel, respectively.

</td><td>
2

OUTPUT DETAILS:

Drive 10 units, stop to acquire 10 more units of fuel, drive 4 more
units, stop to acquire 5 more units of fuel, then drive to the town.</td></tr></table>
