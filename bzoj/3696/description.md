
# Description

<div class="content"><p><span style="font-size: medium">    首长NOI惨跪，于是去念文化课了。现在，他面对一道化学题。<br/>
    这题的来源是因为在一个奇怪的学校两个化竞党在玩一个奇怪的博弈论游戏。这个游戏很蛋疼，我相信你们也没有兴趣听。<br/>
    由于这个游戏涉及博弈论，因此化竞的同学就要求首长求一个类似SG函数的值。<br/>
    他们手中有一种非常神奇的化合物，它的分子由N个原子组成（不要在意一个原子可能和及其多个原子成键这个细节）。这个分子构成一个树结构，1号分子为根。    若两个原子i、j到它们的最近公共祖先的距离分别是Li和Lj，定义它们的Aij值为：<br/>
Aij=Li  xor Lj<br/>
题目要求对于每一个k(k∈N)，求出两两A值为k的原子对个数。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">  第一行一个整数N。<br/>
  接下来N-1行，每行一个整数p，第新亍的整数表示第i个原子的父亲为p。</font></p></div>

# Output

<div class="content"><p><font size="4">从K=0开始，第k+1行输出两两A值为K的原子对个数，输出到第一个不为零的数为止。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1<br/>
1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">【数据规模与约定】<br/><br/>
用h表示树结构分子的最大深度。<br/><br/>
 N&lt;=10^5,H&lt;=500</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

