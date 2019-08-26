
# Description

<div class="content"><p><span style="font-size: medium">Farmer John knows that an intellectually satisfied cow is a happy cow who will give more milk. He has arranged a brainy activity for cows in which they manipulate an M x N grid (1 &lt;= M &lt;= 15; 1 &lt;= N &lt;= 15) of square tiles, each of which is colored black on one side and white on the other side. As one would guess, when a single white tile is flipped, it changes to black; when a single black tile is flipped, it changes to white. The cows are rewarded when they flip the tiles so that each tile has the white side face up. However, the cows have rather large hooves and when they try to flip a certain tile, they also flip all the adjacent tiles (tiles that share a full edge with the flipped tile). Since the flips are tiring, the cows want to minimize the number of flips they have to make. Help the cows determine the minimum number of flips required, and the locations to flip to achieve that minimum. If there are multiple ways to achieve the task with the minimum amount of flips, return the one with the least lexicographical ordering in the output when considered as a string. If the task is impossible, print one line with the word &#34;IMPOSSIBLE&#34;. </span></p>
<div><span style="font-size: medium"> 约翰知道，那些高智力又快乐的奶牛产奶量特别高．所以他做了一个翻瓦片的益智游戏来娱乐奶牛．在一个M×N(1≤M，N≤15)的骨架上，每一个格子里都有一个可以翻转的瓦片．瓦片的一面是黑色的，而另一面是白色的．对一个瓦片进行翻转，可以使黑变白，也可以使白变黑．然而，奶牛们的蹄子是如此的巨大而且笨拙，所以她们翻转一个瓦片的时候，与之有公共边的相邻瓦片也都被翻转了．那么，这些奶牛们最少需要多少次翻转，使所有的瓦片都变成白面向上呢？如杲可以做到，输出字典序最小的结果（将结果当成字符串处理）．如果不能做到，输出“IMPOSSIBLE”．</span></div></div>

# Input

<div class="content"><p>* Line 1: Two space-separated integers: M and N</p>
<p>* Lines 2..M+1: Line i+1 describes the colors (left to right) of row i of the grid with N space-separated integers which are 1 for black and 0 for white</p>
<div><span style="font-size: medium">    第1行输入M和N，之后M行N列，输入游戏开始时的瓦片状态．0表示白面向上，1表示黑面向上．</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">* Lines 1..M: Each line contains N space-separated integers, each specifying how many times to flip that particular location.</span></p>
<div><span style="font-size: medium">    输出M行，每行N个用空格隔开的整数，表示对应的格子进行了多少次翻转．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
1 0 0 1<br/>
0 1 1 0<br/>
0 1 1 0<br/>
1 0 0 1<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 0 0 0<br/>
1 0 0 1<br/>
1 0 0 1<br/>
0 0 0 0<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
After flipping at row 2 column 1, the board will look like:<br/>
0 0 0 1<br/>
1 0 1 0<br/>
1 1 1 0<br/>
1 0 0 1<br/>
<br/>
After flipping at row 2 column 4, the board will look like:<br/>
0 0 0 0<br/>
1 0 0 1<br/>
1 1 1 1<br/>
1 0 0 1<br/>
<br/>
After flipping at row 3 column 1, the board will look like:<br/>
0 0 0 0<br/>
0 0 0 1<br/>
0 0 1 1<br/>
0 0 0 1<br/>
<br/>
After flipping at row 3 column 4, the board will look like:<br/>
0 0 0 0<br/>
0 0 0 0<br/>
0 0 0 0<br/>
0 0 0 0<br/>
<br/>
Another solution might be:<br/>
0 1 1 0<br/>
0 0 0 0<br/>
0 0 0 0<br/>
0 1 1 0<br/>
but this solution is lexicographically higher than the solution above.<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

