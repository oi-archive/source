# 题目描述


<h3>
	Problem
</h3>
<p>
	You live in a 2-dimensional plane, and one of your favourite places to visit is the Hall of Mirrors. The Hall of Mirrors is a room (a 2-dimensional room, of course) that is laid out in a grid. Every square on the grid contains either a square mirror, empty space, or you. You have width 0 and height 0, and you are located in the exact centre of your grid square.
</p>
<p>
	Despite being very small, you can see your reflection when it is reflected back to you exactly. For example, consider the following layout, where &#39;#&#39; indicates a square mirror that completely fills its square, &#39;.&#39; indicates empty space, and the capital letter &#39;X&#39;indicates you are in the center of that square:
</p>
<p>
	<br/>
</p>
<pre class="prettyprint">######
#..X.#
#.#..#
#...##
######</pre>
<p>
	<br/>
</p>
If you look straight up or straight to the right, you will be able to see your reflection.
<p>
	<br/>
</p>
<p>
	Unfortunately in the Hall of Mirrors it is very foggy, so you can&#39;t see further than D units away. Suppose D=3. If you look up, your reflection will be 1 unit away (0.5 to the mirror, and 0.5 back). If you look right, your reflection will be 3 units away (1.5 to the mirror, and 1.5 back), and you will be able to see it. If you look down, your reflection will be 5 units away and you won&#39;t be able to see it.
</p>
<p>
	It&#39;s important to understand how light travels in the Hall of Mirrors. Light travels in a straight line until it hits a mirror. If light hits any part of a mirror but its corner, it will be reflected in the normal way: it will bounce off with an angle of reflection equal to the angle of incidence. If, on the other hand, the light would touch the corner of a mirror, the situation is more complicated. The following diagrams explain the cases:
</p>
<p>
	In the following cases, light approaches a corner and is reflected, changing its direction: <br/>
<img src="/cogs/images/upload/image/20120415/20120415094056_11941.png" alt=""/><br/>
In the first two cases, light approached two adjacent mirrors at the point where they met. Light was reflected in the same way as if it had hit the middle of a long mirror. In the third case, light approached the corners of three adjacent mirrors, and returned in exactly the direction it came from.
</p>
<p>
	In the following cases, light approaches the corners of one or more mirrors, but does not bounce, and instead continues in the same direction: <br/>
<img src="/cogs/images/upload/image/20120415/20120415094104_44100.png" alt=""/><br/>
This happens when light reaches distance 0 from the corner of a mirror, but would not have to pass through the mirror in order to continue in the same direction. In this way, a ray of light can pass between two mirrors that are diagonally adjacent to each other -- effectively going through a space of size 0. Good thing it&#39;s of size 0 too, so it fits!
</p>
<p>
	In the final case, light approaches the corner of one mirror and is destroyed: <br/>
<img src="/cogs/images/upload/image/20120415/20120415094112_80457.png" alt=""/><br/>
The mirror was in the path of the light, and the ray of light didn&#39;t approach the corners of any other mirrors.
</p>
<p>
	Note that light stops when it hits you, but it has to hit the exact centre of your grid square.
</p>
<p>
	How many images of yourself can you see?
</p>
<h3>
	Input
</h3>
<p>
	The first line of the input gives the number of test cases, T. T test cases follow. Each test case starts with a line containing three space-separated integers, H, W and D. H lines follow, and each contains W characters. The characters constitute a map of the Hall of Mirrors for that test case, as described above.
</p>
<h3>
	Output
</h3>
<p>
	For each test case, output one line containing &#34;Case #x: y&#34;, where x is the case number (starting from 1) and y is the number of reflections of yourself you can see.
</p>
<h3>
	Limits
</h3>
<p>
	1 ≤ T ≤ 100.<br/>
3 ≤ H, W ≤ 30.<br/>
1 ≤ D ≤ 50.<br/>
All characters in each map will be &#39;#&#39;, &#39;.&#39;, or &#39;X&#39;.<br/>
Exactly one character in each map will be &#39;X&#39;.<br/>
The first row, the last row, the first column and the last column of each map will be entirely filled with &#39;#&#39; characters.
</p>
<h4>
	Small dataset
</h4>
<p>
	There will be no more than 2W+2H-4 &#39;#&#39; characters.
</p>
<h4>
	Large dataset
</h4>
<p>
	The restriction from the Small dataset does not apply.
</p>
<h3>
	Sample
</h3>
<div>
	<table>
		<tbody>
			<tr>
				<td>
					<br/>
Input <br/>
				</td>
				<td>
					<br/>
Output <br/>
				</td>
			</tr>
			<tr>
				<td>
					6<br/>
3 3 1<br/>
###<br/>
#X#<br/>
###<br/>
3 3 2<br/>
###<br/>
#X#<br/>
###<br/>
4 3 8<br/>
###<br/>
#X#<br/>
#.#<br/>
###<br/>
7 7 4<br/>
#######<br/>
#.....#<br/>
#.....#<br/>
#..X..#<br/>
#....##<br/>
#.....#<br/>
#######<br/>
5 6 3<br/>
######<br/>
#..X.#<br/>
#.#..#<br/>
#...##<br/>
######<br/>
5 6 10<br/>
######<br/>
#..X.#<br/>
#.#..#<br/>
#...##<br/>
######<br/>
				</td>
				<td>
					Case #1: 4<br/>
Case #2: 8<br/>
Case #3: 68<br/>
Case #4: 0<br/>
Case #5: 2<br/>
Case #6: 28<br/>
<br/>
				</td>
			</tr>
		</tbody>
	</table>
</div>
