# 题目描述

<p>Adnan 拥有巴库最大的鞋店。现在有一个装着 $n$ 双鞋的箱子刚运到他的鞋店。每双鞋是大小相同的两只：一只左脚，一只右脚。Adnan 把这 $n$ 只鞋排成一行，该行总共有 $2n$ 个位置，从左到右编号为 $0$ 到 $2n-1$ 。</p>
<p>Adnan 想把这些鞋子重新排成合法的排列。一个排列是合法的，当且仅当对于所有的 $0 \le i \le n-1$，以下条件都成立：</p>
<ul><li>在位置 $2i$ 和 $2i+1$ 上的鞋子大小相同；</li>
<li>在位置 $2i$ 上的鞋子是一只左脚鞋；</li>
<li>在位置 $2i+1$ 上的鞋子是一只右脚鞋。</li>
</ul><p>为实现上述目标，Adnan 可以做若干次对调。在每次对调中，他选择当前<strong>相邻</strong>的两只鞋进行对调（也就是把它们拿起来，然后将每只鞋子放回到另一只鞋子原来的位置上）。两只鞋子是相邻的，如果其位置编号的差为 $1$ 。</p>
<p>请求出 Adnan 最少要做出多少次对调，才能得到一个合法排列。</p>

# 输入格式


<p>第一行一个正整数 $n$ ，表示有 $n$ 双鞋。</p>
<p>第二行 $i$ 个整数 $S_i$，第 $i$ 个整数表示位置编号为 $i-1$ 的鞋子。其中 $|S_i| $等于最初在位置 $i$ 上的鞋子的大小。这里 $|x|$ 表示 $x$ 的绝对值，当 $x &lt; 0$  时等于 $-x$，当 $x &gt; 0$ 时等于 $x$ 。如果 $S_i &lt; 0$ ,则 $i$ 位置上的鞋子是一只左脚鞋，否则是右脚鞋。</p>

# 输出格式


<p>输出一行一个整数，表示最少对调次数。</p>

# 样例一


<h4>input</h4>
<pre><code class="sh_plain">2
2 1 -1 -2</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">4</code></pre>
<h4>explanation</h4>
<p>Adnan 可以通过 $4$ 次对调而得到一个合法的排列。</p>
<p>例如，他可以先对调 $1$ 和 $-1$，再对调 $1$ 和 $-2$，再对调 $-1$ 和 $-2$。最后对调 $2$ 和 $-2$。随后他就可以得到合法的排列 $[-2,2,-1,1]$。无法用少于 $4$ 次对调就得到合法的排列，因此输出 $4$。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/533/shoes.png" alt="样例一示意图"/></p>

# 样例2


<pre><code class="sh_plain">3
-2 2 2 -2 -2 2</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">1</code></pre>
<h4>explanation</h4>
<p>Adnan 可以对调在位置 $3$ 和 $4$ 上的鞋子来得到合法的排列 $[-2,2,-2,2,-2,2]$，因此应当输出 $1$ 。</p>

# 限制与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试包编号</th><th>附加性质</th><th>分值</th></tr></thead><tbody><tr><td>$1$</td><td>$n=1$</td><td>$10$</td></tr><tr><td>$2$</td><td>$n \le 8$</td><td>$20$</td></tr><tr><td>$3$</td><td>所有鞋子大小相同</td><td>$20$</td></tr><tr><td>$4$</td><td>所有在位置 $0 \sim n-1$ 上的鞋都是左脚鞋，而在位置 $n \sim 2n-1$ 上的鞋都是右脚鞋。而且对于所有 $0 \le i \le n-1$，在位置 $i$ 和 $i+n$ 上的鞋子大小相同</td><td>$15$</td></tr><tr><td>$5$</td><td>$n \le 1000$</td><td>$20$</td></tr><tr><td>$6$</td><td>无特殊性质</td><td>$15$</td></tr></tbody></table></div>

<p>对于所有数据，满足 $1 \le n \le 100000,1 \le |S_i| \le n$。</p>
<p>对于所有数据，满足总存在一种交换方式，使得交换后的排列是一个合法排列。</p>
<p><strong>时间限制:</strong> $1\texttt{s}$</p>
<p><strong>空间限制:</strong> $1\texttt{GB}$</p>
