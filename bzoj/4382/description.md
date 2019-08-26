
# Description

<div class="content"><p>长度为n的一串项链，每颗珠子是k种颜色之一。 第i颗与第i-1,i+1颗珠子相邻，第n颗与第1颗也相邻。<br/>
切两刀，把项链断成两条链。要求每种颜色的珠子只能出现在其中一条链中。<br/>
求方案数量（保证至少存在一种），以及切成的两段长度之差绝对值的最小值。</p></div>

# Input

<div class="content"><p>第一行n,k(2&lt;=k&lt;=n&lt;=1000000)。颜色从1到k标号。<br/>
接下来n个数，按顺序表示每颗珠子的颜色。（保证k种颜色各出现至少一次）。</p></div>

# Output

<div class="content"><p>一行两个整数：方案数量，和长度差的最小值</p></div>

# Sample Input

<div class="content"><span class="sampledata">9 5<br/>
2 5 3 2 2 4 1 1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">4 3</span></div>

# Hint

<div class="content"><p></p><p>四种方法中较短的一条分别是(5),(4),(1,1),(4,1,1)。相差最小值6-3=3。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris">鸣谢Claris</a></p></div>

