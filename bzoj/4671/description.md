
# Description

<div class="content"><div>定义两个结点数相同的图 G1 与图 G2 的异或为一个新的图 G, 其中如果 (u, v) 在 G1 与</div>
<div>G2 中的出现次数之和为 1, 那么边 (u, v) 在 G 中, 否则这条边不在 G 中.</div>
<div>现在给定 s 个结点数相同的图 G1...s, 设 S = {G1, G2, . . . , Gs}, 请问 S 有多少个子集的异</div>
<div>或为一个连通图?</div>
<p></p></div>

# Input

<div class="content"><div>第一行为一个整数s, 表图的个数.</div>
<div>接下来每一个二进制串, 第 i 行的二进制串为 gi, 其中 gi 是原图通过以下伪代码转化得</div>
<div>到的. 图的结点从 1 开始编号, 下面设结点数为 n.</div>
<div>Algorithm 1 Print a graph G = (V, E)</div>
<div>for i = 1 to n do</div>
<div>for j = i + 1 to n do</div>
<div>if G contains edge (i, j) then</div>
<div>print 1</div>
<div>else</div>
<div>print 0</div>
<div>end if</div>
<div>end for</div>
<div>end for</div>
<div> 2 ≤ n ≤ 10,1 ≤ s ≤ 60.</div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个整数, 表示方案数</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 <br/>
1 <br/>
1 <br/>
0</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

