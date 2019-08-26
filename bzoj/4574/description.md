
# Description

<div class="content"><div>小Yuuka遇到了一个题目：有一个序列a_1,a_2,?,a_n，q次操作，每次把一个区间内的数改成区间内的最大值，问</div>
<div>最后每个数是多少。小Yuuka很快地就使用了线段树解决了这个问题。于是充满智慧的小Yuuka想，如果操作是随机</div>
<div>的，即在这q次操作中每次等概率随机地选择一个区间[l,r](1≤l≤r≤n)，然后将这个区间内的数改成区间内最大</div>
<div>值（注意这样的区间共有(n(n+1))/2个），最后每个数的期望大小是多少呢？小Yuuka非常热爱随机，所以她给出</div>
<div>的输入序列也是随机的（随机方式见数据规模和约定）。对于每个数，输出它的期望乘((n(n+1))/2)^q再对10</div>
<div>^9+7取模的值。</div>
<p></p></div>

# Input

<div class="content"><p>第一行包含2个正整数n,q，表示序列里数的个数和操作的个数。接下来1行，包含n个非负整数a1,a2...an。N&lt;=400,Q&lt;=400</p>
<p></p></div>

# Output

<div class="content"><p>输出共1行，包含n个整数，表示每个数的答案</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
1 5 2 3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">3152671 3796875 3692207 3623487 3515626</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

