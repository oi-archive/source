# 题目描述

<p>现在的ac程序应该靠谱。。欢迎大家hack<del>（这个题现在标程挂了。。哪位哥哥愿意提供一下靠谱的标程呀？）</del></p>
<p>&#34;分！身！术！&#34; —— 小P</p>
<p>平面上有 $n$ 个小P的分身。定义一组分身占领的区域为覆盖这组分身的最小凸多边形。小P能力有限，每一时刻都会有若干分身消失。但在下一时刻之前，小P会使用</p>
<p>&#34;分！身！术！&#34;</p>
<p>使得这些消失的分身重新出现在原来的位置。小P想知道，每一时刻分身消失后，剩下的分身占领的区域面积是多少？</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>输入第一行包含两个正整数 $n, m$，描述初始时分身的个数，和总时刻数。</p>
<p>接下来 $n$ 行，第 $i$ 行有两个整数 $x_i, y_i$ ，描述第 $i$ 个分身的位置。</p>
<p>接下来 $m$ 行，每行的第一个整数 $k$ 表示这一时刻有 $k$ 个分身消失。接下来有 $k$ 个非负整数 $c_1,c_2,\cdots c_k$，用于生成消失的分身的编号。</p>
<p>生成方式如下：</p>
<p>设上一个时刻中，分身占领面积的<strong>两倍</strong>为 $S$。则该时刻消失的分身 $p_{1}, p_{2}, \dots, p_{k}$ 的编号为：</p>
<p>$$p_i = [(S + c_i) ~\mathrm{mod}~ n] + 1$$</p>
<p>特别的，在第一个时刻，我们认为上一个时刻中， $S=-1$ ，即：第一个时刻消失的分身 $p_{1}, p_{2}, \dots, p_{k}$ 的编号为：</p>
<p>$$p_i = [(-1+c_i) ~\mathrm{mod}~ n] + 1$$</p>

# 输出格式


<p>输出到标准输出。</p>
<p>按给出时刻的顺序依次输出 $m$ 行，每行一个整数，表示该时刻剩余分身所占领区域面积的<strong>两倍</strong>。</p>

# 样例一


<h4>input</h4>
<pre>6 2
-1 0
-1 -1
0 -1
1 0
0 1
0 0
3 1 3 6
2 0 1

</pre>



<h4>output</h4>
<pre>3
2

</pre>

<h4>explanation</h4>
<p>如下图所示：左图表示输入的6个分身的位置及它们占领的区域；中图表示第一个时刻的情形，消失的分身编号分别为 1,3,6，剩余3个点占领图中实线内部区域，占据面积的两倍为 3；右图表示第二个时刻的情形，消失的分身编号分别为 
$$[(0+3) ~\mathrm{mod}~ 6] + 1 = 4$$ 
$$[(1+3) ~\mathrm{mod}~ 6] + 1 = 5$$ </p>
<p>剩余的4个点占领图中实线内部区域。</p>
<p> <img class="img-responsive center-block" src="//img.uoj.ac/problem/319/example.png" alt="样例解释"/></p>

# 样例二


<p>见“样例数据下载”</p>

# 样例三


<p>见“样例数据下载”</p>

# 样例四


<p>见“样例数据下载” </p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点编号</th><th rowspan="1">$n$</th><th rowspan="1">$m$</th><th rowspan="1">$k$</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">10</td><td rowspan="1">10</td><td rowspan="4">$\leq n - 3$</td></tr><tr><td rowspan="1">2</td><td rowspan="3">1000</td><td rowspan="3">1000</td></tr><tr><td rowspan="1">3</td></tr><tr><td rowspan="1">4</td></tr><tr><td rowspan="1">5</td><td rowspan="16">100000</td><td rowspan="16">100000</td><td rowspan="4">$=1$</td></tr><tr><td rowspan="1">6</td></tr><tr><td rowspan="1">7</td></tr><tr><td rowspan="1">8</td></tr><tr><td rowspan="1">9</td><td rowspan="2">$=2$</td></tr><tr><td rowspan="1">10</td></tr><tr><td rowspan="1">11</td><td rowspan="1">$\leq 3$</td></tr><tr><td rowspan="1">12</td><td rowspan="1">$\leq 5$</td></tr><tr><td rowspan="1">13</td><td rowspan="1">$\leq 9$</td></tr><tr><td rowspan="1">14</td><td rowspan="1">$\leq 12$</td></tr><tr><td rowspan="1">15</td><td rowspan="1">$\leq 20$</td></tr><tr><td rowspan="1">16</td><td rowspan="5">$\leq 100$</td></tr><tr><td rowspan="1">17</td></tr><tr><td rowspan="1">18</td></tr><tr><td rowspan="1">19</td></tr><tr><td rowspan="1">20</td></tr></tbody></table></div>

<p>对于所有数据，保证：</p>
<ul><li>$|x_i|, |y_i|\leq 10^{8}$；</li>
<li>没有两个分身的坐标是完全相同的；</li>
<li>$k \leq 100$；</li>
<li>所有时刻的 $k$ 之和不超过 $2 \times 10^{6}$；</li>
<li>$0 \leq c_i \leq 2^{31}-1$；</li>
<li>初始时，所有的 $n$ 个分身占据区域面积大于 $0$；</li>
<li>定义所有 $n$ 个分身所占据区域的<strong>顶点集合</strong>为 $S$， $|S|\geq 3$。在任意时刻，$S$ 中至少存在两个未消失的分身。 </li>
</ul><p><strong>时间限制：</strong>$3\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=319">样例数据下载</a></p>
