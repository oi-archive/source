
# Description

<div class="content"><div>小Q与tangjz正在玩一个有趣的游戏。n块糖果从左往右排成一排，第i颗糖果的能量值为r_i，美味度为s_i。两个</div>
<div>人一开始的能量值分别为A和B，小Q先手，他们轮流做出行动，直到所有糖果都被取完。当前操作方每次可以做以</div>
<div>下两种选择中的一种：</div>
<div>1.不行动，并把机会交给对手，但这需要支付1点能量，如果当前剩余能量为0，则不可以不行动。</div>
<div>2.拿走最左边的糖果，再把机会交给对手，这不需要支付能量，同时还能补充拿走的糖果对应的能量值。</div>
<div>请写一个小Q和tangjz都想让自己拿到的糖果的美味度之和尽量大，他们都会以最佳策略进行游戏。</div>
<div>请写一个程序计算最终两人拿到糖果的美味度之和。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含3个整数n,A,B(1&lt;=n&lt;=150,0&lt;=A,B&lt;=10^9)$，分别表示糖果的个数以及两人的初始能量。</div>
<div>接下来n行，每行两个整数r_i,s_i(0&lt;=r_i&lt;=10^9,0&lt;=s_i&lt;=150)，分别表示从左往右每个糖果的能量值和美味度。</div>
<div>输入数据保证s_1+s_2+...+s_n&lt;=150。</div>
<div></div></div>

# Output

<div class="content"><div>输出一行两个整数，分别表示小Q获得的糖果的美味度之和以及tangjz获得的糖果的美味度之和。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 5 4<br/>
5 7<br/>
4 8</span></div>

# Sample Output

<div class="content"><span class="sampledata">8 7</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获取">本OJ付费获取</a></p></div>

