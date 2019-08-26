
# Description

<div class="content"><p><span style="font-size: medium">小Q最近学习了一些图论知识。根据课本，有如下定义。树：无回路且连通的无向图，每条边都有正整数的权值来表示其长度。如果一棵树有N个节点，可以证明其有且仅有N-1 条边。 路径：一棵树上，任意两个节点之间最多有一条简单路径。我们用 dis(a,b)<br/>
表示点a和点b的路径上各边长度之和。称dis(a,b)为a、b两个节点间的距离。  <br/>
 直径：一棵树上，最长的路径为树的直径。树的直径可能不是唯一的。 <br/>
现在小Q想知道，对于给定的一棵树，其直径的长度是多少，以及有多少条边满足所有的直径都经过该边。 <br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第一行包含一个整数N，表示节点数。 <br/>
接下来N-1行，每行三个整数a, b, c ，表示点 a和点b之间有一条长度为c<br/>
的无向边。 </font></p></div>

# Output

<div class="content"><p><font size="4">  <br/>
共两行。第一行一个整数，表示直径的长度。第二行一个整数，表示被所有<br/>
直径经过的边的数量。 <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata"> <br/>
6 <br/>
3  1 1000<br/>
1  4 10<br/>
4  2 100<br/>
4  5 50<br/>
4  6 100<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1110 <br/>
2 <br/>
 <br/>
 <br/>
【样例说明】 <br/>
直径共有两条，3 到2的路径和3到6的路径。这两条直径都经过边(3, 1)和边(1, 4)。</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">对于100%的测试数据：2≤N≤200000，所有点的编号都在1..N的范围内，<br/><br/>
 <br/><br/>
边的权值≤10^9。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

