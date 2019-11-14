
# Description

<div class="content"><div>输入一个n*m的矩阵，矩阵的每一个元素都是一个整数，然后有q个询问，每次询问一个子矩阵的权值。矩阵的权值是这样定义的，对于一个整数x，如果它在该矩阵中出现了p次，那么它给该矩阵的权值就贡献p^2。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数n，m表示矩阵的规模。</div>
<div>接下来n行每行m个整数，表示这个矩阵的每个元素。</div>
<div>再下来一行一个整数q，表示询问个数。</div>
<div>接下来q行每行四个正整数x1，y1，x2，y2，询问以第x1行第y1列和第x2行第y2列的连线为对角线的子矩阵的权值。</div>
<p></p></div>

# Output

<div class="content"><div>输出q行每行一个整数回答对应询问。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
1 3 2 1<br/>
1 3 2 4<br/>
1 2 3 4<br/>
8<br/>
1 2 2 1<br/>
1 1 2 1<br/>
1 1 3 4<br/>
1 1 1 1<br/>
2 2 3 3<br/>
3 4 2 2<br/>
1 3 3 1<br/>
2 4 3 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
4<br/>
38<br/>
1<br/>
8<br/>
12<br/>
</span></div>

# Hint

<div class="content"><p></p><div>1&lt;=n,m&lt;=200</div><br/>
<div>q&lt;=100000</div><br/>
<div>|矩阵元素大小|&lt;=2*109</div><br/>
<p></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

