
# Description

<div class="content"><div><span style="font-size: 16px"> 今年夏天，NOI在SZ市迎来了她30周岁的生日。来自全国 n 个城市的OIer们都会从各地出发，到SZ市参加这次盛会。</span></div>
<div><span style="font-size: 16px">       全国的城市构成了一棵以SZ市为根的有根树，每个城市与它的父亲用道路连接。为了方便起见，我们将全国的</span><span style="font-size: 16px"> </span><span style="font-size: 16px">n</span><span style="font-size: 16px"> </span><span style="font-size: 16px">个城市用 1 到 n 的整数编号。其中SZ市的编号为 1。对于除SZ市之外的任意一个城市 </span><span style="font-size: 16px">v</span><span style="font-size: 16px">，我们给出了它在这棵树上的父亲城市 f</span><sub><span style="font-size: 16px">v</span></sub><span style="font-size: 16px">  以及到父亲城市道路的长度 s</span><sub><span style="font-size: 16px">v</span></sub><span style="font-size: 16px">。</span></div>
<div><span style="font-size: 16px">从城市 v 前往SZ市的方法为：选择城市 v 的一个祖先 a，支付购票的费用，乘坐交通工具到达 a。再选择城市 a 的一个祖先 b，支付费用并到达 b。以此类推，直至到达SZ市。</span></div>
<div><span style="font-size: 16px">对于任意一个城市 v，我们会给出一个交通工具的距离限制 l</span><sub><span style="font-size: 16px">v</span></sub><span style="font-size: 16px">。对于城市 v 的祖先 a，只有当它们之间所有道路的总长度不超过 l</span><sub><span style="font-size: 16px">v</span></sub><span style="font-size: 16px">  时，从城市 v 才可以通过一次购票到达城市 a，否则不能通过一次购票到达。对于每个城市 v，我们还会给出两个非负整数 p</span><sub><span style="font-size: 16px">v</span></sub><span style="font-size: 16px">,q</span><sub><span style="font-size: 16px">v</span></sub><span style="font-size: 16px">  作为票价参数。若城市 v 到城市 a 所有道路的总长度为 d，那么从城市 v 到城市 a 购买的票价为 dp<sub>v</sub>+q<sub>v</sub>。</span></div>
<div><span style="font-size: 16px">每个城市的OIer都希望自己到达SZ市时，用于购票的总资金最少。你的任务就是，告诉每个城市的OIer他们所花的最少资金是多少。</span></div>
<div></div></div>

# Input

<div class="content"><p><span style="font-size: medium">第 1 行包含2个非负整数 n,t，分别表示城市的个数和数据类型（其意义将在后面提到）。输入文件的第 2 到 n 行，每行描述一个除SZ之外的城市。其中第 v 行包含 5 个非负整数 f_v,s_v,p_v,q_v,l_v，分别表示城市 v 的父亲城市，它到父亲城市道路的长度，票价的两个参数和距离限制。请注意：输入不包含编号为 1 的SZ市，第 2 行到第 n 行分别描述的是城市 2 到城市 n。 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">输出包含 n-1 行，每行包含一个整数。其中第 v 行表示从城市 v+1 出发，到达SZ市最少的购票费用。同样请注意：输出不包含编号为 1 的SZ市。 </span></p>
<p class="MsoNormal"><span style="font-size: medium"><span lang="EN-US"> </span></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 3<br/>
1 2 20 0 3<br/>
1 5 10 100 5<br/>
2 4 10 10 10<br/>
2 9 1 100 10<br/>
3 5 20 100 10<br/>
4 4 20 0 10<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> <br/>
40<br/>
150<br/>
70<br/>
149<br/>
300<br/>
150 </span></div>

# Hint

<div class="content"><p></p><p><br/>
</p><p></p><br/>
<p> </p><br/>
<p></p><br/>
<p></p><br/>
<p class="NOI"><span style="font-family: 黑体"><span style="font-size: 16px; font-family: SimSun"><img height="696" alt="" width="732" src="source/bzoj/3672/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNy8xMSg2KS5qcGc=.jpg"/></span></span></p><br/>
<p class="NOI"></p><br/>
<p class="NOI"><span style="font-family: 黑体"><span style="font-size: 16px; font-family: SimSun">对于所有测试数据，保证 0≤p<sub>v</sub>≤10<sup>6</sup>，0≤q<sub>v</sub>≤10<sup>12</sup>，1≤f<sub>v</sub>&lt;v；保证 0&lt;s<sub>v</sub>≤l<sub>v</sub>≤2×10<sup>11</sup>，且任意城市到SZ市的总路程长度不超过 2×10<sup>11</sup>。</span></span></p><br/>
<p class="NOI"><span style="font-family: 黑体"><span style="font-size: 16px; font-family: SimSun">输入的 t 表示数据类型，0≤t&lt;4，其中：</span></span></p><br/>
<p class="NOI"><span style="font-family: 黑体"><span style="font-size: 16px; font-family: SimSun">当 t=0 或 2 时，对输入的所有城市 v，都有 f<sub>v</sub>=v-1，即所有城市构成一个以SZ市为终点的链；</span></span></p><br/>
<p class="NOI"><span style="font-family: 黑体"><span style="font-size: 16px; font-family: SimSun">当 t=0 或 1 时，对输入的所有城市 v，都有 l<sub>v</sub>=2×10<sup>11</sup>，即没有移动的距离限制，每个城市都能到达它的所有祖先；</span></span></p><br/>
<p class="NOI"><span style="font-family: 黑体"><span style="font-size: 16px; font-family: SimSun">当 t=3 时，数据没有特殊性质。</span></span></p><br/>
<p class="NOI"><span style="font-family: 黑体"><span style="font-size: 16px; font-family: SimSun">n=2×10^5</span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

