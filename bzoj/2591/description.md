
# Description

<div class="content"><p><span style="font-size: medium"><span class="Apple-style-span" style="word-spacing: 0px; font: medium Arial,Microsoft Yahei,Simsun,sans-serif; text-transform: none; color: rgb(0,0,0); text-indent: 0px; white-space: normal; letter-spacing: normal; border-collapse: separate; orphans: 2; widows: 2; webkit-border-horizontal-spacing: 0px; webkit-border-vertical-spacing: 0px; webkit-text-decorations-in-effect: none; webkit-text-size-adjust: auto; webkit-text-stroke-width: 0px"><span class="Apple-style-span" style="font-family: monospace"> Farmer John has noticed that his cows often move between nearby fields. Taking this into account, he wants to plant enough grass in each of his fields not only for the cows situated initially in that field, but also for cows visiting from nearby fields. Specifically, FJ&#39;s farm consists of N fields (1 &lt;= N &lt;= 100,000), where some pairs of fields are connected with bi-directional trails (N-1 of them in total). FJ has designed the farm so that between any two fields i and j, there is a unique path made up of trails connecting between i and j. Field i is home to C(i) cows, although cows sometimes move to a different field by crossing up to K trails (1 &lt;= K &lt;= 20). FJ wants to plant enough grass in each field i to feed the maximum number of cows, M(i), that could possibly end up in that field -- that is, the number of cows that can potentially reach field i by following at most K trails. Given the structure of FJ&#39;s farm and the value of C(i) for each field i, please help FJ compute M(i) for every field i. </span></span></span></p>
<p><span style="font-size: medium"><span class="Apple-style-span" style="word-spacing: 0px; font: medium Arial,Microsoft Yahei,Simsun,sans-serif; text-transform: none; color: rgb(0,0,0); text-indent: 0px; white-space: normal; letter-spacing: normal; border-collapse: separate; orphans: 2; widows: 2; webkit-border-horizontal-spacing: 0px; webkit-border-vertical-spacing: 0px; webkit-text-decorations-in-effect: none; webkit-text-size-adjust: auto; webkit-text-stroke-width: 0px"><span class="Apple-style-span" style="font-family: monospace">FJ发现他的牛经常跑到附近的草地去吃草，FJ准备给每个草地种足够的草供这个草地以及附近草地的奶牛来吃。FJ有N个草地(1&lt;=N&lt;=100000)，有N-1条双向道路连接这些草地，FJ精心设计了这些道路使每两个草地有且仅有一条简单路径连接。第i个草场有Ci头牛，有时候奶牛会走过K条道路到其他草地吃草。FJ想知道每个草场最多可能有的奶牛数量Mi，即所有走过K条道路后可能到达i的奶牛总数。<br/>
</span></span></span></p></div>

# Input

<div class="content"><p><font face="Courier New" size="4">* Line 1: Two space-separated integers, N and K. </font></p>
<p><font face="Courier New" size="4">* Lines 2..N: Each line contains two space-separated integers, i and j (1 &lt;= i,j &lt;= N) indicating that fields i and j are directly connected by a trail. </font></p>
<p><font face="Courier New" size="4">* Lines N+1..2N:</font></p>
<p><font face="Courier New" size="4">Line N+i contains the integer C(i). (0 &lt;= C(i) &lt;= 1000) </font></p></div>

# Output

<div class="content"><p> * Lines 1..N: Line i should contain the value of M(i).</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 2<br/>
5 1<br/>
3 6<br/>
2 4<br/>
2 1<br/>
3 2<br/>
1<br/>
2<br/>
3<br/>
4<br/>
5<br/>
6<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">15<br/>
21<br/>
16<br/>
10<br/>
8<br/>
11<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

