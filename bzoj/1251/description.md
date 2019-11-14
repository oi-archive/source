
# Description

<div class="content"><p>网上有许多题，就是给定一个序列，要你支持几种操作：A、B、C、D。一看另一道题，又是一个序列 要支持几种操作：D、C、B、A。尤其是我们这里的某人，出模拟试题，居然还出了一道这样的，真是没技术含量……这样 我也出一道题，我出这一道的目的是为了让大家以后做这种题目有一个“库”可以依靠，没有什么其他的意思。这道题目 就叫序列终结者吧。 【问题描述】 给定一个长度为N的序列，每个序列的元素是一个整数（废话）。要支持以下三种操作： 1. 将[L,R]这个区间内的所有数加上V。 2. 将[L,R]这个区间翻转，比如1 2 3 4变成4 3 2 1。 3. 求[L,R]这个区间中的最大值。 最开始所有元素都是0。</p></div>

# Input

<div class="content"><p>第一行两个整数N，M。M为操作个数。 以下M行，每行最多四个整数，依次为K，L，R，V。K表示是第几种操作，如果不是第1种操作则K后面只有两个数。</p></div>

# Output

<div class="content"><p>对于每个第3种操作，给出正确的回答。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
1 1 3 2<br/>
1 2 4 -1<br/>
2 1 3<br/>
3 2 4<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
【数据范围】<br/>
N&lt;=50000，M&lt;=100000。<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

