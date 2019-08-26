
# Description

<div class="content"><div>Bessie and her friends have invented a new game. The game is named accurately, but not particularly </div>
<div>creatively. They call it the &#34;Push A Box Around The Barn To Get It In The Right Spot And Don&#39;t Move </div>
<div>The Hay&#34; game (if you think that&#39;s excessive, you should see some of the variable names the cows use</div>
<div> when they write code...)The barn can be modeled as an N×M rectangular grid. Some of the grid cells</div>
<div> have hay in them. Bessie occupies one cell in this grid, and a large wooden box occupies another ce</div>
<div>ll. Bessie and the box are not able to fit in the same cell at the same time, and neither can fit in</div>
<div>to a cell containing hay.Bessie can move in the 4 orthogonal directions (north, east, south, west) a</div>
<div>s long as she does not walk into hay. If she attempts to walk to the space with the box, then the bo</div>
<div>x will be pushed one space in that direction, as long as there is an empty cell on the other side. I</div>
<div>f there is no empty cell, then Bessie will not be able to make that move.A certain grid cell is desi</div>
<div>gnated as the goal. Bessie&#39;s goal is to get the box into that location.Given the layout of the barn,</div>
<div> including the starting positions of the box and the cow, and the target position of the box, determ</div>
<div>ine if it possible to win the game.</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line has three numbers, N, M, and Q, </div>
<div>where N is the number of rows in the grid and M is the number of columns.</div>
<div>1≤N,M≤1500</div>
<div>1≤Q≤50,000</div>
<div>On the next N lines is a representation of the grid, </div>
<div>where characters represent empty cells (.), hay (#),</div>
<div>Bessie&#39;s starting position (A), and the box&#39;s initial location (B).</div>
<div></div>
<div>This is followed by Q lines, each with a pair of integers (R,C). </div>
<div>For each pair, you should determine if it is possible to get the box to that cell at row R, column C, </div>
<div>starting from the initial state of the barn. The top row is row 1, and the left column is column 1.</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Q lines, each with either the string &#34;YES&#34; or &#34;NO&#34;.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5 4<br/>
##.##<br/>
##.##<br/>
A.B..<br/>
##.##<br/>
##.##<br/>
3 2<br/>
3 5<br/>
1 3<br/>
5 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">NO<br/>
YES<br/>
NO<br/>
NO<br/>
To push the box to the position (3, 5), the cow just needs to move 3 spaces to the right.<br/>
None of the other three positions are attainable.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum">Platinum</a></p></div>

