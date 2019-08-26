
# Description

<div class="content"><p>魔术师的桌子上有n个杯子排成一行，编号为1,2,…,n，其中某些杯子底下藏有一个小球，如果你准确地猜出是哪些杯子，你就可以获得奖品。花费c_ij元，魔术师就会告诉你杯子i,i+1,…,j底下藏有球的总数的奇偶性。<br/>
采取最优的询问策略，你至少需要花费多少元，才能保证猜出哪些杯子底下藏着球？</p></div>

# Input

<div class="content"><p>第一行一个整数n(1&lt;=n&lt;=2000)。<br/>
第i+1行(1&lt;=i&lt;=n)有n+1-i个整数，表示每一种询问所需的花费。其中c_ij（对区间[i,j]进行询问的费用，1&lt;=i&lt;=j&lt;=n,1&lt;=c_ij&lt;=10^9）为第i+1行第j+1-i个数。</p></div>

# Output

<div class="content"><p>输出一个整数，表示最少花费。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2 3 4 5<br/>
4 3 2 1<br/>
3 4 5<br/>
2 1<br/>
5<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Jcvb">鸣谢Jcvb</a></p></div>

