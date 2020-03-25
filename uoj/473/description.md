# 题目描述

<p>白云苍狗，沧海桑田。  </p>
<p>白云的眼前只剩下了模糊的一片。  </p>
<p>在若隐若现之中，它看到了一个个小小的珍珠，有一些发着五彩的光芒。这些珍珠是白兔留下来的，每颗珍珠有一个颜色，为 $D$ 种颜色中随机的一种。  </p>
<p>白云想把这些珍珠放进一些小瓶子中，每个瓶子能恰好容纳两颗珍珠。不过它也有要求，每个瓶子必须装满，并且装的都是相同颜色的珍珠。  </p>
<p>白云希望能得到至少 $m$ 个装满珍珠的瓶子，它想知道它的愿望能被实现的概率是多少呢？</p>
<p>有 $n$ 个在范围 $[1,D]$ 内的整数均匀随机变量。  </p>
<p>求至少能选出 $m$ 个瓶子，使得存在一种方案，选择一些变量，并把选出来的每一个变量放到一个瓶子中，满足每个瓶子都恰好装两个值相同的变量的概率。  </p>
<p>请输出概率乘上 $D^n$ 后对 $998244353$ 取模的值。取模部分说明可参考<a href="/problem/472">第一题（随机立方体）</a>。</p>

# 输入格式


<p>输入仅一行，三个用空格隔开的整数 $D,n,m$。</p>

# 输出格式


<p>输出一个整数，表示所求概率乘上 $D^n$ 后对 $998244353$ 取模的结果。</p>

# 样例一


<h4>input</h4>
<pre><code>2 2 1</code></pre>
<h4>output</h4>
<pre><code>2</code></pre>
<h4>explanation</h4>
<p>情况 $1$ : 第一个变量为 $1$，第二个变量为 $1$。</p>
<p>情况 $2$ : 第一个变量为 $1$，第二个变量为 $2$。</p>
<p>情况 $3$ : 第一个变量为 $2$，第二个变量为 $1$。</p>
<p>情况 $4$ : 第一个变量为 $2$，第二个变量为 $2$。  </p>
<p>其中情况 $1$ 和 $4$ 可以把两个变量放到一个瓶子中。 </p>
<p>情况 $2$ 和 $3$ 中两个变量的值不相同，所以不能放到同一个瓶子中。</p>

# 样例二至样例三


<p>见样例数据下载。</p>

# 限制与约定


<p>对于所有测试数据： $0\le m\le 10^9,1\le n\le 10^9,1\le D\le 10^5$。</p>
<p>每个测试点的具体限制见下表：</p>
 <div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>测试点编号</th><th>$D  $ </th><th>$n  $ </th><th>$m  $ </th></tr></thead><tbody><tr><td>$1$</td><td>$\le 2$</td><td>$\le 10$</td><td>$\le n$</td></tr><tr><td>$2$</td><td>$\le 2$</td><td>$\le 20$</td><td>$\le n$</td></tr><tr><td>$3$</td><td>$\le 100$</td><td>$\le 100$</td><td>$\le n$</td></tr><tr><td>$4$</td><td>$\le 100$</td><td>$\le 100$</td><td>$\le n$</td></tr><tr><td>$5$</td><td>$\le 100$</td><td>$\le 100$</td><td>$\le n$</td></tr><tr><td>$6$</td><td>$\le 100$</td><td>$\le 100$</td><td>$\le n$</td></tr><tr><td>$7$</td><td>$\le 100$</td><td>$\le 100$</td><td>$\le n$</td></tr><tr><td>$8$</td><td>$\le 4000$</td><td>$\le 4000$</td><td>$\le n$</td></tr><tr><td>$9$</td><td>$\le 4000$</td><td>$\le 4000$</td><td>$\le n$</td></tr><tr><td>$10$</td><td>$\le 4000$</td><td>$\le 4000$</td><td>$\le n$</td></tr><tr><td>$11$</td><td>$\le 4000$</td><td>$\le 4000$</td><td>$\le n$</td></tr><tr><td>$12$</td><td>$\le 4000$</td><td>$\le 4000$</td><td>$\le n$</td></tr><tr><td>$13$</td><td>$\le 300$</td><td>$\le 1000000000$</td><td>$\le n$</td></tr><tr><td>$14$</td><td>$\le 300$</td><td>$\le 1000000000$</td><td>$\le n$</td></tr><tr><td>$15$</td><td>$\le 300$</td><td>$\le 1000000000$</td><td>$\le n$</td></tr><tr><td>$16$</td><td>$\le 100000$</td><td>$\le 1000000000$</td><td>$\le 0$</td></tr><tr><td>$17$</td><td>$\le 100000$</td><td>$\le 1000000000$</td><td>$\le 1$</td></tr><tr><td>$18$</td><td>$\le 100000$</td><td>$\le 1000000000$</td><td>$\le 2$</td></tr><tr><td>$19$</td><td>$\le 100000$</td><td>$\le 1000000000$</td><td>$\le n$</td></tr><tr><td>$20$</td><td>$\le 100000$</td><td>$\le 1000000000$</td><td>$\le n$</td></tr><tr><td>$21$</td><td>$\le 100000$</td><td>$\le 1000000000$</td><td>$\le n$</td></tr><tr><td>$22$</td><td>$\le 100000$</td><td>$\le 1000000000$</td><td>$\le n$</td></tr><tr><td>$23$</td><td>$\le 100000$</td><td>$\le 1000000000$</td><td>$\le n$</td></tr><tr><td>$24$</td><td>$\le 100000$</td><td>$\le 1000000000$</td><td>$\le n$</td></tr><tr><td>$25$</td><td>$\le 100000$</td><td>$\le 1000000000$</td><td>$\le n$</td></tr></tbody></table></div>

<p><strong>时间限制: 1s</strong></p>
<p><strong>空间限制: 512MB</strong></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=473">样例数据下载</a></p>
