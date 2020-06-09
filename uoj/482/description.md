# 题目描述

<p>小 S 在和小 F 玩一个叫「斗地主」的游戏。</p>
<p>可怜的小 S 发现自己打牌并打不过小 F，所以他想要在洗牌环节动动手脚。</p>
<p>一副牌一共有 $n$ 张牌，从上到下依次标号为 $1 \sim n$。标号为 $i$ 的牌<strong>分数</strong>是 $f (i)$。在本题，$f (i)$ 有且仅有两种可能：$f (i) = i$ 或 $f (i) = i^2$。</p>
<p>洗牌的方式和我们日常生活中的比较类似，以下我们用形式化的语言来定义：</p>
<p>洗牌环节一共分 $m$ 轮，这 $m$ 轮洗牌依次进行。第 $i$ 轮洗牌时：
1. 小 S 会拿出从最上面往下数的前 $A_i$ 张牌。这样这副牌就被分成了两堆：第一堆是最上面的 $A_i$ 张牌，第二堆是剩下的 $n − A_i$ 张牌，且这两堆牌内相对顺序不变。特别地，当 $A_i = n$ 或 $A_i = 0$ 时，有一堆牌是空的。
2. 接下来对两堆牌进行合并，从而产生新的第三堆牌。当第一堆牌还剩下 $X$ 张，第二堆牌还剩下 $Y$ 张的时候，以 $\frac{X}{X+Y}$ 的概率取出第一堆牌的最下面的牌，并将它放入新的第三堆牌的最上面，$\frac{Y}{X+Y}$ 的概率取出第二堆牌的最下面的牌，并将它放入新的第三堆牌的最上面。
3. 重复操作 2，一直取到两堆牌都为空为止。这样我们就完成了一轮洗牌。</p>
<p>因为洗牌过程是随机的，所以小 S 发现自己没法知道某个位置上具体是哪张牌。但小 S 想问你在经历了这 $m$ 轮洗牌后，某个位置上的牌的<strong>期望分数</strong>是多少。小 S 一共会问你 $Q$ 个这样的问题。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>输入的第一行包含三个正整数 $n, m, \text{type}$，分别表示牌的数量，洗牌的轮数与 $f (i)$ 的类型。当 $\text{type} = 1$ 时，$f (i) = i$。当 $\text{type} = 2$ 时，$f (i) = i^2$。</p>
<p>接下来一行，一共 $m$ 个整数，表示 $A_1 \sim A_m$。</p>
<p>接下来一行一个正整数 $Q$，表示小 S 的询问个数。</p>
<p>接下来 $Q$ 行，每行一个正整数 $c_i$，表示小 S 想要知道从上往下第 $c_i$ 个位置上的牌的<strong>期望分数</strong>。保证 $1 \le c_i \le n$。</p>

# 输出格式


<p>输出到标准输出中。</p>
<p>输出一共 $Q$ 行，每行一个整数，表示答案在模 $998244353$ 意义下的取值。</p>
<p>即设答案化为最简分式后的形式为 $\frac{a}{b}$，其中 $a$ 和 $b$ 互质。输出整数 $x$ 使得 $bx \equiv a\ (\text{mod}\ 998244353)$ 且 $0 \le x &lt; 998244353$。可以证明这样的整数 $x$ 是唯一的。</p>

# 样例一


<h4>input</h4>
<pre><code>4 1 1
3
1
1</code></pre>
<h4>output</h4>
<pre><code>249561090</code></pre>
<h4>explanation</h4>
<p>两棵树相同，所以任意两个点都必须被给予相同的数，方案数为 $2$。</p>
<p>有 $\frac 1 4$ 的概率从上到下的最终结果是 $\{1, 2, 3, 4\}$。</p>
<p>有 $\frac{1}{4}$ 的概率从上到下的最终结果是 $\{1, 2, 4, 3\}$。</p>
<p>有 $\frac{1}{4}$ 的概率从上到下的最终结果是 $\{1, 4, 2, 3\}$。</p>
<p>有 $\frac{1}{4}$ 的概率从上到下的最终结果是 $\{4, 1, 2, 3\}$。</p>
<p>所以最终有 $\frac{1}{4}$ 的概率第一个位置是 $4$，有 $\frac{3}{4}$ 的概率第一个位置是 $1$，所以第一个位置的期望分数是 $\frac{7}{4}$。</p>
<p>为了帮助你们更直观地了解洗牌的过程，我们在下面画出了结果是 $\{1, 4, 2, 3\}$ 的过程：</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/482/douzhudi.webp" style="width:600px;" alt="斗主地"/></p>

# 样例二至样例三


<p>见样例数据下载。</p>

# 限制与约定


<p>对于所有测试数据：$3 \le n \le 10^7 , 1 \le m, Q \le 5 \times 10^5 , 0 \le A_i \le n , \text{type} \in \{1, 2\}$。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>测试点编号</th><th>$n$</th><th>$m$</th><th>$\text{type}=$</th><th>其他性质</th></tr></thead><tbody><tr><td>$1$</td><td>$\le 10$</td><td>$\le 1$</td><td>$1$</td><td>无</td></tr><tr><td>$2$</td><td>$\le 80$</td><td>$\le 80$</td><td>$1$</td><td>无</td></tr><tr><td>$3$</td><td>$\le 80$</td><td>$\le 80$</td><td>$2$</td><td>无</td></tr><tr><td>$4$</td><td>$\le 100$</td><td>$5\times 10^5$</td><td>$2$</td><td>所有$A_i$均相同</td></tr><tr><td>$5$</td><td>$10^7$</td><td>$5\times 10^5$</td><td>$1$</td><td>无</td></tr><tr><td>$6$</td><td>$10^7$</td><td>$5\times 10^5$</td><td>$1$</td><td>无</td></tr><tr><td>$7$</td><td>$10^7$</td><td>$5\times 10^5$</td><td>$1$</td><td>无</td></tr><tr><td>$8$</td><td>$10^7$</td><td>$5\times 10^5$</td><td>$2$</td><td>无</td></tr><tr><td>$9$</td><td>$10^7$</td><td>$5\times 10^5$</td><td>$2$</td><td>无</td></tr><tr><td>$10$</td><td>$10^7$</td><td>$5\times 10^5$</td><td>$2$</td><td>无</td></tr></tbody></table></div>

<p><strong>时间限制: 4s</strong></p>
<p><strong>空间限制: 512MB</strong></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=482">样例数据下载</a></p>
