
# Description

<div class="content"><div>现在有一棵n个结点的树，对于点i(i&gt;1)，它的父亲结点编号为trunc(i/2)。</div>
<div>现在有m只鸟，每只鸟有初始位置pi。树上每个结点有最大容纳量ci，表</div>
<div>示这个结点最多能容纳的鸟的数量。定义移动一只鸟的代价为树上的距离。</div>
<div>现在询问，对于k从1∼m，将前k只鸟移动位置使得满足每个结点上的</div>
<div>鸟的个数不大于最大容纳量的最小代价。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行两个用空格隔开的整数n,m。n, m ≤ 3 × 10^5</div>
<div>第二行n个整数表示c1,c2,···,cn。</div>
<div>第三行m个整数表示p1,p2,···,pm。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出一行，表示对于每个k的最小代价。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4 <br/>
0 0 4 1 1<br/>
2 4 5 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 1 2 4<br/>
第一只鸟在 2 上，只需移到 4 或 5 即可，代价为 1。<br/>
第一、二只鸟在 2,4 上，第一只鸟移到 5，第二只鸟不动，代价为 1。<br/>
第一、二、三只鸟在 2, 4, 5 上，第一只鸟移到 3，第二、三只鸟不动，代价为 2。<br/>
第一、二、三、四只鸟在 2, 4, 5, 2 上，第一、四只鸟移到 3，第二、三只鸟不动，代价为 4。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

