
# Description

<div class="content"><p>有n个房间和n盏灯，你需要在每个房间里放入一盏灯。每盏灯都有一定功率，每间房间都需要不少于一定功率的灯泡才可以完全照亮。<br/>
你可以去附近的商店换新灯泡，商店里所有正整数功率的灯泡都有售。但由于背包空间有限，你至多只能换k个灯泡。<br/>
你需要找到一个合理的方案使得每个房间都被完全照亮，并在这个前提下使得总功率尽可能小。</p></div>

# Input

<div class="content"><p>第一行两个整数n,k(1&lt;=k&lt;=n&lt;=500000)。<br/>
第二行n个整数p[i](1&lt;=p[i]&lt;=10^9)，表示你现有的灯泡的功率。<br/>
第三行n个整数w[i](1&lt;=w[i]&lt;=10^9)，表示照亮每间房间所需要的最小功率。</p></div>

# Output

<div class="content"><p>如果无法照亮每间房间，仅输出NIE。<br/>
否则输出最小的总功率。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 2<br/>
12 1 7 5 2 10<br/>
1 4 11 4 7 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">33</span></div>

# Hint

<div class="content"><p></p><p>解释：将2和10换成4和4。配对方案为1-1,4-4,4-4,5-5,7-7,11-12。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Jcvb">鸣谢Jcvb</a></p></div>

