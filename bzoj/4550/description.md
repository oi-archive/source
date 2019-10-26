
# Description

<div class="content"><div>
<div>这个游戏是在一个1*n的棋盘上进行的，棋盘上有k个棋子，一半是黑色，一半是白色。最左边是白色棋子，最右边</div>
<div>是黑色棋子，相邻的棋子颜色不同。</div>
</div>
<div> <img width="449" height="87" alt="" src="/source/bzoj/4550/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNC9kZCg2KS5wbmc=.png"/></div>
<div>
<div>小奇可以移动白色棋子，提比可以移动黑色的棋子，它们每次操作可以移动1到d个棋子。每当移动某一个棋子时，</div>
<div>这个棋子不能跨越两边的棋子，当然也不可以出界。当谁不可以操作时，谁就失败了。小奇和提比轮流操作，现在</div>
<div>小奇先移动，有多少种初始棋子的布局会使它有必胜策略？</div>
</div>
<p></p></div>

# Input

<div class="content"><div>共一行，三个数，n，k，d。对于100%的数据，有1&lt;=d&lt;=k&lt;=n&lt;=10000, k为偶数，k&lt;=100。</div>
<p></p></div>

# Output

<div class="content"><div>输出小奇胜利的方案总数。答案对1000000007取模。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 4 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">182</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Hzwer">By Hzwer</a></p></div>

