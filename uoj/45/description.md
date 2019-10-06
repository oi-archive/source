# 题目描述

<p>小强和阿米巴是好朋友。</p>
<p>阿米巴告诉小强，变形虫（又叫阿米巴虫）和绝大多数生物一样，也是有 DNA 的。并且，变形虫可以通过分裂的方式进行无性繁殖。</p>
<p>我们把一个变形虫的基因组抽象成一个大小为 $L$ 的基因集合。每个基因都是一个 $4$ 位长的字符串（字符包括大小写字母、数字、符号“<samp>~!@#$%^&amp;()[]`:;&#34;&#39;&lt;&gt;,.?/|\=-{}</samp>”）。现在，有 $N$ 个变形虫凑到了一起。由于他们是从天南海北过来的，我们可以认为，他们的基因组都是从一个大小为 $M$ 的“变形虫基因库“中独立的随机的选取L个基因得到的。目前人类并不了解这个基因库里都有什么基因，但是我们知道它的大小是 $M$。</p>
<p>这时，环境突然发生巨变。这 $N$ 个变形虫在外界的刺激下同时进行了一次分裂。每个变形虫分裂成了两个。分裂的过程中，原来的变形虫的基因组（基因的集合）被原样的复制成了两份，分别进入两个新的变形虫。两个新变形虫中的一只的基因组中有一半发生了突变，被替换为“变形虫基因库”中随机的其他的基因。如果两个变形虫是由原来的一个变形虫产生的，我们叫它们“同源”的。</p>
<p>给出 $2N$ 个变形虫的基因组，请你找出每个变形虫同源的另一只虫是谁。</p>

# 输入格式


<p>第一行三个整数 $N$、$M$、$L$。</p>
<p>接下来一行 $2NL \times 4$个字符，依次表示每个集合中的元素。集合内的元素之间的顺序是无关紧要的。</p>

# 输出格式


<p>输出 $2N$ 行，每行一个整数表示第 $i$ 个变形虫（从 $1$ 开始标号）同源的另一只变形虫是谁。</p>

# 样例一


<h4>input</h4>
<pre>2 100 6
H[P,86(^,&lt;n&amp;7X_Sg&#34;LY67m2H$n+5&#39;!VHp5IA.@GM:4-NJsqsiG!H[P,7X_S86(^&gt;aNQ22&#39;B5&#39;!V&lt;FD!F!6xNJsq&gt;!]dHp5I

</pre>

<h4>output</h4>
<pre>3
4
1
2

</pre>


# 样例二


<p>见样例数据下载</p>
<h4>explanation</h4>
<p>输入文件一共有两行。四个基因组分别是</p>
<p>“<samp>H[P,</samp>”，“<samp>86(^</samp>”，“<samp>,&lt;n&amp;</samp>”，“<samp>7X_S</samp>”，“<samp>g&#34;LY</samp>”， “<samp>67m2</samp>”</p>
<p>“<samp>H$n+</samp>”，“<samp>5&#39;!V</samp>”，“<samp>Hp5I</samp>”，“<samp>A.@G</samp>”，“<samp>M:4-</samp>”，“<samp>NJsq</samp>”</p>
<p>“<samp>siG!</samp>”，“<samp>H[P,</samp>”，“<samp>7X_S</samp>”，“<samp>86(^</samp>”，“<samp>&gt;aNQ</samp>”，“<samp>22&#39;B</samp>”</p>
<p>“<samp>5&#39;!V</samp>”，“<samp>&lt;FD!</samp>”，“<samp>F!6x</samp>”，“<samp>NJsq</samp>”，“<samp>&gt;!]d</samp>”，“<samp>Hp5I</samp>”</p>
<p>明显，1、3是同源的，2、4是同源的。</p>

# 限制与约定


<p>一共有 $10$ 个测试点。数据均为按照题目中描述的方法随机生成的。对于非同源的两个变形虫，他们的基因组的交的大小均小于 $L/2$。对于同源的两个变形虫，他们的基因组的交的大小刚好是 $L/2$。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$N$</th>
<th>$M$</th>
<th>$L$</th>
</tr></thead><tbody><tr><td>1</td><td>$400$</td><td>$400$</td><td>$20$</td></tr><tr><td>2</td><td>$900$</td><td>$900$</td><td>$30$</td></tr><tr><td>3</td><td>$1600$</td><td>$1600$</td><td>$40$</td></tr><tr><td>4</td><td>$2500$</td><td>$2500$</td><td>$50$</td></tr><tr><td>5</td><td>$3600$</td><td>$3600$</td><td>$60$</td></tr><tr><td>6</td><td>$6400$</td><td>$6400$</td><td>$80$</td></tr><tr><td>7</td><td>$10000$</td><td>$10000$</td><td>$100$</td></tr><tr><td>8</td><td>$12100$</td><td>$12100$</td><td>$110$</td></tr><tr><td>9</td><td>$14400$</td><td>$14400$</td><td>$120$</td></tr><tr><td>10</td><td>$16900$</td><td>$16900$</td><td>$130$</td></tr></tbody></table></div>

<p>最大的一个测试数据的大小是 $17\texttt{MB}$ 左右（$2NL \times 4=17576000$）。在测评系统上，由于磁盘缓存的存在，使用 scanf 将数据读入需要的时间小于 $0.1$ 秒。请不要使用 cin。经测试：</p>
<ul><li>一个实现良好的 $O(N^2L)$时间复杂度的算法能拿 30 分，</li>
<li>一个实现良好的 $O(N^2 + N^2L^2 / M)$时间复杂度的算法能拿 50 分。</li>
</ul><p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$256\texttt{MB}$</p>

# 来源


<p>中国国家队清华集训2014~2015 Day 4 - By 范浩强</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=45">样例数据下载</a></p>
