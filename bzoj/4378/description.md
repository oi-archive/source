
# Description

<div class="content"><p>维护一个长度为n的序列，一开始都是0，支持以下两种操作：<br/>
1.U k a 将序列中第k个数修改为a。<br/>
2.Z c s 在这个序列上，每次选出c个正数，并将它们都减去1，询问能否进行s次操作。<br/>
每次询问独立，即每次询问不会对序列进行修改。</p></div>

# Input

<div class="content"><p>第一行包含两个正整数n,m(1&lt;=n,m&lt;=1000000)，分别表示序列长度和操作次数。<br/>
接下来m行为m个操作，其中1&lt;=k,c&lt;=n，0&lt;=a&lt;=10^9，1&lt;=s&lt;=10^9。</p></div>

# Output

<div class="content"><p>包含若干行，对于每个Z询问，若可行，输出TAK，否则输出NIE。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 8<br/>
U 1 5<br/>
U 2 7<br/>
Z 2 6<br/>
U 3 1<br/>
Z 2 6<br/>
U 2 2<br/>
Z 2 6<br/>
Z 2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">NIE<br/>
TAK<br/>
NIE<br/>
TAK</span></div>

# Hint

<div class="content"><p></p><p>鸣谢Claris</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris">鸣谢Claris</a></p></div>

