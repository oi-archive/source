
# Description

<div class="content"><div>Maishroom拿到了一张H格高W格宽的数表，其中左上角的数是0，其他数都在0到S之间（含）。Maishroom想从左上角走到右下角，每一步只能向下或向右走，使得路径上数之和最大。</div>
<div>这是个有趣的题目，因为有一个正确性显然不对的贪心算法。</div>
<div>Greedily_Act(Now_h, Now_w)</div>
<div>If Now_w == W</div>
<div>    MOVE_DOWN</div>
<div>Else If Now_h == H</div>
<div>    MOVE_RIGHT</div>
<div>Else If V[Now_h][Now_w + 1] &gt;= V[Now_h + 1][Now_w]</div>
<div>    MOVE_RIGHT</div>
<div>Else</div>
<div>    MOVE_DOWN</div>
<div>End</div>
<div>Maishroom知道你们用脚趾头都能做出原来那道题，</div>
<div>于是现在他的问题是：求出有多少种数表，满足在该贪心算法下的答案为S。</div>
<p></p></div>

# Input

<div class="content"><div>一行四个整数，H, W, S, P。P是素数。</div>
<p></p></div>

# Output

<div class="content"><div>一个整数，为答案对P取模的结果。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 2 2 1000000007	</span></div>

# Sample Output

<div class="content"><span class="sampledata">9</span></div>

# Hint

<div class="content"><p></p><div>对于100%的数据：1≤H, W, S≤10^6, 108≤P≤2^30，P是素数。</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

