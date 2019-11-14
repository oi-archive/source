# 题目描述

<p>Matthew 已经为UOJ工作了很多年，出过很多令人耳目一新的妙题——但他仍然不怎么会写题面。</p>
<p>而这次为了准备 NOI 而举办的 UNR，由于人手不够，写题面的重担落到了 Matthew 的头上，可是学了八门语言的 Matthew 哪里会使用汉语写作呢，写出来的都是形如 “La main dans la main, nous vivrons ensemble jusqu&#39;à la fin de la vie” 一般，令大多数人不明所以的东西，在绞尽脑汁写题面的过程中，Matthew 不小心睡着了……</p>
<p>Matthew 睡得很沉，还做了个梦，梦见自己来到了 OI 大帝的面前，向 OI 大帝讨教写题面的秘方。</p>
<p>OI 大帝用斯洛僧嘉高里西利斯克语告诉 Matthew，如果你能解出下面的问题，这写题面的秘方便告诉你：</p>
<p>给定参数 $b, c$，求满足以下条件的 $m$ 元组 $(x_1, x_2, \dots, x_m)$ 的方案数：</p>
<ul><li>$x_i \in \mathbb{Z}$，即每个 $x_i$ 都是整数</li>
<li>$0 \leq x_i \leq b^i - c$</li>
<li>$x_1 + x_2 + \dots + x_m &lt; n$.</li>
</ul><p>Matthew 冥思苦想了许久，终于一拍脑袋大叫一声：“我会啦！”</p>
<p>可是梦突然就醒了……</p>
<p>Matthew 茫然的看着电脑，这题面似乎就写好了呢？</p>
<p>那作为正在备战 NOI 的可怜的你，当然得解决 OI 大帝给出的问题啦！</p>
<p>当然，你只需要输出答案对 $998244353$ 取模的结果即可。</p>

# 输入格式


<p>第一行三个整数 $m,b,c$，第二行一个整数 $n$，含义均如前所述。</p>

# 输出格式


<p>一行一个整数表示答案对 $998244353$ 取模的结果。</p>

# 样例一


<h4>input</h4>
<pre>2 2 1
3

</pre>

<h4>output</h4>
<pre>5

</pre>



# explanation


<p>Explication:</p>
<p>Les restrictions sont $x_1 \le 1, x_2 \le 3$.</p>
<p>Les solutions sont $\{0, 0\}, \{0, 1\}, \{0, 2\}, \{1, 0\}, \{1, 1\}$.</p>

# 样例二


<h4>input</h4>
<pre>6 2 0
100

</pre>

<h4>output</h4>
<pre>4705522

</pre>


# explanation


<p>いいえコメントありません</p>

# 样例三


<h4>input</h4>
<pre>50 50 0
5123021850918490285093289038490280918904289058934081194908904690941972871983

</pre>

<h4>output</h4>
<pre>316279832

</pre>


# explanation


<p>Bez komentarza</p>

# 限制与约定


<p>对于 $10\%$ 的数据，$m \le 3, c = 1$；</p>
<p>对于 $30\%$ 的数据，$m \le 15, c = 1$；</p>
<p>对于 $60\%$ 的数据，$c = 1$；</p>
<p>对于 $100\%$ 的数据，$c \in \{0, 1\}, 0 \leq n &lt; b ^ {m + 1}, 2 \le b \le 50, 1 \le m \le 50$.</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=312">样例数据下载</a></p>
