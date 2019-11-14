
# Description

<div class="content"><div>Antonio 最近对有机化学比较感兴趣，他想请你帮助他快速计算出某种烃类的同分异</div>
<div>构体的数目。 </div>
<div>为了表述方便，我们作出如下定义： </div>
<div>  环烷烃： 具有n 个碳原子的环烷烃可以表示成一张具有n 个顶点n 条边的无向连通</div>
<div>简单图(基环+外向树)。每个顶点的度数不超过 4。 </div>
<div>  M-环烷烃：至多有m 个顶点在环上的环烷烃。（注意环上至少有 3 个顶点，因为</div>
<div>任意两个顶点之间至多只能有1 条边）。 </div>
<div> 同构：假设结构A和结构B 均具有n 个碳原子，A和B 同构当且仅当能够对A和</div>
<div>B 中的每个碳原子都按照 1~n 编号，使得对于编号为 v1 和 v2 的两个碳原子，他</div>
<div>们在 A中存在边相连当且仅当他们在 B中存在边相连。（换言之，A和 B对应的图</div>
<div>同构）。 </div>
<div>现在，给出n, m，Antonio 希望你帮助他统计有多少种互不同构的含有n 个碳原子的</div>
<div>m-环烷烃。由于这个数量可能很大，你只需要输出它对p 的余数。（p是一个素数）。 </div>
<div>在本题中，我们不考虑某结构在化学上是否能够稳定存在，也不考虑其他的异构方式。</div></div>

# Input

<div class="content"><p>输入文件只有一行，用空格隔开的三个整数n, m, p 。保证有m &lt;=n,p为素数。</p></div>

# Output

<div class="content"><div>输出文件有且仅有一行，表示具有n 个碳原子的互不同构的m-环烷烃的数量，对 p的</div>
<div>余数。</div></div>

# Sample Input

<div class="content"><span class="sampledata">10 10 66103</span></div>

# Sample Output

<div class="content"><span class="sampledata">476<br/>
</span></div>

# Hint

<div class="content"><p></p><p> 3 &lt;=N&lt;=1000,3&lt;=M&lt;= 50 ，且m&lt;= n ,10^4&lt;=P&lt;= 2*10^9 10 ，且 p 为素数 </p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

