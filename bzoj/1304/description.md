
# Description

<div class="content"><p>给一棵m个结点的无根树，你可以选择一个度数大于1的结点作为根，然后给一些结点（根、内部结点和叶子均可）着以黑色或白色。你的着色方案应该保证根结点到每个叶子的简单路径上都至少包含一个有色结点（哪怕是这个叶子本身）。 对于每个叶结点u，定义c[u]为从根结点从U的简单路径上最后一个有色结点的颜色。给出每个c[u]的值，设计着色方案，使得着色结点的个数尽量少。</p></div>

# Input

<div class="content"><p>第一行包含两个正整数m, n，其中n是叶子的个数，m是结点总数。结点编号为1，2，…，m，其中编号1，2，… ，n是叶子。以下n行每行一个0或1的整数（0表示黑色，1表示白色），依次为c[1]，c[2]，…，c[n]。以下m-1行每行两个整数a，b（1&lt;=a &lt; b &lt;= m），表示结点a和b 有边相连。</p></div>

# Output

<div class="content"><p>仅一个数，即着色结点数的最小值。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
0<br/>
1<br/>
0<br/>
1 4<br/>
2 5<br/>
4 5<br/>
3 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p><p>M&lt;=10000</p><br/>
<p><span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23px;">N&lt;=5021</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

