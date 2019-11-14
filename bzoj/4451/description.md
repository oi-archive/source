
# Description

<div class="content"><div>给你一个n*n矩阵的第一行和第一列，其余的数通过如下公式推出： </div>
<div>F[i,j]=a*f[i,j-1]+b*f[i-1,j]+c </div>
<div>求f[n][n]%(10^6+3) </div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行三个数n，a，b，c </div>
<div>第二行n个数，第i个表示f[i][1] </div>
<div>第三行n个数，第i个表示f[1][i] </div>
<div>2&lt;=n&lt;=200000 </div>
<div>其余的数大于等于0小于等于10^6 </div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>仅一个数表示f[n][n]%(10^6+3) </div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">Sample Input1: <br/>
3 0 0 0 <br/>
0 0 2 <br/>
0 3 0 <br/>
<br/>
Sample Input2: <br/>
4 3 5 2 <br/>
7 1 4 3 <br/>
7 4 4 8 </span></div>

# Sample Output

<div class="content"><span class="sampledata">Sample Output1: <br/>
0 <br/>
<br/>
Sample Output2: <br/>
41817 </span></div>

# Hint

<div class="content"><p></p><p>题解:<a href="/JudgeOnline/upload/201603/4451.rar">JudgeOnline/upload/201603/4451.rar</a></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

