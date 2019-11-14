
# Description

<div class="content"><div>小Q和tangjz正在一个长度为n的序列a_1,a_2,...,a_n上玩一个有趣的关于区间翻转的游戏。小Q和tangjz轮流行动</div>
<div>，小Q先手。每次行动方玩家需要选择一个长度为4x+2或4x+3的区间[l,r](1&lt;=l&lt;=r&lt;=n)，其中x是该玩家自行选择</div>
<div>的非负整数，然后将a_l,a_{l+1},...,a_{r-1},a_r翻转，例如1 3 2 5 4翻转会得到4 5 2 3 1。为了防止游戏无</div>
<div>限进行下去，他们规定每次操作之后得到的新序列的字典序必须比操作前的序列大。最先不能采取任何行动的玩家</div>
<div>将会输掉这局游戏。假设小Q和tangjz都会采取最优策略行动，请写一个程序判断谁会获得这局游戏的胜利。</div></div>

# Input

<div class="content"><div>第一行包含一个正整数n(1&lt;=n&lt;=50)，表示序列的长度。</div>
<div>第二行包含n个互不相同的正整数a_1,a_2,...,a_n(1&lt;=a_i&lt;=n)，分别表示序列中的每个元素。</div></div>

# Output

<div class="content"><div>输出一行一个字符，若小Q胜利，输出&#34;Q&#34;；若tangjz胜利，输出&#34;T&#34;（不含引号）。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
4 2 1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">T</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获取">本OJ付费获取</a></p></div>

