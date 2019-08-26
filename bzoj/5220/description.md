
# Description

<div class="content"><div>Byteasar 最近正在学习数据结构，他遇到了这样一个问题：给定一个长度为n 的序列a1, a2, ..., an 和一个整</div>
<div>数k， 问有多少连续区间[l, r] 满足al ⊕ al+1 ⊕ ... ar-1 ⊕ ar = k？其中“⊕” 表示按位异或运算。当</div>
<div>掌握这类问题的解法的时候，Byteasar 发出感叹：“为什么这么巧妙呢？”小Q 最近也在学习数据结构，当他掌</div>
<div>握了线段树实现区间加操作之后，也发出了同样的感叹。这天，Byteasar 向小Q 普及了他最近新学会的姿势，但</div>
<div>是他们之间产生了分歧：Byteasar 认为异或问题比区间加操作要难，而小Q 则坚持区间加更难。他们一时争执不</div>
<div>下，于是决定询问你的意见。他们将两个问题进行了结合，问题是这样的：给定一个长度为n 的序列a1, a2, ...,</div>
<div> an 和一个整数k，定义一个连续区间[l, r] 是Byteasar 关心的，当且仅当该区间满足al ⊕ al+1 ⊕...ar-1 </div>
<div>⊕ ar = k，其中“⊕” 表示按位异或运算。小Q 的手上一开始是一个长度为n 的全0 序列b1, b2, ..., bn，在B</div>
<div>yteasar 标出所有他关心的区间后，小Q 会进行m 次操作。每次操作他会给出一个区间[st, en] 和一个整数w，对</div>
<div>于每一个Byteasar关心的且是[st, en] 子区间的区间[l, r]，将bl, bl+1, ..., br-1, br 的每个数都加上w。</div>
<div>他们希望你输出所有操作进行完毕之后的b 序列，然后告诉他们异或问题与区间加究竟哪一个更难，相信你一定能</div>
<div>做出这道题，给他们一个满意的答复。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含两个正整数n;m 和一个整数k，分别表示序列的长度、操作的个数和参数k。</div>
<div>第二行包含n 个整数a1, a2, ..., an，表示序列a。</div>
<div>接下来m 行，每行三个整数st, en;w，依次表示每个操作。</div>
<div>0 ≤ k, ai &lt; 2^30, 1 ≤ st ≤ en ≤ n, 0 ≤ w ≤ 10000。</div>
<div></div></div>

# Output

<div class="content"><div>输出一行n 个整数，即b1, b2, ... bn，由于答案可能很大，请对1073741824取模输出。</div>
<div>N,M &lt; = 150000,Ai&lt; 2 ^30</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 3 7<br/>
5 7<br/>
1 2 3<br/>
2 2 4<br/>
1 1 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 7</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Claris原创，本站版权所有">Claris原创，本站版权所有</a></p></div>

