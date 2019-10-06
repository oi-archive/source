# 题目描述

<p>这天是星期天，早上7点你突然被喊醒：“起床了起床了，你上学快迟到了！”</p>
<p>什么今天不是休息吗？你感到一阵晕眩。</p>
<p>在上学路上，蹭蹭蹭窜出来一个黑衣人，他说：“昨天晚上 IIIS 邪教的恐怖分子为了让 IIIS 的礼拜日 —— 星期八成为休息日，盗取了我们的时光机，回到公元321年刺杀了宣布星期日为休息日的基督教徒罗马帝国皇帝君士坦丁一世。”</p>
<p>这时你的下巴已经吃惊得掉在了地上。</p>
<p>黑衣人说：“他还给我们的时光机改了密码使得我们无法回到过去修正历史！我知道你的黑客技术很高超，请帮我们破解密码吧！”</p>
<p>时光机的密码是一个由 $n$ 个<strong>小写英文字母</strong>组成的字符串 $s$。</p>
<p>时光机有一套判定密码是否正确的方法。首先他定义了函数 $f(t)$，其中 $t$ 是一个字符串，$t_0, \dots, t_{n - 1}$ 依次表示 $t$ 的每个字符：</p>
<p>\begin{equation}
f(t) = \left( \sum_{k = 0}^{n-1}26^{n - k - 1} \times \mathrm{num}(t_k) \right) \bmod p
\end{equation}
其中 $\mathrm{num}(c)$ 表示 $c$ 这个字母在字母表中排第几个（从 $0$ 开始编号，例如 $\mathrm{num}(\texttt{&#39;a&#39;}) = 0$，$\mathrm{num}(\texttt{&#39;g&#39;}) = 6$）。$p$ 是个<strong>素数</strong>。$a \bmod b$ 表示 $a$ 除以 $b$ 的余数。</p>
<p>时光机会把输入的密码 $s$ 旋转 $0, 1, \dots, {n-1}$ 次得到字符串 $a_0, a_1, \dots, a_{n-1}$。所谓旋转就是把原字符串的第一个字符放到字符串最后面去，把原字符串第二个字符作为新的字符串的开始。（你可能需要参照样例解释来更好地理解）</p>
<p>时光机存储了 $n$ 个值 $h_0, h_1, \dots, h_{n - 1}$，假如对于任意一个 $0 \leq k &lt; n$ 的整数 $k$ 都满足 $f(a_k) = h_k$，那么就算密码正确。</p>
<p>现在给你 $n, p$ 和 $h_0, \dots, h_{n - 1}$，请你求出密码。</p>

# 输入格式


<p>第一行两个正整数 $n, p$，含义如前所述。保证 $p &gt; 26$ 且<strong>是一个素数</strong>。</p>
<p>接下来 $n$ 行，每行包含一个非负整数依次表示 $h_0, \dots, h_{n - 1}$。保证 $0 \leq h_0, \dots, h_{n - 1} &lt; p$。</p>

# 输出格式


<p>输出一个由小写英文字母组成的字符串表示正确密码。</p>
<p>保证至少存在一个正确的密码。</p>
<p>如果有多种正确的密码，你只要输出任意一个即可。</p>

# 样例一


<h4>input</h4>
<pre>5 31
10
15
13
16
19

</pre>

<h4>output</h4>
<pre>sbvfk

</pre>

<h4>explanation</h4>
<p>$a_0 = \texttt{&#34;sbvfk&#34;}$，（旋转 $0$ 次）</p>
<p>$a_1 = \texttt{&#34;bvfks&#34;}$，（旋转 $1$ 次）</p>
<p>$a_2 = \texttt{&#34;vfksb&#34;}$，（旋转 $2$ 次）</p>
<p>$a_3 = \texttt{&#34;fksbv&#34;}$，（旋转 $3$ 次）</p>
<p>$a_4 = \texttt{&#34;ksbvf&#34;}$。（旋转 $4$ 次）</p>
<p>依次带入 $f$ 求值得 $10, 15, 13, 16, 19$。</p>
<p>举个例子：$f(\texttt{&#34;sbvfk&#34;}) = \left(26^4 \times 18 + 26^3 \times 1 + 26^2 \times 21 + 26^1 \times 5 + 26^0 \times 10\right) \bmod 31$</p>

# 样例二


<h4>input</h4>
<pre>4 677
0
0
0
0

</pre>

<h4>output</h4>
<pre>aaaa

</pre>


# 限制与约定


<p>对于所有数据，$26 &lt; p \leq 10^9$。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$的规模</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="2">$n \leq 5$</td></tr><tr><td>2</td></tr><tr><td>3</td><td rowspan="3">$n \leq 100$</td></tr><tr><td>4</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="5">$n \leq 10^5$</td></tr><tr><td>7</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=74">样例数据下载</a></p>
