
# Description

<div class="content"><div style="background: white"><span style="font-size: medium"><span style="background: white; color: #444444">Byteasar read an interesting story recently. Its protagonist was some Greek crown prince who defeated a monster with a wool yarn, or something like that. But something else fascinated Byteasar about the story. What he liked most was the fact that the climax took place in a maze. From then on Byteasar is crazy about mazes.</span></span></div>
<div style="background: white"><span style="font-size: medium"><span style="background: white; color: #444444">Byteasar sketches mazes on a squared sheet of paper. Each sketch is a polygon with sides (representing the walls of the maze) parallel to either of the sheet&#39;s edges (i.e., the axes of the Carthesian coordinate system), and every two successive sides are perpendicular. Byteasar observed that if the entrance is placed on one of the sides of such a maze, then one can traverse the whole maze and return to the entrance by always keeping the right hand to the wall as one goes.</span></span></div>
<div style="background: white"><span style="font-size: medium"><span style="background: white; color: #444444">Moreover, throughout the maze traversal we can note the turns we take. We shall write the letter L if we turn left when we move along one wall to another, and P if we turn right in such case. Byteasar wonders for which words composed of the letters L and P there exists a maze whose traversal results in writing this very word.</span></span></div>
<p><span style="font-size: medium">构造一个n个顶点的多边形，按照它的边缘走，如果右转就是P，左转就是L。输出每个点的顶点</span></p>
<div><span style="font-size: medium">多边形不能自交，坐标绝对值要求在10^9以内</span></div></div>

# Input

<div class="content"><div style="background: white"><span style="font-size: medium"><span style="background: white; color: #444444">The first line of the standard input gives a single </span><span style="background: white; color: #444444">-letter word (1&lt;=N&lt;=100000) composed of the letters L and P, describing the sequence of successive turns made during the maze&#39;s traversal.</span></span></div></div>

# Output

<div class="content"><div style="background: white; margin: 8.7pt 0cm"> </div>
<div style="background: white"><span style="font-size: medium"><span style="background: white; color: #444444">If no maze corresponds to the description given as input, then the word NIE (Polish for <i>no</i>) is to be printed on the standard output. Otherwise, exactly </span><span style="background: white; color: #444444"> lines should be printed, specifying any maze (consistent with the input) as follows. The -th of these lines is to hold two integers, </span>xi <span style="background: white; color: #444444">and </span>yi</span><span style="font-size: medium">(-10^9&lt;=xi,yi&lt;=10^9)<span style="background: white; color: #444444">, separated by a single space, that are the coordinates of the </span>i<span style="background: white; color: #444444">-th vertex of the maze&#39;s sketch. The vertices are to be printed in their counterclockwise order on the polygon&#39;s perimeter; an arbitrary vertex can be chosen as the first one, and the position of the entrance need not be indicated.</span></span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">LLLLPPLL</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 0<br/>
2 0<br/>
2 2<br/>
-1 2<br/>
-1 -2<br/>
1 -2<br/>
1 -1<br/>
0 -1<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

