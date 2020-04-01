
# Description

<div class="content"><p><span style="font-size: medium">每天,农夫John需要经过一些道路去检查牛棚N里面的牛. 农场上有M(1&lt;=M&lt;=50,000)条双向泥土道路,编号为1..M. 道路i连接牛棚P1_i和P2_i (1 &lt;= P1_i &lt;= N; 1 &lt;= P2_i&lt;= N). John需要T_i (1 &lt;= T_i &lt;= 1,000,000)时间单位用道路i从P1_i走到P2_i或者从P2_i 走到P１_i 他想更新一些路经来减少每天花在路上的时间.具体地说,他想更新K (1 &lt;= K &lt;= 20)条路经，将它们所须时间减为０．帮助FJ选择哪些路经需要更新使得从１到N的时间尽量少. </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第一行: 三个空格分开的数: N, M, 和 K * 第2..M+1行: 第i+1行有三个空格分开的数：P1_i, P2_i, 和 T_i </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第一行: 更新最多Ｋ条路经后的最短路经长度．</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 1<br/>
1 2 10<br/>
2 4 10<br/>
1 3 1<br/>
3 4 100<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">K是1; 更新道路3-&gt;4使得从３到４的时间由１００减少到０. 最新最短路经是1-&gt;3-&gt;4,总用时为１单位. N&lt;=10000</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

