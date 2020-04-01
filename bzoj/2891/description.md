
# Description

<div class="content"><div style="text-indent: 12pt"><span style="font-size: 12pt">给定一个二分图a,b.每条a-&gt;b的边都有一个存在的概率。求期望最大匹配数。</span></div></div>

# Input

<div class="content"><div style="text-indent: 12pt"><span style="font-size: 12pt">第一行两个整数</span><span style="font-size: 12pt">a,b</span></div>
<div style="text-indent: 12pt"><span style="font-size: 12pt">接下来一个</span><span style="font-size: 12pt">a*b</span><span style="font-size: 12pt">的矩阵表示</span><span style="font-size: 12pt">i-&gt;j</span><span style="font-size: 12pt">这条边存在的概率。</span></div></div>

# Output

<div class="content"><div style="text-indent: 12pt"><span style="font-size: 12pt">一个实数表示期望最大匹配数。保留</span><span style="font-size: 12pt">2</span><span style="font-size: 12pt">位小数（注意</span><span style="font-size: 12pt">C++</span><span style="font-size: 12pt">以及</span><span style="font-size: 12pt">PASCAL</span><span style="font-size: 12pt">对于四舍五入的问题，比如</span><span style="font-size: 12pt">PASCAL</span><span style="font-size: 12pt">对于</span><span style="font-size: 12pt">2.5</span><span style="font-size: 12pt">四舍五入会输出</span><span style="font-size: 12pt">2</span><span style="font-size: 12pt">，建议输出时加一个极小量）</span></div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
3 3<br/>
0.38064 0.30000 0.29486<br/>
0.41715 0.90000 0.67837<br/>
0.53316 1.00000 1.00000<br/>
【输出样例】<br/>
2.575940<br/>
<br/>
<br/>
【输入样例】<br/>
2 2<br/>
0.40000 1.00000<br/>
0.10000 1.00000<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
1.46<br/>
【数据规模和约定】<br/>
10% a*b&lt;=16 <br/>
<br/>
10% a = 1,b &lt;= 100<br/>
10% a = 2,b &lt;= 100<br/>
10% a = 3,b &lt;= 100<br/>
20% a = 4,b &lt;= 100<br/>
20% a = 5,b &lt;= 100<br/>
20% a=6,b&lt;=100</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

