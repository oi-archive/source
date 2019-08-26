
# Description

<div class="content"><p>After eating too much fruit in Farmer John&#39;s kitchen, Bessie the cow is getting some very strange dreams! In her most recent dream, she is trapped in a maze in the shape of an N×M grid of tiles (1≤N,M≤1,000). She starts on the top-left tile and wants to get to the bottom-right tile. When she is standing on a tile, she can potentially move to the adjacent tiles in any of the four cardinal directions.<br/>
<br/>
But wait! Each tile has a color, and each color has a different property! Bessie&#39;s head hurts just thinking about it:<br/>
<br/>
    If a tile is red, then it is impassable.<br/>
    If a tile is pink, then it can be walked on normally.<br/>
    If a tile is orange, then it can be walked on normally, but will make Bessie smell like oranges.<br/>
    If a tile is blue, then it contains piranhas that will only let Bessie pass if she smells like oranges.<br/>
    If a tile is purple, then Bessie will slide to the next tile in that direction (unless she is unable to cross it). If this tile is also a purple tile, then Bessie will continue to slide until she lands on a non-purple tile or hits an impassable tile. Sliding through a tile counts as a move. Purple tiles will also remove Bessie&#39;s smell. <br/>
<br/>
(If you&#39;re confused about purple tiles, the example will illustrate their use.)<br/>
<br/>
Please help Bessie get from the top-left to the bottom-right in as few moves as possible.</p>
<p></p>
<p>奶牛Bessie被困在了N*M的网格图迷宫中，她位于左上角(1,1)，出口在右下角(N,M)。Bessie只能上下左右行走。</p>
<p>每块地砖都有一个颜色：</p>
<p>如果是红色，那么不可通行。</p>
<p>如果是粉色，那么可以通行。</p>
<p>如果是橙色，那么可以通行，但是会给Bessie带上橘子的气味。</p>
<p>如果是蓝色，那么当且仅当Bessie带着橘子的气味时，才可以通行。</p>
<p>如果是紫色，那么Bessie会保持原有方向滑过去，如果之后仍然是紫色，那么会继续滑。当滑到不是紫色的地砖上或者不可通行的时候，才会停下来。并且这会消除Bessie身上的气味。每一步滑行和走路一样，都需要耗费一单位时间。</p>
<p>请输出Bessie逃到出口所需的最短时间。</p>
<p></p></div>

# Input

<div class="content"><p>The first line has two integers N and M, representing the number of rows and columns of the maze.<br/>
<br/>
The next NN lines have MM integers each, representing the maze:<br/>
<br/>
    The integer &#39;0&#39; is a red tile<br/>
    The integer &#39;1&#39; is a pink tile<br/>
    The integer &#39;2&#39; is an orange tile<br/>
    The integer &#39;3&#39; is a blue tile<br/>
    The integer &#39;4&#39; is a purple tile <br/>
<br/>
The top-left and bottom-right integers will always be &#39;1&#39;.</p></div>

# Output

<div class="content"><p>A  single integer, representing the minimum number of moves Bessie must  use to cross the maze, or -1 if it is impossible to do so.</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
1 0 2 1<br/>
1 1 4 1<br/>
1 0 4 0<br/>
1 3 1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">10</span></div>

# Hint

<div class="content"><p></p><p>In this example, Bessie walks one square down and two squares to the right (and then slides one more square to the right). She walks one square up, one square left, and one square down (sliding two more squares down) and finishes by walking one more square right. This is a total of 10 moves (DRRRULDDDR).</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold鸣谢Claris提供译文">Gold鸣谢Claris提供译文</a></p></div>

