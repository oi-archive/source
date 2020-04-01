
# Description

<div class="content"><p><span style="font-size: medium">Bessie wants to navigate her spaceship through a dangerous asteroid field in the shape of an N x N grid (1 &lt;= N &lt;= 500). The grid contains K asteroids (1 &lt;= K &lt;= 10,000), which are conveniently located at the lattice points of the grid. Fortunately, Bessie has a powerful weapon that can vaporize all the asteroids in any given row or column of the grid with a single shot. This weapon is quite expensive, so she wishes to use it sparingly. Given the location of all the asteroids in the field, find the minimum number of shots Bessie needs to fire to eliminate all of the asteroids. </span></p>
<div><span style="font-size: medium">贝茜想驾驶她的飞船穿过危险的小行星群．小行星群是一个NxN的网格(1≤N≤500)，在</span><span style="font-size: medium">网格内有K个小行星(1≤K≤10000)． 幸运地是贝茜有一个很强大的武器，一次可以消除所有在一行或一列中的小行星，这种武器很贵，所以她希望尽量地少用．给出所有的小行星的位置，算出贝茜最少需要多少次射击就能消除所有的小行星．</span></div>
<div></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Two integers N and K, separated by a single space. </span></p>
<p><span style="font-size: medium">* Lines 2..K+1: Each line contains two space-separated integers R and C (1 &lt;= R, C &lt;= N) denoting the row and column coordinates of an asteroid, respectively. </span></p>
<div><span style="font-size: medium">    第1行：两个整数N和K，用一个空格隔开．</span></div>
<div><span style="font-size: medium">    第2行至K+1行：每一行有两个空格隔开的整数R，C(1≤R，C≤N)，分别表示小行星所在</span><span style="font-size: medium">的行和列．</span></div>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: The integer representing the minimum number of times Bessie must shoot. </span></p>
<p><span style="font-size: medium">    一个整数表示贝茜需要的最少射击次数，可以消除所有的小行星</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
1 1<br/>
1 3<br/>
2 2<br/>
3 2<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
The following diagram represents the data, where &#34;X&#34; is an<br/>
asteroid and &#34;.&#34; is empty space:<br/>
X.X<br/>
.X.<br/>
.X.<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
Bessie may fire across row 1 to destroy the asteroids at (1,1) and<br/>
(1,3), and then she may fire down column 2 to destroy the asteroids<br/>
at (2,2) and (3,2).<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

