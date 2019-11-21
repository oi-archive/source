# 

 
 # 题目描述 
<p>
<br>Farmer John has arranged his N (1 <= N <= 5,000) cows in a row and<br>many of them are facing forward, like good cows, Some of them are<br>facing backward, though, and he needs them all to face forward to<br>make his life perfect.<br><br>Fortunately, FJ recently bought an automatic cow turning machine.<br>Since he purchased the discount model, it must be irrevocably preset<br>to turn K (1 <= K <= N) cows at once, and it can only turn cows<br>that are all standing next to each other in line. Each time the<br>machine is used, it reverses the facing direction of a contiguous<br>group of K cows in the line (one cannot use it on fewer than K cows,<br>e.g., at the either end of the line of cows). Each cow remains in<br>the same *location* as before, but ends up facing the *opposite<br>direction*.  A cow that starts out facing forward will be turned<br>backward by the machine and vice-versa.<br><br>Because FJ must pick a single, never-changing value of K, please<br>help him determine the minimum value of K that minimizes the number of<br>operations required by the machine to make all the cows face forward.<br>Also determine M, the minimum number of machine operations required<br>to get all the cows facing forward using that value of K.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: A single integer: N<br><br>* Lines 2..N+1: Line i+1 contains a single character, F or B,<br>        indicating whether cow i is facing forward or backward.<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: Two space-separated integers: K and M<br></p> 
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
7
B
B
F
B
F
B
B

INPUT DETAILS:

There are seven cows and they are facing backward, backward, forward,
backward, forward, backward, and backward, respectively.
</td><td>
3 3

OUTPUT DETAILS:

For K = 3, the machine must be operated three times: turn cows (1,2,3),
(3,4,5), and finally (5,6,7):

      B > F   F   F
      B > F   F   F
      F > B > F   F
      B   B > F   F
      F   F > B > F
      B   B   B > F
      B   B   B > F</td></tr></table>
