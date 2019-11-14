# 题目描述

<p>21 世纪，许多人得了一种奇怪的病：起床困难综合症，其临床表现为：起床难，起床后精神不佳。作为一名青春阳光好少年，atm 一直坚持与起床困难综合症作斗争。通过研究相关文献，他找到了该病的发病原因：在深邃的太平洋海底中，出现了一条名为 drd 的巨龙，它掌握着睡眠之精髓，能随意延长大家的睡眠时间。正是由于 drd 的活动，起床困难综合症愈演愈烈，以惊人的速度在世界上传播。为了彻底消灭这种病，atm 决定前往海底，消灭这条恶龙。</p>
<p>历经千辛万苦，atm 终于来到了 drd 所在的地方，准备与其展开艰苦卓绝的战斗。drd 有着十分特殊的技能，他的防御战线能够使用一定的运算来改变他受到的伤害。具体说来，drd 的防御战线由 $n$ 扇防御门组成。每扇防御门包括一个运算 $op$ 和一个参数 $t$，其中运算一定是 $\texttt{OR}, \texttt{XOR}, \texttt{AND}$ 中的一种，参数则一定为非负整数。如果还未通过防御门时攻击力为 $x$，则其通过这扇防御门后攻击力将变为 $x~op~t$。最终drd 受到的伤害为对方初始攻击力 $x$ <strong>依次经过所有 $n$ 扇防御门</strong>后转变得到的攻击力。</p>
<p>由于 atm 水平有限，他的初始攻击力只能为 $0$ 到 $m$ 之间的一个整数（即他的初始攻击力只能在 $0,1,\dots,m$ 中任选，但在通过防御门之后的攻击力不受 $m$ 的限制）。为了节省体力，他希望通过选择合适的初始攻击力使得他的攻击能让 drd 受到最大的伤害，请你帮他计算一下，他的一次攻击最多能使 drd 受到多少伤害。</p>

# 输入格式


<p>第一行包含两个整数，依次为 $n,m$，表示 drd 有 $n$ 扇防御门，atm 的初始攻击力为 $0$ 到 $m$ 之间的整数。</p>
<p>接下来 $n$ 行，依次表示每一扇防御门。每行包括一个字符串 $op$ 和一个非负整数 $t$，两者由一个空格隔开，且 $op$ 在前，$t$ 在后，$op$ 表示该防御门所对应的操作，$t$ 表示对应的参数。</p>

# 输出格式


<p>一行一个整数，表示 atm 的一次攻击最多使 drd 受到多少伤害。</p>

# 样例一


<h4>input</h4>
<pre>3 10
AND 5
OR 6
XOR 7

</pre>

<h4>output</h4>
<pre>1

</pre>

<h4>explanation</h4>
<p>atm可以选择的初始攻击力为 $0, 1, \dots, 10$。</p>
<p>假设初始攻击力为$4$，最终攻击力经过了如下计算
\begin{eqnarray}
4~\texttt{AND}~5 &amp; = &amp; 4\\\\
4~\texttt{OR}~6  &amp; = &amp; 6\\\\
6~\texttt{XOR}~7 &amp; = &amp; 1\\\\
\end{eqnarray}
类似的，我们可以计算出初始攻击力为 $1,3,5,7,9$ 时最终攻击力为 $0$，初始攻击力为 $0,2,4,6,8,10$ 时最终攻击力为 $1$，因此 atm 的一次攻击最多使 drd 受到的伤害值为 $1$。</p>

# 样例二


<p>见“样例数据下载”</p>

# 限制与约定


<p>所有测试数据的范围和特点如下表所示</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n, m$的规模</th>
<th>约定</th>
<th>备注</th>
</tr></thead><tbody><tr><td>1</td><td>$2 \leq n \leq 100, m = 0$</td><td rowspan="10">$0 \leq t &lt; 2^{30}$<br/>$op$一定为$\texttt{OR}, \texttt{XOR}, \texttt{AND}$中的一种</td><td></td>
</tr><tr><td>2</td><td rowspan="2">$2 \leq n \leq 1000, 1 \leq m \leq 1000$</td><td></td>
</tr><tr><td>3</td><td></td>
</tr><tr><td>4</td><td rowspan="3">$2 \leq n, m \leq 10^5$</td><td>存在一扇防御门为$\texttt{AND}~0$</td>
</tr><tr><td>5</td><td>所有防御门的操作均相同</td>
</tr><tr><td>6</td><td></td>
</tr><tr><td>7</td><td rowspan="4">$2 \leq n \leq 10^5, 2 \leq m &lt; 2^{30}$</td><td>所有防御门的操作均相同</td>
</tr><tr><td>8</td><td></td>
</tr><tr><td>9</td><td></td>
</tr><tr><td>10</td><td></td>
</tr></tbody></table></div>

<p>在本题中，<strong>选手需要先将数字变换为二进制后再进行计算</strong>。如果操作的两个数二进制长度不同，则在前补 $0$ 至相同长度。</p>
<p>$\texttt{OR}$ 为按位或运算，处理两个长度相同的二进制数，两个相应的二进制位中只要有一个为 $1$，则该位的结果值为 $1$，否则为 $0$。</p>
<p>$\texttt{XOR}$ 为按位异或运算，对等长二进制模式或二进制数的每一位执行逻辑异或操作。如果两个相应的二进制位不同（相异），则该位的结果值为 $1$，否则该位为 $0$。</p>
<p>$\texttt{AND}$ 为按位与运算，处理两个长度相同的二进制数，两个相应的二进制位都为 $1$，该位的结果值才为 $1$，否则为 $0$。</p>
<p>例如，我们将十进制数 $5$ 与十进制数 $3$ 分别进行 $\texttt{OR}$，$\texttt{XOR}$ 与 $\texttt{AND}$ 运算，可以得到如下结果：</p>
<div class="row">
<div class="col-sm-4">
<pre>    0101 (十进制 5)
 OR 0011 (十进制 3)
  = 0111 (十进制 7)
</pre>
</div>
<div class="col-sm-4">
<pre>    0101 (十进制 5)
XOR 0011 (十进制 3)
  = 0110 (十进制 6)
</pre>
</div>
<div class="col-sm-4">
<pre>    0101 (十进制 5)
AND 0011 (十进制 3)
  = 0001 (十进制 1)
</pre>
</div>
</div>

<p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=2">样例数据下载</a></p>
