# 题目描述

<p><strong>这是一道提交答案题</strong></p>
<p>你是制作团子的专家。你现在有若干个团子和竹签，团子被整体摆放在一个$R$行$C$列的格子里，每个格子恰好有一个团子。团子颜色为粉色($P$),白色($W$),绿色($G$)。</p>
<p>你每次会选择三个连续的团子，这三个团子必须沿着竖直方向(从上往下)，水平方向(从左往右)或者对角线方向(从左上至右下，或从右上至左下)。例如，如果你选择了竖直方向的三个团子，你会按照上-中-下的顺序依次将团子串到竹签上。一个团子只能被串在一根竹签上。</p>
<p>一串团子是漂亮的当且仅当竹签上串的团子的颜色依次为粉-白-绿或者绿-白-粉。</p>
<p>你想要制作尽量多的漂亮的团子。</p>

# 输入格式


<p>这是一道提交答案题，共有 $6$ 组输入数据，这些数据命名为 <code>input_01.txt</code> ~ <code>input_06.txt</code>。</p>
<p>第一行两个正整数$R,C$。</p>
<p>接下来$R$行，每行$C$个字符，表示团子的颜色。第$i+1$行的第$j$个字符代表着第$i$行第$j$列的团子颜色。</p>

# 输出格式


<p>对于每组输入数据，你需要提交相应的输出文件 <code>output_01.txt</code> ~ <code>output_06.txt</code>。</p>
<p>$R$行，每行一个长度为$C$的仅包含<samp>&#39;P&#39;,&#39;W&#39;,&#39;G&#39;,&#39;|&#39;,&#39;-&#39;,&#39;/&#39;,&#39;\&#39;</samp>的字符串，含义如下:</p>
<ul><li>若字符为<samp>&#39;|&#39;</samp>，表示一个使用上方的格子，当前格子，下方的格子的一串团子</li>
<li>若字符为<samp>&#39;-&#39;</samp>，表示一个使用左方的格子，当前格子，右方的格子的一串团子</li>
<li>若字符为<samp>&#39;\&#39;</samp>，表示一个使用左上方的格子，当前格子，右下方的格子的一串团子</li>
<li>若字符为<samp>&#39;/&#39;</samp>，表示一个使用右上方的格子，当前格子，左下方的格子的一串团子</li>
<li>否则字符为输入中该团子的颜色。</li>
</ul>
# 样例一


<h4>input</h4>
<pre><code class="sh_plain">3 4
PWGP
WGPW
GWPG</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">P-GP
WGP|
G-PG</code></pre>
<h4>explanation</h4>
<p>注意不能按照&#39;WGP&#39;的顺序串团子。</p>

# 样例二


<h4>input</h4>
<pre><code class="sh_plain">3 4
PWWP
WWWW
PGGP</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">PWWP
W\/W
PGGP</code></pre>

# 评分标准


<p>对于每个测试点，我们给出四个参数$S,X,Y,Z$。参数如下:</p>
<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$S$</th><th>$X$</th><th>$Y$</th><th>$Z$</th></tr></thead><tbody><tr><td>$1$</td><td>$15$</td><td>44000</td><td>47000</td><td>47220</td></tr><tr><td>$2$</td><td>$15$</td><td>39000</td><td>41700</td><td>41980</td></tr><tr><td>$3$</td><td>$15$</td><td>45000</td><td>51000</td><td>51390</td></tr><tr><td>$4$</td><td>$15$</td><td>18000</td><td>19000</td><td>19120</td></tr><tr><td>$5$</td><td>$20$</td><td>43000</td><td>48200</td><td>48620</td></tr><tr><td>$6$</td><td>$20$</td><td>44000</td><td>46000</td><td>46500</td></tr></tbody></table></div>

<p>对于每个测试点:</p>
<ul><li>若你的输出不合法，你的得分为0。否则设你的方案中漂亮的团子串个数为$N$。</li>
<li>若 $N &lt; X$,你的得分为 0。</li>
<li>若 $X \le N &lt; Y$，你的得分为 $\frac{N-X}{2(Y-X)} \times S$。</li>
<li>若 $Y \le N &lt; Z$，你的得分为 $(\frac{1}{2}+\frac{N-Y}{2(Z-Y)}) \times S$。</li>
<li>若 $Z \le N$，你的得分为 $S$。</li>
</ul>
# 数据范围


<p>对于所有数据，满足$3 \le R,C \le 500$。</p>
<p><a href="http://uoj.ac/download.php?type=problem&amp;id=511">测试数据下载</a></p>
