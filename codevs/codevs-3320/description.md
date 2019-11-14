<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>今年夏天，NOI在SZ市迎来了她30周岁的生日。来自全国 n 个城市的OIer们都会从各地出发，到SZ市参加这次盛会。 全国的城市构成了一棵以SZ市为根的有根树，每个城市与它的父亲用道路连接。为了方便起见，我们将全国的n个城市用 1 到 n 的整数编号。其中SZ市的编号为 1。对于除SZ市之外的任意一个城市 v，我们给出了它在这棵树上的父亲城市 fv 以及到父亲城市道路的长度 sv。从城市 v 前往SZ市的方法为：选择城市 v 的一个祖先 a，支付购票的费用，乘坐交通工具到达 a。再选择城市 a 的一个祖先 b，支付费用并到达 b。以此类推，直至到达SZ市。对于任意一个城市 v，我们会给出一个交通工具的距离限制 lv。对于城市 v 的祖先 a，只有当它们之间所有道路的总长度不超过 lv 时，从城市 v 才可以通过一次购票到达城市 a，否则不能通过一次购票到达。对于每个城市 v，我们还会给出两个非负整数 pv,qv 作为票价参数。若城市 v 到城市 a 所有道路的总长度为 d，那么从城市 v 到城市 a 购买的票价为 dpv+qv。每个城市的OIer都希望自己到达SZ市时，用于购票的总资金最少。你的任务就是，告诉每个城市的OIer他们所花的最少资金是多少。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第 1 行包含2个非负整数 n,t，分别表示城市的个数和数据类型（其意义将在后面提到）。 输入文件的第 2 到 n 行，每行描述一个除SZ之外的城市。其中第 v 行包含 5 个非负整数 f_v,s_v,p_v,q_v,l_v，分别表示城市 v 的父亲城市，它到父亲城市道路的长度，票价的两个参数和距离限制。 请注意：输入不包含编号为 1 的SZ市，第 2 行到第 n 行分别描述的是城市 2 到城市 n。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出包含 n-1 行，每行包含一个整数。其中第 v 行表示从城市 v+1 出发，到达SZ市最少的购票费用。 同样请注意：输出不包含编号为 1 的SZ市。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>7 3 </span><br><span>1 2 20 0 3 </span><br><span>1 5 10 100 5 </span><br><span>2 4 10 10 10 </span><br><span>2 9 1 100 10 </span><br><span>3 5 20 100 10 </span><br><span>4 4 20 0 10 </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>40 </span><br><span>150 </span><br><span>70 </span><br><span>149 </span><br><span>300 </span><br><span>150</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于所有测试数据，保证 0≤pv≤10^6，0≤qv≤10^12，1≤fv&lt;v；保证 0&lt;sv≤lv≤2×10^11，且任意城市到SZ市的总路程长度不超过 2×10^11。<br>输入的 t 表示数据类型，0≤t&lt;4，其中：<br>当 t=0 或 2 时，对输入的所有城市 v，都有 fv=v-1，即所有城市构成一个以SZ市为终点的链；<br>当 t=0 或 1 时，对输入的所有城市 v，都有 lv=2×10^11，即没有移动的距离限制，每个城市都能到达它的所有祖先；<br>当 t=3 时，数据没有特殊性质。</p>
</div>
</div>