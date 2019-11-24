# 题目描述

<p>成为鸽王的三个要求之二，优秀的找借口水平。</p>
<p>众所周知，咕咕咕时找的借口不能相似，否则虽然咕掉了事情，但是很有可能因此被人挂起来*。</p>
<p>例如蚂蚁国的代表选手就犯下了重大失误，在某次交互中给出了两个相似的借口，被主持人判了违规。那两个借口看上去差别很大，然而主持人很快就发现，只要进行几次魔改，这两个借口就会变的完全一样。</p>
<p>具体来说，每个借口都可以对应一个$n\times m$的矩阵，且矩阵的每个元素都是不大于$k$的正整数。将一个借口的对应矩阵进行左右翻转某一行或者上下翻转某一列的操作，被称为是对这个借口的一次魔改。</p>
<p>如果一个借口进行若干次魔改后，和另一个借口的对应矩阵完全相同，则称这两个借口是相似的。</p>
<p>主持人突然想要考考码农同学，有多少个有序借口对$(S,T)$满足$S$和$T$是相似的。码农同学仅仅精通找不相似的借口，对这种数数问题自然一无所知，因此来求助你。由于答案可能很大，请对$998244353$取模。</p>

# 输入格式


<p>输入共一行，包含三个正整数 $ n, m, k $ 。</p>

# 输出格式


<p>输出共一行一个非负整数，表示答案。</p>

# 样例一


<h4>input</h4>
<pre><code>2 2 2</code></pre>
<h4>output</h4>
<pre><code>70</code></pre>

# 样例二


<h4>input</h4>
<pre><code>2 3 2</code></pre>
<h4>output</h4>
<pre><code>420</code></pre>

# 样例三


<h4>input</h4>
<pre><code>5 5 3</code></pre>
<h4>output</h4>
<pre><code>985619174</code></pre>

# 样例四


<h4>input</h4>
<pre><code>5 233 99824435</code></pre>
<h4>output</h4>
<pre><code>461607324</code></pre>

# 样例五


<h4>input</h4>
<pre><code>8 9 72</code></pre>
<h4>output</h4>
<pre><code>690487734</code></pre>

# 限制与约定


<p>对于 $ 100 \% $ 的数据，$ 1 \le n \times m \le 5 \times 10^5, 1 \le k &lt; 998244353 $ 。 下表是更详细的数据范围，表中留空代表无特殊限制。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>子任务编号</th><th>$n$</th><th>$n \times m$</th><th>$k$</th><th>分值</th></tr></thead><tbody><tr><td>$1$</td><td></td><td>$\le 15$</td><td>$\le 5$</td><td>$5$</td></tr><tr><td>$2$</td><td></td><td></td><td>$\le 3$</td><td>$8$</td></tr><tr><td>$3$</td><td></td><td>$\le 80$</td><td></td><td>$10$</td></tr><tr><td>$4$</td><td></td><td>$\le 5000$</td><td></td><td>$22$</td></tr><tr><td>$5$</td><td>$\le 5$</td><td></td><td></td><td>$20$</td></tr><tr><td>$6$</td><td></td><td></td><td></td><td>$35$</td></tr></tbody></table></div>

<p><strong>时间限制: $ 5 $s </strong></p>
<p><strong>空间限制: $ 512 $MB </strong></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=485">样例数据下载</a></p>
