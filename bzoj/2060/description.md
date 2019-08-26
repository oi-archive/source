
# Description

<div class="content">经过了几周的辛苦工作,贝茜终于迎来了一个假期.作为奶牛群中最会社交的牛,她希望去拜访N(1&lt;=N&lt;=50000)个朋友.这些朋友被标号为1..N.这些奶牛有一个不同寻常的交通系统,里面有N-1条路,每条路连接了一对编号为C1和C2的奶牛(1 &lt;= C1 &lt;= N; 1 &lt;= C2 &lt;= N; C1&lt;&gt;C2).这样,在每一对奶牛之间都有一条唯一的通路.
FJ希望贝茜尽快的回到农场.于是,他就指示贝茜,如果对于一条路直接相连的两个奶牛,贝茜只能拜访其中的一个.当然,贝茜希望她的假期越长越好,所以她想知道她可以拜访的奶牛的最大数目.
</div>

# Input

<div class="content">第1行:单独的一个整数N
第2..N行:每一行两个整数,代表了一条路的C1和C2.
</div>

# Output

<div class="content">单独的一个整数,代表了贝茜可以拜访的奶牛的最大数目.
</div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
6 2<br/>
3 4<br/>
2 3<br/>
1 2<br/>
7 6<br/>
5 6<br/>
<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
Bessie knows 7 cows. Cows 6 and 2 are directly connected by a road,<br/>
as are cows 3 and 4, cows 2 and 3, etc. The illustration below depicts the<br/>
roads that connect the cows:<br/>
<br/>
                       1--2--3--4<br/>
                          |<br/>
                       5--6--7<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
Bessie can visit four cows. The best combinations include two cows<br/>
on the top row and two on the bottom. She can&#39;t visit cow 6 since<br/>
that would preclude visiting cows 5 and 7; thus she visits 5 and<br/>
7. She can also visit two cows on the top row: {1,3}, {1,4}, or<br/>
{2,4}.<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

