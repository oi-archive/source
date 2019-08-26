
# Description

<div class="content"><div>SHUXK 正在对一棵N个结点的有根树进行研究，首要的一件事就是对这棵树进行编码。</div>
<div>lz 说：“这还不容易吗？我令根节点的编号为 1，然后保证每个结点的编号都比它的父亲结点的编号大。这样不</div>
<div>就行了吗？”但 SHUXK 对这种编码方案并不满意，因为没什么特色，从中也得不到什么有用的信息。于是他想出</div>
<div>了一种新的编码，这种编码需要满足两个条件：</div>
<div>1. 作为一个 OIer，应该保证每个结点的编码是一个 01 串；</div>
<div>2. 为了体现树的特点，假设??号结点的编码为Si，应该有如下性质：</div>
<div>如果结点U是结点V的祖先，那么Su就应该是Sv的前缀；</div>
<div>如果结点U不是结点V的祖先或后代，那么Su就不允许是Sv的前缀。</div>
<div>lz 说：“ 这样编码确实有特色。 但是这样一来，编码会很长呀！”</div>
<div>SHUXK 说：“我们就来求一种最优的编码，使得所有结点的编码长度之和最小。”当然， lz 和 SHUXK 都已经从 </div>
<div>OI 界退役了，他们讨论完了以后就把这个任务交给你了。</div>
<p></p></div>

# Input

<div class="content"><div>输入文件的第一行包含一个正整数N(N&lt;=10^5)，表示棋盘的大小。</div>
<div>第二行包含N - 1个整数， 分别表示2~N号结点的父亲结点Fi（ 保证Fi&lt;i，也就是说 lz 已经编码好了）。</div>
<p></p></div>

# Output

<div class="content"><div>输出文件只有一行一个整数， 表示所有结点编码长度之和的最小值。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 1 3 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">6</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

