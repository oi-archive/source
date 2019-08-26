
# Description

<div class="content"><div>Association of Collision Management (ACM) is planning to perform the controlled collision of two asteroids. The asteroids will be slowly brought together and collided at negligible speed. ACM expects asteroids to get attached to each other and form a stable object. </div>
<div>Each asteroid has the form of a convex polyhedron. To increase the chances of success of the experiment ACM wants to bring asteroids together in such manner that their centers of mass are as close as possible. To achieve this, ACM operators can rotate the asteroids and move them independently before bringing them together. </div>
<div>Help ACM to find out what minimal distance between centers of mass can be achieved. </div>
<div>For the purpose of calculating center of mass both asteroids are considered to have constant density.</div>
<div></div>
<div>
<div>给这下两个三维凸包，问如何放置使得它们的质心相距最近。每个凸包</div>
<div>只无序给出它的顶点。求两个凸包质心的最近距离。</div>
<div>凸包点数不超过60</div>
</div>
<p></p></div>

# Input

<div class="content"><div>Input file contains two descriptions of convex polyhedra. </div>
<div>
<div>The first line of each description contains integer number n - the number of vertices of the polyhedron (4 &lt;= n &lt;= 60). The following n lines contain three integer numbers xi, yi, zi each - the coordinates of the polyhedron vertices (-104 &lt;= xi, yi, zi &lt;= 104). It is guaranteed that the given points are vertices of a convex polyhedron, in particular no point belongs to the convex hull of other points. Each polyhedron is non-degenerate. </div>
<div>The two given polyhedra have no common points.</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>Output one floating point number - the minimal distance between centers of mass of the asteroids that can be achieved. Your answer must be accurate up to 10-5.</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">8<br/>
0 0 0<br/>
0 0 1<br/>
0 1 0<br/>
0 1 1<br/>
1 0 0<br/>
1 0 1<br/>
1 1 0<br/>
1 1 1<br/>
5<br/>
0 0 5<br/>
1 0 6<br/>
-1 0 6<br/>
0 1 6<br/>
0 -1 6<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.75<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris提供SPJ">鸣谢Claris提供SPJ</a></p></div>

