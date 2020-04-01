
# Description

<div class="content"><div>Alice设计了一个树结构，有 N 个结点（包括根）被依次编号为 1 到 N ，由 N-1 条边连接。后来，Bob在上面增</div>
<div>加了 K 条原来没有的边（也就是说既不是自环，也不会因此产生重边）并称这样得到的图为“K-嫁接树”。现在A</div>
<div>lice希望对嫁接树的每一个结点进行染色，允许使用的颜色恰有 N 种，分别编号为 1 到 N 。Alice要求相邻两个</div>
<div>结点要涂上不同的颜色。假设颜色为 i 的结点有 ti 个，则Bob给出了如下的评价分数：</div>
<div><img src="/source/bzoj/4089/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNS_ml6DmoIfpopgoMykucG5n.png" width="401" height="86" alt=""/></div>
<div>其中 P 为非负系数。现在，Alice希望可以找到一种染色方案，使得Bob给出来的评分最大。你能帮助他吗？</div>
<div></div></div>

# Input

<div class="content"><div>第一行有 2 个整数，依次为 N 和 K，如题所述。</div>
<div>第二行到第 N+K 行，每行有两个整数 u 和 v ，依次给出了 N+K-1 条边。</div>
<div>保证不存在自环，也不存在重边。</div>
<div>最后一行给定非负浮点数 P 。</div>
<div>K≤2；1≤N≤20000；0≤P&lt;10</div>
<div></div></div>

# Output

<div class="content"><p>输出最大的可能评分，四舍五入保留到小数点后第三位。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">9 0 <br/>
1 2 <br/>
1 3 <br/>
1 4 <br/>
1 5 <br/>
2 6 <br/>
2 7 <br/>
2 8 <br/>
2 9 <br/>
2.5</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.253</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

