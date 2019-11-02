# 

 
 # 题目描述 
<p>
<br>Figuring that they cannot do worse than the humans have, Farmer<br>John's cows have decided to start an airline.  Being cows, they<br>decide to cater to the heretofore-untapped market of cows as<br>passengers. They plan to serve the cows who live along the western<br>coast of Lake Michigan. Each morning, they will fly from the<br>northern-most point of the coast southward towards Chicowgo, making<br>many stops along the way.  Each evening, they will fly back north<br>to the northern-most point.<br><br>They need your help to decide which passengers to carry each day.<br>Each of N (1 <= N <= 10,000) farms numbered 1..N along the coast<br>contains an airport (Farm 1 is northern-most; farm N is southern-most).<br>On this day, K (1 <= K <= 50,000) groups of cows wish to travel.<br>Each group of cows wants to fly from a particular farm to another<br>particular farm.  The airline, if it wishes, is allowed to stop and<br>pick up only part of a group. Cows that start a flight, however,<br>must stay on the plane until they reach their destination.<br><br>Given the capacity C (1 <= C <= 100) of the airplane and the groups<br>of cows that want to travel, determine the maximum number of cows<br>that the airline can fly to their destination.<br><br></p> 

 
 # 输入格式 
<p>
<br>* Line 1: Three space-separated integers: K, N, and C<br><br>* Lines 2..K+1: Each line contains three space-separated integers S,<br>        E, and M that specify a group of cows that wishes to travel. <br>        The M (1 <= M <= C) cows are currently at farm S and want to<br>        travel to farm E (S != E).<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: The maximum number of cows that can be flown to their<br>        destination. This is the sum of the number of cows flown to<br>        their destination on the flight southward in the morning plus<br>        the number of cows flown to their destination on the flight<br>        northward in the evening.<br><br></p> 
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
4 8 3
1 3 2
2 8 3
4 7 1
8 3 2

INPUT DETAILS:

Four groups of cows, eight farms, and three seats on the
plane.

</td><td>
6

OUTPUT DETAILS:

In the morning, the flight takes 2 cows from 1->3, 1 cow from 2->8,
and 1 cow from 4->7.  In the evening, the flight takes 2 cows from
8->3.</td></tr></table>
