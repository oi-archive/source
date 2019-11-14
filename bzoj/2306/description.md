
# Description

<div class="content"><p>有向图 G有n个顶点 1,  2, …,  n，点i 的权值为 w(i)。现在有一只蚂蚁，从<br/>
给定的起点 v0出发，沿着图 G 的边爬行。开始时，它的体力为 1。每爬过一条<br/>
边，它的体力都会下降为原来的 ρ 倍，其中ρ 是一个给定的小于1的正常数。而<br/>
蚂蚁爬到某个顶点时的幸福度，是它当时的体力与该点权值的乘积。 <br/>
我们把蚂蚁在爬行路径上幸福度的总和记为 H。很显然，对于不同的爬行路<br/>
径，H 的值也可能不同。小 Z 对 H 值的最大可能值很感兴趣，你能帮助他计算<br/>
吗？注意，蚂蚁爬行的路径长度可能是无穷的。</p></div>

# Input

<div class="content"><p>每一行中两个数之间用一个空格隔开。 <br/>
输入文件第一行包含两个正整数 n,  m，分别表示 G 中顶点的个数和边的条<br/>
数。 <br/>
第二行包含 n个非负实数，依次表示 n个顶点权值 w(1), w(2), …, w(n)。 <br/>
第三行包含一个正整数 v0，表示给定的起点。 <br/>
第四行包含一个实数 ρ，表示给定的小于 1的正常数。 <br/>
接下来 m行，每行两个正整数 x, y，表示&lt;x, y&gt;是G的一条有向边。可能有<br/>
自环，但不会有重边。</p></div>

# Output

<div class="content"><p>仅包含一个实数，即 H值的最大可能值，四舍五入到小数点后一位。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5 <br/>
10.0 8.0 8.0 8.0 15.0 <br/>
1 <br/>
0.5 <br/>
1 2 <br/>
2 3 <br/>
3 4 <br/>
4 2 <br/>
4 5 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">18.0 </span></div>

# Hint

<div class="content"><p></p><p>对于 100%的数据， n ≤ 100， m ≤ 1000， ρ ≤ 1 – 10^-6<br/><br/>
， w(i) ≤ 100 (i = 1, 2, …, n)。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day1">Day1</a></p></div>

