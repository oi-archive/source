
# Description

<div class="content"><p><span style="font-size: medium">农民 John 的牛参加了一次和农民 Bob 的牛的竞赛。他们在区域中画了一个N*N 的正方形点阵，两个农场的牛各自占据了一些点。当然不能有两头牛处于同一个点。农场的目标是用自己的牛作为4个顶点，形成一个面积最大的正方形(不必须和边界平行) 。 除了 Bessie 以外，FJ其他的牛都已经放到点阵中去了，要确定bessie放在哪个位置，能使得农民约翰的农场得到一个最大的正方形(Bessie不是必须参与作为正方形的四个顶点之一)。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: 一个整数 N，2&lt;=N&lt;=100</span></p>
<p><span style="font-size: medium">* Lines 2..N+1: 第 i+1 行描述点阵的第i行，有 N 个字符。字符集是： &#39;J&#39; 表示这个点是农民 John 的牛， &#39;B&#39;表示这个点是农民 Bob 的牛， &#39;*&#39; 表示这个点没有被占据。保证至少有一个点没有被占据。 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: 最大正方形的面积，或者无解的话输出0。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
J*J***<br/>
******<br/>
J***J*<br/>
******<br/>
**B***<br/>
******<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
<br/>
输出解释:<br/>
<br/>
如果 Bessie 可以占据 农民 Bob 的牛所占的点，那么可以生成一个面积为8<br/>
的正方形，但是她只能放到第3行第3列，形成一个最大的、面积为 4个正方形。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

