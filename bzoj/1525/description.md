
# Description

<div class="content">给出一个N个点M条边的无向图G，定义图G的一个独立集为一个顶点集合V’，满足V’∈V，并且对于任何a∈V’且b∈V’的a和b，不存在(a,b)∈E。
问是否存在顶点个数不小于K的独立集，如果存在，找出顶点个数最多的独立集。
</div>

# Input

<div class="content">
第一行两个正整数N (2 &lt;= N &lt;= 1,000,000)、K (N-10 &lt;= K &lt;= N)。第二行一个正整数M (1 &lt;= M &lt;= 3,000,000)。接着M行，每行两个正整数a和b (1 &lt;= a, b &lt;= N, a ≠ b)，表示一条边。（注意同样的边可能多次出现）
</div>

# Output

<div class="content">如果不存在顶点个数不小于K的独立集，就输出NIE，否则输出最大独立集的顶点个数。
</div>

# Sample Input

<div class="content"><span class="sampledata">9 4<br/>
12<br/>
9 6<br/>
4 6<br/>
7 9<br/>
1 2<br/>
2 1<br/>
9 7<br/>
7 6<br/>
4 5<br/>
7 8<br/>
8 9<br/>
3 4<br/>
4 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p>最大独立集为{1, 3, 5, 6, 8}。<br/>
<br/>
==================================<br/>
鸣谢Oimaster</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

