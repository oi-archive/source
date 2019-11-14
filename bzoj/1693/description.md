
# Description

<div class="content">
Bessie wants to navigate her spaceship through a dangerous asteroid
field in the shape of an N x N grid (1 &lt;= N &lt;= 500).  The grid
contains K asteroids (1 &lt;= K &lt;= 10,000), which are conveniently
located at the lattice points of the grid.

Fortunately, Bessie has a powerful weapon that can vaporize all the
asteroids in any given row or column of the grid with a single shot.
This weapon is quite expensive, so she wishes to use it sparingly.
Given the location of all the asteroids in the field, find the
minimum number of shots Bessie needs to fire to eliminate all of
the asteroids.

</div>

# Input

<div class="content">* Line 1: Two integers N and K, separated by a single space.

* Lines 2..K+1: Each line contains two space-separated integers R and
        C (1 &lt;= R, C &lt;= N) denoting the row and column coordinates of
        an asteroid, respectively.

</div>

# Output

<div class="content">* Line 1: The integer representing the minimum number of times Bessie
        must shoot.

</div>

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

<div class="content"><span class="sampledata"><br/>
2<br/>
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

