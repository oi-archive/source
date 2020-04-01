
# Description

<div class="content"><div>这是一道卡常大水题，会做的人也不要激动，希望大家不要被卡常。</div>
<div>给定一张N个点的有向完全图，点的编号为1到N，每一条边有两个权值，注</div>
<div>意x到y的边和y到x的边的权值不一定相同。</div>
<div>现在你想选出一些边，使得任意两个点都可以仅经过这些边互相到达，并且</div>
<div>这个边集中每种权值的最大值的和尽量小。保证图中至少有两个点，因此该边集</div>
<div>显然不能为空。</div></div>

# Input

<div class="content"><div>输入的第一行包括一个整数t，表示数据组数。</div>
<div>每组数据的第一行包括一个整数N，表示有向完全图的点数。</div>
<div>接下来是一个N×N的矩阵，第i行第J列的整数Aij当i=j时是0，当i≠j时表</div>
<div>示点i与点j之间的连边的第一种权值。</div>
<div>接下来是一个N×N的矩阵，第i行第j列的整数Bij当i=j时是0，当i≠j时表</div>
<div>示点i与点j之间的连边的第二种权值。</div>
<div>2 ≤ N ≤ 150， 0 ≤ Aij, Bij ≤ 10^9， Aii = Bii = 0</div></div>

# Output

<div class="content"><div>输出一行一个整数，表示最小的和。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
0 1 2<br/>
2 0 1<br/>
1 2 0<br/>
0 3 1<br/>
1 0 3<br/>
3 1 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
一种最优解是选择边1 → 3， 3 → 2， 2 → 1， 两种权值的最大值分别是2， 1<br/>
因此答案是2 + 1 = 3。</span></div>

# Hint

<div class="content"><p></p><div>本题时限较紧，请注意尽量选择效率高的算法。</div><br/>
<div>高维数组寻址的效率不高，因此优化高维数组寻址可以获得很高的效率提升。</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

