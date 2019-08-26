
# Description

<div class="content"><div>ZCC loves playing Minecraft, a sandbox construction game, with his friends. Each friend built his own house, which can be regarded as a point in a plane. However, their houses are so dispersed that they often get attacked by monsters on the way to others&#39; houses. Fortunately, monsters won&#39;t come into being in the bright areas. ZCC planned to light a point set S up, through which his friends can visit each other safely. S should include every house. For the convenience of transport, the intersection of S and an arbitrary horizon or vertical line should be empty, a point, or a single continuous segment. This definition is similar to the definition of convex hull, but the line can only be horizon or vertical here because everything in Minecraft is formed by cubes. ZCC also wanted to minimize the area of S to save money.</div>
<div>After working hard for a long time, ZCC obtained the solution. However, as ZCC became more and more famous, the number of his friends increased sharply. Every time a new friend joins the game, ZCC have to calculate S again. He needs your help.</div>
<div>Notice that S may not be continuous, but it&#39;s guaranteed that S is continuous at any time. The situation of the following figure will never occur.</div>
<div><img src="source/bzoj/3845/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwMS9hMS5qcGc=.jpg" width="272" height="210" alt=""/></div>
<p></p></div>

# Input

<div class="content"><div>
<div>The input contains several test cases.</div>
<div>Each test case contains n+1 lines.</div>
<div>A integer N(1≤N≤100000) will exist in the first line of each input,which represents the number of friends.</div>
<div>The i-th (2≤i≤n+1) line contains two integers x,y (-100000≤x,y≤100000),which represent the coordinate of the i-1-th friend.</div>
</div>
<p></p></div>

# Output

<div class="content"><div>Output should contain n lines.</div>
<div>The i-th line is a number that is the area of S after the i-th friend joins the game.</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
0 0<br/>
0 5<br/>
3 3<br/>
1 1<br/>
2 -1</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
0<br/>
0<br/>
2<br/>
6<br/>
</span></div>

# Hint

<div class="content"><p></p><p>The blue areas in the following pictures represent point set S.</p><br/>
<div><img src="source/bzoj/3845/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwMS9hMi5qcGc=.jpg" width="561" height="233" alt=""/></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 镇海中学">By 镇海中学</a></p></div>

