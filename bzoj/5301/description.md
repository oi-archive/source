
# Description

<div class="content"><div>已知一个长度为 n 的整数数列 a[1],a[2],…,a[n] ，给定查询参数 l、r ，问在 [l,r] 区间内，有多少连续子</div>
<div>序列满足异或和等于 k 。</div>
<div>也就是说，对于所有的 x，y (l≤x≤y≤r)，能够满足a[x]^a[x+1]^…^a[y]=k的x，y有多少组。</div>
<div></div></div>

# Input

<div class="content"><div>输入文件第一行，为3个整数n，m，k。</div>
<div>第二行为空格分开的n个整数，即ai，a2,…．an。</div>
<div>接下来m行，每行两个整数lj，rj，表示一次查询。</div>
<div>1≤n，m≤105，O≤k，ai≤105，1≤lj≤rj≤n</div></div>

# Output

<div class="content"><div>输出文件共m行，对应每个查询的计算结果。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 5 1<br/>
1 2 3 1<br/>
1 4<br/>
1 3<br/>
2 3<br/>
2 4<br/>
4 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
2<br/>
1<br/>
2<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Amphetamine整理题面&amp;&amp;codeforces 617E">鸣谢Amphetamine整理题面&amp;&amp;codeforces 617E</a></p></div>

