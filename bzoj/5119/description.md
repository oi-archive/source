
# Description

<div class="content"><div>在一个s个点的图中，存在s-n条边，使图中形成了n个连通块，第i个连通块中有ai</div>
<div>个点。现在我们需要再连接n?1条边，使该图变成一棵树。对一种连边方案，设原图中第i个连通块连出了di条边，那么这棵树T的价值为：</div>
<div> <img src="source/bzoj/5119/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcxMi8xMTExMS5wbmc=.png" width="440" height="152" alt=""/></div>
<div>你的任务是求出所有可能的生成树的价值之和，对998244353取模。</div>
<div></div>
<div></div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入的第一行包含两个整数n,m意义见题目描述。</div>
<div>接下来一行有n个整数，第i个整数表示ai(1≤ai&lt;998244353)</div>
<div>你可以由ai计算出图的总点数s，所以在输入中不再给出s的值。</div>
<div>本题共有 20个测试点，每个测试点 5 分。</div>
<div>20%的数据中，n≤500</div>
<div>另外 20% 的数据中，n≤3000</div>
<div>另外 10% 的数据中，n≤10010,m=1</div>
<div>另外 10%的数据中，n≤10015,m=2</div>
<div>另外 20% 的数据中，所有 ai相等。</div>
<div>100% 的数据中，n≤3×10^4,m≤30</div>
<div></div>
<div></div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出包含一行一个整数，表示答案。</div>
<div></div>
<div></div>
<div></div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 1<br/>
2 3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">1728<br/>
样例解释1<br/>
令i表示大小为i的原连通块，我们在连通块之间的连边有以下三种可能:<br/>
2−3−4<br/>
3−2−4<br/>
2−4−3<br/>
价值和为:<br/>
(2×3^2×4×2+3×2^2×4×2+2×4^2×3×2)×(1+2+1)=1728</span></div>

# Hint

<div class="content"><p></p><p> 测评似乎有问题，请自行下数据测<a href="/JudgeOnline/upload/201801/5119.rar">JudgeOnline/upload/201801/5119.rar</a></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

