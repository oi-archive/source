<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>The center of Gdynia is located on an island in the middle of the Kacza river. Every morning thousands of<br>cars drive through this island from the residential districts on the western bank of the river (using bridge<br>connections to junctions on the western side of the island) to the industrial areas on the eastern bank (using<br>bridge connections from junctions on the eastern side of the island).<br>The island resembles a rectangle, whose sides are parallel to the cardinal directions. Hence, we view it as<br>an A × B rectangle in a Cartesian coordinate system, whose opposite corners are in points (0, 0) and (A,B).<br>On the island, there are n junctions numbered from 1 to n. The junction number i has coordinates (xi, yi).<br>If a junction has coordinates of the form (0, y), it lies on the western side of the island. Similarly, junctions<br>with the coordinates (A, y) lie on the eastern side. Junctions are connected by streets. Each street is a line<br>segment connecting two junctions. Streets can be either unidirectional or bidirectional. No two streets may<br>have a common point (except for, possibly, a common end in a junction). There are are no bridges or tunnels.<br>You should not assume anything else about the shape of the road network. In particular, there can be streets<br>going along the river bank or junctions with no incoming or outgoing streets.<br>Because of the growing traﬃc density, the city mayor has hired you to check whether the current road<br>network on the island is suﬃcient. He asked you to write a program which determines how many junctions on<br>the eastern side of the island are reachable from each junction on the western side.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The ﬁrst line of the standard input contains four integers n, m, A and B (1 ¬ n ¬ 300 000, 0 ¬ m ¬ 900 000,<br>1 ¬ A,B ¬ 109). They denote the number of junctions in the center of Gdynia, the number of streets and<br>dimensions of the island, respectively.<br>In each of the following n lines there are two integers xi, yi (0 ¬ xi ¬ A, 0 ¬ yi ¬ B) describing the<br>coordinates of the junction number i. No two junctions can have the same coordinates.<br>The next m lines describe the streets. Each street is represented in a single line by three integers ci, di, ki<br>(1 ¬ ci, di ¬ n, ci = di, ki ∈ {1, 2}). Their meaning is that junctions ci and di are connected with a street. If<br>ki = 1, then this is a unidirectional street from ci to di. Otherwise, the street can be driven in both directions.<br>Each unordered pair {ci, di} can appear in the input at most once.<br>You can assume that there is at least one junction on the western side of the island from which it is possible<br>to reach some junction on the eastern side of the island.<br>Additionally, in test cases worth at least 30 points, n,m ¬ 6 000.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>Your program should write to the standard output one line for each junction on the western side of the island.<br />This line should contain the number of junctions on the eastern side that are reachable from that junction.<br />The output should be ordered according to decreasing y-coordinates of the junctions.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 3 1 3<br>0 0<br>0 1<br>0 2<br>1 0<br>1 1<br>1 4 1<br>1 5 2<br>3 5 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2<br>0<br>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1 ¬ n ¬ 300 000, 0 ¬ m ¬ 900 000</p>
</div>
</div>