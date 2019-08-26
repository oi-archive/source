
# Description

<div class="content"><p>小 W 很喜欢序列，尤其喜欢“W”形的和“M”形的序列。定义“M”形<br/>
的序列为一个长度为 T 的序列{Si}，满足：存在 1 &lt; x &lt; y &lt; z &lt; N，使得S1 &lt; ... &lt; <br/>
Sx &gt; ... &gt; Sy &lt; ... &lt; Sz &gt; ... &gt; ST。 <br/>
一天他看到了一个长度为N 的整数序列{Ai}，他想通过一些修改把序列变成<br/>
“M”形的。但这时小 X 过来了，说这个序列是他的，小 W 如果想要修改就要<br/>
支付一定的费用。每支付一单位的费用，小 W 都可以进行这样的操作：将一段<br/>
连续的数同时加上 1，即选定i, j 满足1 ≤ i ≤ j ≤ N 并令Ai, Ai+1, ..., Aj均加上1。 <br/>
小 W 想用最小的费用将序列变成“M”形的。但是有个条件：如果他修改<br/>
成的目标是序列{Bi}满足B1 &lt; ... &lt; Bx &gt; ... &gt; By &lt; ... &lt; Bz &gt; ... &gt; BN， 那么必须有Ay= <br/>
By。 <br/>
现在，他希望你来帮他计算最小费用。</p></div>

# Input

<div class="content"><p>第一行包含一个整数 N，表示序列A的长度。 <br/>
第二行有 N 个整数给出初始的序列{Ai}。</p></div>

# Output

<div class="content"><p>仅包含一行，为最小的花费。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 <br/>
2 1 2 2 3  </span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据满足 5 ≤ N ≤ 100 000，0 ≤ Ai ≤ 10 ^9。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

