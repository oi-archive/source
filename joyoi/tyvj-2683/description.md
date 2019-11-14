# 

 
 # 题目描述 
<p>
Imagine that you are in a building with F floors (starting at floor 1, the lowest floor), and you have a large number of identical eggs, each in its own identical protective container. For each floor in the building, you want to know whether or not an egg dropped from that floor will break. If an egg breaks when dropped from floor i, then all eggs are guaranteed to break when dropped from any floor j ≥ i. Likewise, if an egg doesn't break when dropped from floor i, then all eggs are guaranteed to never break when dropped from any floor j ≤ i.<br>We can define Solvable(F, D, B) to be true if and only if there exists an algorithm to determine whether or not an egg will break when dropped from any floor of a building with F floors, with the following restrictions: you may drop a maximum of D eggs (one at a time, from any floors of your choosing), and you may break a maximum of B eggs. You can assume you have at least D eggs in your possession.<br></p> 

 
 # 输入格式 
<p>
The first line of input gives the number of cases, N. N test cases follow. Each case is a line formatted as:<br>F D B<br>Solvable(F, D, B) is guaranteed to be true for all input cases.<br></p> 

 
 # 输出格式 
<p>
For each test case, output one line containing "Case #x: " followed by three space-separated integers: Fmax, Dmin, and Bmin. <br>The definitions are as follows:<br>1.	Fmax is defined as the largest value of F' such that Solvable(F', D, B) is true, or -1 if this value would be greater than or equal to 232 .(In other words, Fmax = -1 if and only if Solvable(232, D, B) is true.)<br>2.	Dmin is defined as the smallest value of D' such that Solvable(F, D', B) is true.<br>3.	Bmin is defined as the smallest value of B' such that Solvable(F, D, B') is true.<br><br>Limits<br>1 ≤ N ≤ 100. <br>Small dataset<br>1 ≤ F ≤ 100,<br>1 ≤ D ≤ 100,<br>1 ≤ B ≤ 100. <br>Large dataset<br>1 ≤ F ≤ 2000000000,<br>1 ≤ D ≤ 2000000000,<br>1 ≤ B ≤ 2000000000. <br></p> 
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
<tr><td>2
3 3 3
7 5 3
</td><td>Case #1: 7 2 1
Case #2: 25 3 2</td></tr></table>
