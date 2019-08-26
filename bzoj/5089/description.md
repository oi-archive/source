
# Description

<div class="content"><div>
<div>给出一个长度为 n 的序列，要求支持如下两种操作：</div>
<div>A  l  r  x ：将 [l,r] 区间内的所有数加上 x ；</div>
<div>Q  l  r ： 询问 [l,r] 区间的最大连续子段和。</div>
<div>其中，一个区间的最大连续子段和指的是：该区间所有子区间的区间和中的最大值（本题中子区间包括空区间，区间和为 0 ）。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数 n、m，表示序列的长度以及操作的数目。</div>
<div>之后的 m 行，每行输入一个操作，含义如题目所述。保证操作为  A  l  r  x  或  Q  l  r  之一。</div>
<div>对于 30% 的数据，n,m≤300 ；</div>
<div>对于 60% 的数据，n,m≤1000 ；</div>
<div>对于 100% 的数据，1≤n,m≤50000, |a_i |≤〖10〗^9, 1≤x≤40000, 1≤l,r≤n</div>
<p></p></div>

# Output

<div class="content"><div>每个 Q 操作输出一行，表示询问区间的最大连续子段和。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
2 -3 0 4 -7<br/>
Q 1 2<br/>
Q 1 5<br/>
A 2 3 2<br/>
Q 2 5<br/>
Q 1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
4<br/>
6<br/>
3<br/>
样例解释<br/>
第一、二个 Q 操作时序列为 2,-3,0,4,-7 ，[1,2] 的最大连续子段和为空区间的区间和 0 ，<br/>
[1,5] 的最大连续子段和为 [4,4] 的区间和 4 ；<br/>
第三、四个 Q 操作时序列为 2,-1,2,4,-7 ，[2,5] 的最大连续子段和为 [3,4] 的区间和 6 ，<br/>
[1,3] 的最大连续子段和为 [1,3] 的区间和 3。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By GXZlegend
">By GXZlegend<br/>
</a></p></div>

