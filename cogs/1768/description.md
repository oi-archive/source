# 题目描述


<h3>
【题目描述】
</h3>
<p>
今年夏天，NOI在SZ市迎来了她30周岁的生日。来自全国 $n $个城市的OIer们都会从各地出发，到SZ市参加这次盛会。
</p>
<p>
全国的城市构成了一棵以SZ市为根的有根树，每个城市与它的父亲用道路连接。为了方便起见，我们将全国的$n$个城市用$ 1$ 到$ n$
</p>
<p>
的整数编号。其中SZ市的编号为 $1$。对于除SZ市之外的任意一个城市 $v$，我们给出了它在这棵树上的父亲城市 $f_v$ 以及到父亲城市道路的长度$s_v$。从城市 v 前往SZ市的方法为：选择城市 $v$ 的一个祖先 $a$，支付购票的费用，乘坐交通工具到达 $a$。再选择城市 $a$ 的一个祖先$b$，支付费用并到达$ b$。以此类推，直至到达SZ市。对于任意一个城市 $v$，我们会给出一个交通工具的距离限制 $l_v$。对于城市$ v $的祖先$a$，只有当它们之间所有道路的总长度不超过$ l_v $时，从城市 $v$ 才可以通过一次购票到达城市 $a$，否则不能通过一次购票到达。对于每个城市$v$，我们还会给出两个非负整数 $p_v$,$q_v$ 作为票价参数。若城市$ v $到城市$ a $所有道路的总长度为 $d$，那么从城市 $v $到城市$ a $购买的票价为
</p>
<p>
$d p_v+q_v$。每个城市的OIer都希望自己到达SZ市时，用于购票的总资金最少。你的任务就是，告诉每个城市的OIer他们所花的最少资金是多少。
</p>
<h3>
【输入格式】
</h3>
<p>
输入的第$ 1 $行包含$2$个非负整数 $n,t$，分别表示城市的个数和数据类型（其意义将在后面提到）。 输入文件的第 $2$ 到 $n$
</p>
<p>
行，每行描述一个除SZ之外的城市。其中第 v 行包含 5 个非负整数 $f_v,s_v,p_v,q_v,l_v$，分别表示城市 $v$
</p>
<p>
的父亲城市，它到父亲城市道路的长度，票价的两个参数和距离限制。 请注意：输入不包含编号为 1 的SZ市，第 2 行到第 n 行分别描述的是城市 2到城市 n。
</p>
<h3>
【输出格式】
</h3>
<p>
输出包含 n-1 行，每行包含一个整数。其中第 v 行表示从城市 v+1 出发，到达SZ市最少的购票费用。 同样请注意：输出不包含编号为 1 的SZ市。
</p>
<h3>
【样例输入】
</h3>
<p>
<br/>
</p>
<p>
7 3
</p>
<p>
1 2 20 0 3
</p>
<p>
1 5 10 100 5
</p>
<p>
2 4 10 10 10
</p>
<p>
2 9 1 100 10
</p>
<p>
3 5 20 100 10
</p>
<p>
4 4 20 0 10
</p>
<p>
<br/>
</p>
<h3>
【样例输出】
</h3>
<p>
<br/>
</p>
<p>
40
</p>
<p>
150
</p>
<p>
70
</p>
<p>
149
</p>
<p>
300
</p>
<p>
150
</p>
<p>
<br/>
</p>
<h3>
【提示】
</h3>
<p>
对于所有测试数据，保证 $0≤p_v≤10^6，0≤q_v≤10^{12}，1≤f_v&lt;v$；保证$ 0&lt;s_v≤l_v≤2×10^{11}$，且任意城市到SZ市的总路程长度不超过$ 2×10^{11}$。
</p>
<p>
输入的 t 表示数据类型，$0≤t&lt;4$，其中：
</p>
<p>
当 t=0 或 2 时，对输入的所有城市 v，都有$ f_v=v-1$，即所有城市构成一个以SZ市为终点的链；
</p>
<p>
当 t=0 或 1 时，对输入的所有城市 v，都有 $l_v=2×10^{11}$，即没有移动的距离限制，每个城市都能到达它的所有祖先；
</p>
<p>
当 t=3 时，数据没有特殊性质。
</p>
<p>
<img src="/upload/image/20150529/20150529121625_80416.png" alt=""/> 
</p>
<h3>
【来源】
</h3>
<p>
NOI2014 day2 C
</p>