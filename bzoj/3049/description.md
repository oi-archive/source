
# Description

<div class="content"><p><span style="font-size: medium">Farmer John has taken the cows to a vacation out on the ocean! The cows are living on N (1 &lt;= N &lt;= 15) islands, which are located on an R x C grid (1 &lt;= R, C &lt;= 50). An island is a maximal connected group of squares on the grid that are marked as &#39;X&#39;, where two &#39;X&#39;s are connected if they share a side. (Thus, two &#39;X&#39;s sharing a corner are not necessarily connected.) Bessie, however, is arriving late, so she is coming in with FJ by helicopter. Thus, she can first land on any of the islands she chooses. She wants to visit all the cows at least once, so she will travel between islands until she has visited all N of the islands at least once. FJ&#39;s helicopter doesn&#39;t have much fuel left, so he doesn&#39;t want to use it until the cows decide to go home. Fortunately, some of the squares in the grid are shallow water, which is denoted by &#39;S&#39;. Bessie can swim through these squares in the four cardinal directions (north, east, south, west) in order to travel between the islands. She can also travel (in the four cardinal directions) between an island and shallow water, and vice versa. Find the minimum distance Bessie will have to swim in order to visit all of the islands. (The distance Bessie will have to swim is the number of distinct times she is on a square marked &#39;S&#39;.) After looking at a map of the area, Bessie knows this will be possible. </span></p>
<div><span style="font-size: 14pt">  </span><span style="font-size: 14pt">给你一张</span><span style="font-size: 14pt">r*c</span><span style="font-size: 14pt">的地图，有</span><span style="font-size: 14pt">’S’,’X’,’.’</span><span style="font-size: 14pt">三种地形，所有判定相邻与行走都是四连通的。我们设</span><span style="font-size: 14pt">’X’</span><span style="font-size: 14pt">为陆地，一个</span><span style="font-size: 14pt">’X’</span><span style="font-size: 14pt">连通块为一个岛屿，</span><span style="font-size: 14pt">’S’</span><span style="font-size: 14pt">为浅水，</span><span style="font-size: 14pt">’.’</span><span style="font-size: 14pt">为深水。刚开始你可以降落在任一一块陆地上，在陆地上可以行走，在浅水里可以游泳。并且陆地和浅水之间可以相互通行。但无论如何都不能走到深水。你现在要求通过行走和游泳使得你把所有的岛屿都经过一边。</span><span style="font-size: 14pt">Q</span><span style="font-size: 14pt">：你最少要经过几个浅水区？保证有解。</span></div>
<div> </div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Two space-separated integers: R and C. <br/>
* Lines 2..R+1: Line i+1 contains C characters giving row i of the grid. Deep water squares are marked as &#39;.&#39;, island squares are marked as &#39;X&#39;, and shallow water squares are marked as &#39;S&#39;. <br/>
</span></p></div>

# Output

<div class="content"><p>* Line 1: A single integer representing the minimum distance Bessie has to swim to visit all islands.</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4<br/>
XX.S<br/>
.S..<br/>
SXSS<br/>
S.SX<br/>
..SX<br/>
<br/>
<br/>
INPUT DETAILS: There are three islands with shallow water paths connecting some of them. <br/>
<br/>
 </span></div>

# Sample Output

<div class="content"><span class="sampledata"> 3 <br/>
OUTPUT DETAILS: Bessie can travel from the island in the top left to the one in the middle, swimming 1 unit, <br/>
and then travel from the middle island to the one in the bottom right, swimming 2 units, for a total of 3 units. <br/>
<br/>
<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><div><span style="font-size: 14pt">样例解释：</span></div><br/>
<div><span style="font-size: 14pt"> 5*4</span><span style="font-size: 14pt">的地图，先走到左上角的岛屿，再向下经过</span><span style="font-size: 14pt">1</span><span style="font-size: 14pt">个</span><span style="font-size: 14pt">’S’</span><span style="font-size: 14pt">区到达中间的岛屿，再向右经过</span><span style="font-size: 14pt">2</span><span style="font-size: 14pt">个</span><span style="font-size: 14pt">’S’</span><span style="font-size: 14pt">区到达右下角的岛屿。（最优路径不一定只有一条）</span></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

