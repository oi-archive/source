
# Description

<div class="content"><p>背景：烁烁很喜欢爬树，这吓坏了树上的皮皮鼠。<br/>
题意：<br/>
给定一颗n个节点的树，边权均为1，初始树上没有皮皮鼠。<br/>
烁烁他每次会跳到一个节点u，把周围与他距离不超过d的节点各吸引出w只皮皮鼠。皮皮鼠会被烁烁吸引，所以会一直待在节点上不动。<br/>
烁烁很好奇，在当前时刻，节点u有多少个他的好朋友---皮皮鼠。<br/>
大意：<br/>
给一颗n个节点的树，边权均为1，初始点权均为0，m次操作：<br/>
Q x：询问x的点权。<br/>
M x d w：将树上与节点x距离不超过d的节点的点权均加上w。</p></div>

# Input

<div class="content"><p>第一行两个正整数：n，m<br/>
接下来的n-1行，每行三个正整数u，v，代表u，v之间有一条边。<br/>
接下来的m行，每行给出上述两种操作中的一种。</p></div>

# Output

<div class="content"><p>对于每个Q操作，输出当前x节点的皮皮鼠数量。</p></div>

# Sample Input

<div class="content"><span class="sampledata">7 6<br/>
1 2<br/>
1 4<br/>
1 5<br/>
2 3<br/>
2 7<br/>
5 6<br/>
M 1 1 2<br/>
Q 5<br/>
M 2 2 3<br/>
Q 3<br/>
M 1 2 1<br/>
Q 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
3<br/>
6<br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据范围：<br/><br/>
n，m&lt;=10^5,|w|&lt;=10^4<br/><br/>
注意：w不一定为正整数，因为烁烁可能把皮皮鼠吓傻了。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

