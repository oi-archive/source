
# Description

<div class="content"><div>在二分图中，所有点被划分成了两个不相交的集合A和B，每条边都恰好连接着某个A和某个B。一个匹配是一个边集</div>
<div>，满足没有任何两条边有相同的端点。我们称一个匹配M覆盖了点集V当且仅当V中的每个点都是M中至少一条边的端</div>
<div>点。给定一个二分图，每个点有一个正整数权值。定义一个点集的权值为其中所有点的权值之和。给定一个参数t</div>
<div>，请统计有多少点集V，满足V的权值不小于t，且V被至少一个匹配M覆盖。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含两个正整数n,m(1&lt;=n,m&lt;=20)，分别表示A集合的点数和B集合的点数。</div>
<div>接下来n行，每行m个01字符，其中第i行第j列为1表示A_i和B_j之间有一条边。</div>
<div>接下来一行包含n个正整数v_1,v_2,...,v_n(1&lt;=v_i&lt;=10^7)，分别表示A中每个点的权值。</div>
<div>接下来一行包含m个正整数w_1,w_2,...,w_m(1&lt;=w_i&lt;=10^7)，分别表示B中每个点的权值。</div>
<div>最后一行包含一个正整数t(1&lt;=t&lt;=4*10^8)，表示参数t。</div>
<div></div></div>

# Output

<div class="content"><div>输出一行一个整数，即满足条件的点集个数。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
010<br/>
111<br/>
010<br/>
1 2 3<br/>
8 5 13<br/>
21</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
HINT<br/>
3个集合分别为{a1,a2,b2,b3}、{a3,b2,b3}、{a2,a3,b2,b3}。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

