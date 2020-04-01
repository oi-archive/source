
# Description

<div class="content"><div>给定一个n*n的矩阵，矩阵中的每个数可能为1或-1。定义一种变换操作：矩阵中的每个数都变成变换前它上下左右</div>
<div>四个数字的乘积（如果某个数上下左右某个位置没有数字，那就取其他数字的乘积）。</div>
<div>例如：</div>
<div><img src="/source/bzoj/5176/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMi8xMSgyKS5wbmc=.png" width="496" height="116" alt=""/></div>
<div>如果一个矩阵经过这样的变换操作后，得到的矩阵和原来的矩阵完全相同，那么我们称这样的矩阵是“优美”的。</div>
<div>（相同指对应位置的数字都相等，不考虑旋转或翻转后的相同。）现在，毛明明在一个空的矩阵中先选了若干个位</div>
<div>置填上了数字，现在他想知道，如果把其他的位置都继续填满，最后得到的矩阵有多少种是“优美”的。</div>
<p></p></div>

# Input

<div class="content"><div>第一行，包含2个整数n、m，分别为矩阵的大小、已填的位置个数。</div>
<div>接下来m行，每行三个整数x、y、z，表示已在矩阵第x行、第y列填上了数字z。</div>
<div>（1&lt;=x,y&lt;=n,z为1或-1，且所有的x互不相同，所有的y互不相同。）</div>
<div>N&lt;=1000</div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个整数，表示“优美”矩阵的个数。</div>
<div>若不论怎么填都不能得到“优美”矩阵，则输出“0”。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 2<br/>
1 1 -1<br/>
4 4 -1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p><p><img src="/source/bzoj/5176/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMi8yMigyKS5wbmc=.png" width="316" height="332" alt=""/></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

