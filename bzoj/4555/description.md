
# Description

<div class="content"><p>在2016年，佳媛姐姐刚刚学习了第二类斯特林数，非常开心。</p>
<div>现在他想计算这样一个函数的值:</div>
<div><img src="/source/bzoj/4555/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNC8xMTEoMSkucG5n.png" width="437" height="47" alt=""/></div>
<div>S(i, j)表示第二类斯特林数，递推公式为:</div>
<div>S(i, j) = j ∗ S(i − 1, j) + S(i − 1, j − 1), 1 &lt;= j &lt;= i − 1。</div>
<div>边界条件为：S(i, i) = 1(0 &lt;= i), S(i, 0) = 0(1 &lt;= i)</div>
<div>你能帮帮他吗?</div></div>

# Input

<div class="content"><p>输入只有一个正整数</p></div>

# Output

<div class="content"><p> 输出f(n)。由于结果会很大，输出f(n)对998244353(7 × 17 × 223 + 1)取模的结果即可。1 ≤ n ≤ 100000</p></div>

# Sample Input

<div class="content"><span class="sampledata">3</span></div>

# Sample Output

<div class="content"><span class="sampledata">87</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

