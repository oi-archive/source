# 

 
 # 题目描述 
<p>
<br>Bessie wants to navigate her spaceship through a dangerous asteroid<br>field in the shape of an N x N grid (1 <= N <= 500).  The grid<br>contains K asteroids (1 <= K <= 10,000), which are conveniently<br>located at the lattice points of the grid.<br><br>Fortunately, Bessie has a powerful weapon that can vaporize all the<br>asteroids in any given row or column of the grid with a single shot.<br>This weapon is quite expensive, so she wishes to use it sparingly.<br>Given the location of all the asteroids in the field, find the<br>minimum number of shots Bessie needs to fire to eliminate all of<br>the asteroids.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Two integers N and K, separated by a single space.<br><br>* Lines 2..K+1: Each line contains two space-separated integers R and<br>        C (1 <= R, C <= N) denoting the row and column coordinates of<br>        an asteroid, respectively.<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: The integer representing the minimum number of times Bessie<br>        must shoot.<br><br></p> 
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
<tr><td>3 4
1 1
1 3
2 2
3 2

INPUT DETAILS:

The following diagram represents the data, where "X" is an
asteroid and "." is empty space:
X.X
.X.
.X.

</td><td>
2

OUTPUT DETAILS:

Bessie may fire across row 1 to destroy the asteroids at (1,1) and
(1,3), and then she may fire down column 2 to destroy the asteroids
at (2,2) and (3,2).</td></tr></table>
