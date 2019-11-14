
# Description

<div class="content"><div>定义和谐矩阵为长不小于 Mina 且宽不小于 Minb 的矩阵，矩阵的权值为整个矩阵内所有数的和。给定一个长为 N</div>
<div>，宽为 M 的矩阵 A，求它的所有和谐子矩阵中权值第 K 小的矩阵，并输出它的权值。</div>
<div></div></div>

# Input

<div class="content"><div>第 1 行为五个正整数，分别为 N , M , Mina , Minb , K，相邻两个数用一个空格分隔。接下来的 N 行，每行 M</div>
<div> 个用一个空格分隔的数，表示给定的矩阵 A。</div>
<div>1 &lt;= N,M &lt;=1000， 1 &lt;= Mina &lt;= N, 1 &lt;= Minb &lt;= M,</div>
<div>1 &lt;= K &lt;= 250000 ，矩阵 A 内每个数均为不超过 3000 的非负整数</div>
<div></div></div>

# Output

<div class="content"><div>仅一行，一个数，表示第 K 小矩阵的权值。如果第 K 小矩阵不存在，输出-1。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 4 2 2 3<br/>
0 1 3 7<br/>
1 16 5 2<br/>
7 6 9 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">19<br/>
【样例解释】<br/>
对于第一个样例，最小子矩阵为 3 + 7 + 5 + 2 = 17，次小子矩阵为 0 + 1 + 1 + 16 = 18，<br/>
第三小子矩阵为 5 + 2 + 9 + 3 = 19，所以答案为 19。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

