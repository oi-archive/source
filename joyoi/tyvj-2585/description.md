# 

 
 # 题目描述 
<p>
<br>Over the years, FJ has made a huge number of farmer friends all<br>around the world.  Since he hasn't visited 'Farmer Ted' from England<br>and 'Boer Harms' from Holland for a while, he'd like to visit them.<br><br>He knows the longitude of the farm where each of his worldwide<br>friends resides.  This longitude is an angle (an integer in the<br>range 0..359) describing the farm's location on the Earth, which<br>we will consider to be a circle instead of the more complex and<br>traditional spherical representation. Except for the obvious<br>discontinuity, longitudes increase when traveling clockwise on this<br>circle.<br><br>FJ plans to travel by airplane to visit his N (1 <= N <= 5,000)<br>friends (whose farms are uniquely numbered 1..N). He knows the<br>schedules for M (1 <= M <= 25,000) bidirectional flights connecting<br>the different farms.  Airplanes always travel shortest paths on the<br>Earth's surface (i.e., on the shortest arc of a circle).<br><br>There will always be a unique shortest path between two farms that<br>are directly connected.  No pair of antipodal farms (exactly opposite<br>each other on the circle) is ever directly connected.<br><br>Each airplane flight can be described as traveling in clockwise or<br>counterclockwise direction around the Earth's surface. For example,<br>a flight from longitude 30 to longitude 35 would be clockwise, as<br>would be a flight from longitude 350 to longitude 10.  However, a<br>flight from longitude 350 to longitude 200 follows a shortest path<br>counterclockwise around the circle.<br><br>FJ would find it very cool if he could make a trip around the world,<br>visiting some of his friends along the way. He'd like to know if<br>this is possible and if so, what is the minimum number of flights<br>he can take to do so.<br><br>He wants to start and finish his journey at the location of his<br>best friend (the one listed first in the input below).  In order<br>to make sure he actually circles the Earth, he wants to ensure that<br>the clockwise distance he travels is different from the counterclockwise<br>distance he travels.<br><br></p> 

 
 # 输入格式 
<p>
<br>* Line 1: Two space-separated integers: N  and M<br><br>* Lines 2..N+1: Line i+1 contains one integer: the longitude of the<br>        i-th farm. Line 2 contains the location of the farm of his<br>        best friend.<br><br>* Lines N+2..N+M+1: Line i+N+1 contains two integers giving the<br>        indices of two farms that are connected by a flight.<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: A single integer specifying the minimum number of flights FJ<br>        needs to visit to make a trip around the world. Every time FJ<br>        moves from one farm to another counts as one flight. If it is<br>        impossible to make such a trip, output the integer -1.<br><br></p> 
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
3 3
0
120
240
1 2
2 3
1 3

INPUT DETAILS:

Farmer John has three friends at longitudes 0, 120, and 240.  There are
three flights: 0<->120, 120<->240, and 0<->240.  The journey must start and
finish at longitude 0.

</td><td>
3

OUTPUT DETAILS:

FJ must visit all 3 friends to make a full trip around the world.</td></tr></table>
