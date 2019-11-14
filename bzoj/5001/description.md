
# Description

<div class="content"><div>给定一个NM的01矩阵（原矩阵）。每次可以选择原矩阵中任意一个点“搞事情”：具体来说会把原矩阵中选中点与</div>
<div>其上下左右共五个点取反。您要通过最少操作次数使得原矩阵数值全部变成0！然而，您输出的不是最少操作次数</div>
<div>，而是一个NM的答案矩阵。答案矩阵中每个点代表对于原矩阵该点被“搞事情”操作的次数。也就是答案矩阵所有</div>
<div>点数值加起来和为总操作最少次数。由于在相同操作次数下的答案矩阵可能有多个，出题人又懒的不想写SPJ！所</div>
<div>以您需要输出字典序最小的答案矩阵。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数N和M。</div>
<div>接下来是一个NM的01原矩阵。</div>
<div>1 ≤ N，M ≤ 20</div>
<p></p></div>

# Output

<div class="content"><div>输出NM的答案矩阵，<span style="font-size: medium;"><span style="color: rgb(255, 0, 0);">若是无解则输出“IMPOSSlBLE”(这有点坑人了啊！)</span></span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
1 0 0 1<br/>
0 1 1 0<br/>
0 1 1 0<br/>
1 0 0 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 0 0 0<br/>
1 0 0 1<br/>
1 0 0 1<br/>
0 0 0 0</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

