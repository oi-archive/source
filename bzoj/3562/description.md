
# Description

<div class="content"><div>科学家最近发现了一种高分子有机化合物 SHTSC。这种物质的分子由单个或多个原子组成,原子之间通过化学键相</div>
<div>互连接。SHTSC 十分不稳定,其原子之间的化学键经常会伴随着炫酷的声音特效和光影效果发生断裂或者重新连接</div>
<div>。然而,令科学家们大为惊异的是,SHTSC 在变化过程中始终保持着一种特殊的性质:即不存在这样的原子序列 a1,a</div>
<div>2,...,an(n&gt;3)满足 a1 与 a2、a2 与a3、......、an-1 与 an 以及 an 与 a1 都通过化学键相连,但它们之间却</div>
<div>没有其他化学键相连的情况。现在科学家将 SHTSC 的原子由 1 到 n 标号,并告诉你SHTSC 的初始形态以及原子之</div>
<div>间的化学键变化情况,他们想知道在实验过程中的某些时刻 SHTSC 分裂成了多少个分子?</div></div>

# Input

<div class="content"><div>第一行两个整数:n, m。表示 SHTSC 的总原子个数以及初始的化学键数。</div>
<div>从第二行开始的 m 行,每行两个整数 a, b (1≤a,b≤n)。表示编号为 a, b 的两</div>
<div>个原子在初始状态中有化学键相连。数据保证每对 a, b 只出现一次。</div>
<div>第 m+2 行有一个整数:q。表示实验的总操作数。</div>
<div>之后 q 行中的每一行为以下三种操作当中的一种:</div>
<div>1、A i j 表示 i 号原子与 j 号原子之间形成了一条新的化学键;</div>
<div>2、D i j 表示 i 号原子与 j 号原子之间原有的化学键断裂了;</div>
<div>3、Q 询问当前 SHTSC 分裂成了多少个不同的分子。</div>
<div>数据保证所有的实验操作都是合法的。</div>
<div>n≤5000,m≤200000,q≤10000。</div></div>

# Output

<div class="content"><p>对于每个 Q 操作,输出一行一个整数,为相应时刻的分子个数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">7 10 <br/>
1 2 <br/>
2 3 <br/>
3 4 <br/>
4 1 <br/>
1 3 <br/>
2 4 <br/>
5 6 <br/>
6 7 <br/>
7 5 <br/>
2 5 <br/>
10 <br/>
Q <br/>
D 2 5 <br/>
Q <br/>
D 5 6 <br/>
D 5 7 <br/>
Q <br/>
A 2 5 <br/>
Q <br/>
A 5 6 <br/>
Q </span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
3<br/>
2<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

