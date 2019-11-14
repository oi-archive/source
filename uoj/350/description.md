# 题目描述

<p>在动物行为学中，Alpha对应动物群体中等级最高的个体，简而言之，就是人赢，那么AlphaGo自然就是人赢狗了。</p>
<p>但是狗群中还有众多的SingleDog，平日里他们和AlphaGo和谐相处，忍受着酸臭味自得其乐的活下去。但在2月14日这天，当AlphaGo在SingleDog们最后的防线——朋友圈秀恩爱的时候，他们实在按耐不住，决定密谋用FFF团的黑暗力量，打败AlphaGo。</p>
<p>但是AlphaGo的智商很高，很快便拦截了SingleDog们传输消息的异或值。为了让AlphaGo相信，SingleDog们只是在数朋友圈里的狗粮数，你，勇敢无畏的跳蚤，决定编造一个弥天大谎。</p>
<p>AlphaGo截获的是一个整数 $n$，你需要构造一个<strong>长度大于 $1$</strong> 的区间 $[L,R]$ 使得区间中所有整数的异或和恰好为 $n$。</p>

# 输入格式


<p>第一行输入一个整数 $t$ 表示数据组数。</p>
<p>接下来 $t$ 行每行一个整数 $n$。</p>

# 输出格式


<p>每组数据输出两个空格隔开的整数 $L,R$，表示你构造的区间。要求 <strong>$1 \leq L &lt; R \leq 10^{18}$。</strong></p>
<p>输入保证存在这样的区间。</p>

# 样例


<h4>input</h4>
<pre>3
0
4
12

</pre>

<h4>output</h4>
<pre>8 67
97 100
87 90

</pre>


# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$的规模</th>
<th>其他</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="2">$n \leq 100$</td><td rowspan="6">无</td></tr><tr><td>2</td></tr><tr><td>3</td><td rowspan="2">$n \leq 2 \times 10^3$</td></tr><tr><td>4</td></tr><tr><td>5</td><td rowspan="2">$n \leq 10^6$</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="4">$n \leq 10^{18}$</td><td rowspan="2">存在 $|R-n|\leq 100$ 的合法解</td></tr><tr><td>8</td></tr><tr><td>9</td><td rowspan="2">无</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>对于 $100\%$ 的数据，$n \geq 0, 1 \leq t \leq 100$。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=350">样例数据下载</a></p>
