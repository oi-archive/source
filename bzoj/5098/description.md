
# Description

<div class="content"><div>小Q来到了一台赌博机面前，这台赌博机上将会按顺序依次进行n轮游戏。对于每轮游戏，小Q可以选择玩，也可以</div>
<div>选择跳过。小Q是个游戏高手，因此只要他出手，必能通关那一轮游戏。赌博机为了吸引玩家，设置了一定的奖励</div>
<div>分。具体来说，如果选择玩第i轮游戏，并且这是第k次玩游戏，那么将会获得w_i*(k^2+ak+b)点分数。小Q非常不</div>
<div>会数学，因此他希望你给他写一个程序，帮他计算如果他恰好玩其中的i轮游戏，那么最多能得到多少分？</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含三个整数n,a,b(1&lt;=n&lt;=100000,0&lt;=a,b&lt;=100,a^2&gt;=4b)，分别表示游戏的轮数以及相关参数。</div>
<div>第二行包含n个整数w_1,w_2,...,w_n(|w_i|&lt;=1000)，依次表示每轮游戏的参数。</div>
<div></div></div>

# Output

<div class="content"><div>输出n行，每行一个整数，其中第i行输出恰好玩i轮游戏的最大收益。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 3 2<br/>
1 -1 1 -1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
18<br/>
38<br/>
44<br/>
26</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获取">本OJ付费获取</a></p></div>

