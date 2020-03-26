# 题目描述

<p>“第七套广播体操，原地踏步——走！”</p>
<p>众所周知，跳蚤们最喜欢每天早起做早操，经常天还没亮就齐刷刷地站在操场做着反复纵跳热热身。跳晚国在研制三星 note7 的时候注意到了这点，于是他们打算让炸弹更快地引爆，这样就可以消灭更多早起的跳蚤。</p>
<p>三星 note7 的主板可以看作是由 $(2n + 1) \times (2n + 1)$ 个中继器构成的，某些中继器会有导线连在一起，左上角和右下角的中继器分别连着电源的正负极。</p>
<p>电流流过一根导线的时间可忽略不计，但当电流经过中继器时，会延缓一段时间再从中继器流出。这个时间只跟该中继器本身有关，我们把这段时间的长度称为中继器的延时值。</p>
<p>这些中继器由导线连接围成一个一个的层，同个层的中继器的种类都一样，而不同层的种类都不一样，可以发现总共有 $n + 1$ 层。当 $n = 4$ 时，主板大概长这样：</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/244/1.png" style="width:500px;" alt="图1"/></p>
<p>跳晚们打算再加几根导线将某些中继器连接起来.凭借发达的重工业，他们能生产出无数条导线。但由于主板的限制，他们的导线只能和主板四周的边平行，且其长度只够连接相邻两个中继器。</p>
<p>现在他们想知道，他们改造的三星 note7 的电源正极流出的电流能在多短的时间到达电源负极从而造成短路，这样电池就会释放出巨大的能量摧毁跳蚤国的有生力量了。</p>
<p>请参考输入格式和样例配图来更好地理解题意。</p>

# 输入格式


<p>第一行一个正整数 $n$。</p>
<p>第二行 $n + 1$ 个正整数 $a_0, a_1, \dots, a_n$，表示从内到外每层的中继器的延时值，单位为秒。其中，第 $i$ 行第 $j$ 列的中继器的延时值为（$1 \le i, j \le n$）
\begin{equation}
a_{\max(\left|i-n-1\right|,\left|j-n-1\right|)}
\end{equation}</p>

# 输出格式


<p>输出一行一个数表示改造后的最短引爆时间。</p>
<p>C/C++ 输入输出 long long 时请用 <code>%lld</code>。C++ 可以直接使用 cin/cout 输入输出。</p>

# 样例一


<h4>input</h4>
<pre>1
1 2

</pre>

<h4>output</h4>
<pre>9

</pre>

<h4>explanation</h4>
<p>这个数据对应的主板如下所示：</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/244/2.png" alt="图2"/></p>
<p>显然，我们可以用导线改造成这样：</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/244/3.png" alt="图3"/></p>
<p>这样从左上角到右下角就会有条 $\{2,2,1,2,2\}$ 的电流路径，耗时为 $9$ 秒。</p>

# 样例二


<h4>input</h4>
<pre>9
9 5 3 7 6 9 1 8 2 4

</pre>

<h4>output</h4>
<pre>69

</pre>


# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
</tr></thead><tbody><tr><td>1</td><td>$n \le 5$</td></tr><tr><td>2</td><td rowspan="2">$n \le 2000$</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="2">$n \le 5000$</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="5">$n \le 10^5$</td></tr><tr><td>7</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>对于所有数据，保证每个数都是不超过 $10^9$ 的正整数。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=244">样例数据下载</a></p>
