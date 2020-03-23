# 题目描述

<p>小南有一套可爱的玩具小人，它们各有不同的职业。</p>
<p>有一天，这些玩具小人把小南的眼镜藏了起来。小南发现玩具小人们围成了一个圈，它们有的面朝圈内，有的面朝圈外。如下图：</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/260/toy.png" alt="toy" style="width:500px;"/></p>
<p>这时 <code>singer</code> 告诉小南一个谜题：“眼镜藏在我左数第 $3$ 个玩具小人的右数第 $1$ 个玩具小人的左数第 $2$ 个玩具小人那里。”</p>
<p>小南发现，这个谜题中玩具小人的朝向非常关键，因为朝内和朝外的玩具小人的左右方向是相反的：
面朝圈内的玩具小人，它的左边是顺时针方向，右边是逆时针方向；而面向圈外的玩具小人，它的左边是逆时针方向，右边是顺时针方向。</p>
<p>小南一边艰难地辨认着玩具小人，一边数着：</p>
<p>“<code>singer</code> 朝内，左数第 $3$ 个是 <code>archer</code>。</p>
<p>“<code>archer</code> 朝外，右数第 $1$ 个是 <code>thinker</code>。</p>
<p>“<code>thinker</code> 朝外，左数第 $2$ 个是 <code>writer</code>。</p>
<p>“所以眼镜藏在 <code>writer</code> 这里！”</p>
<p>虽然成功找回了眼镜，但小南并没有放心。如果下次有更多的玩具小人藏他的眼镜，或是谜题的长度更长，他可能就无法找到眼镜了。
所以小南希望你写程序帮他解决类似的谜题。这样的谜题具体可以描述为：</p>
<p>有 $n$ 个玩具小人围成一圈，已知它们的职业和朝向。现在第 $1$ 个玩具小人告诉小南一个包含 $m$ 条指令的谜题，其中第 $i$ 条指令形如“左数/右数第 $s_i$ 个玩具小人”。</p>
<p>你需要输出依次数完这些指令后，到达的玩具小人的职业。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>输入的第一行包含两个正整数 $n,m$，表示玩具小人的个数和指令的条数。</p>
<p>接下来 $n$ 行，每行包含一个整数和一个字符串，以<strong>逆时针</strong>为顺序给出每个玩具小人的朝向和职业。其中 $0$ 表示朝向圈内，$1$ 表示朝向圈外。
保证不会出现其他的数。字符串长度不超过 $10$ 且仅由小写字母构成，字符串不为空，并且字符串两两不同。整数和字符串之间用一个空格隔开。</p>
<p>接下来 $m$ 行，其中第 $i$ 行包含两个整数 $a_i,s_i$，表示第 $i$ 条指令。若 $a_i=0$，表示向左数 $s_i$ 个人；若 $a_i=1$，表示向右数 $s_i$ 个人。
保证 $a_i$ 不会出现其他的数，$1 \le s_i &lt; n$。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>输出一个字符串，表示从第一个读入的小人开始，依次数完 $m$ 条指令后到达的小人的职业。</p>

# 样例一


<h4>input</h4>
<pre>7 3
0 singer
0 reader
0 mengbier
1 thinker
1 archer
0 writer
1 mogician
0 3
1 1
0 2

</pre>


<h4>output</h4>
<pre>writer

</pre>

<h4>explanation</h4>
<p>这组数据就是题目描述中提到的例子。</p>

# 样例二


<h4>input</h4>
<pre>10 10
1 c
0 r
0 p
1 d
1 e
1 m
1 t
1 y
1 u
0 v
1 7
1 1
1 4
0 5
0 3
0 1
1 6
1 2
0 8
0 4

</pre>


<h4>output</h4>
<pre>y

</pre>


# 限制与约定


<p>子任务会给出部分测试数据的特点。如果你在解决题目中遇到了困难，可以尝试只解决一部分测试数据。</p>
<p>每个测试点的数据规模及特点如下表：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点</th><th rowspan="1">$n$</th><th rowspan="1">$m$</th><th rowspan="1">全朝内</th><th rowspan="1">全左数</th><th rowspan="1">$s_i=1$</th><th rowspan="1">职业长度为$1$</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="16">$=20$</td><td rowspan="16">$=10^{3}$</td><td rowspan="1">√</td><td rowspan="2">√</td><td rowspan="4">√</td><td rowspan="8">√</td></tr><tr><td rowspan="1">2</td><td rowspan="1">×</td></tr><tr><td rowspan="1">3</td><td rowspan="1">√</td><td rowspan="2">×</td></tr><tr><td rowspan="1">4</td><td rowspan="1">×</td></tr><tr><td rowspan="1">5</td><td rowspan="1">√</td><td rowspan="2">√</td><td rowspan="4">×</td></tr><tr><td rowspan="1">6</td><td rowspan="1">×</td></tr><tr><td rowspan="1">7</td><td rowspan="1">√</td><td rowspan="2">×</td></tr><tr><td rowspan="1">8</td><td rowspan="1">×</td></tr><tr><td rowspan="1">9</td><td rowspan="1">√</td><td rowspan="2">√</td><td rowspan="4">√</td><td rowspan="12">×</td></tr><tr><td rowspan="1">10</td><td rowspan="1">×</td></tr><tr><td rowspan="1">11</td><td rowspan="1">√</td><td rowspan="2">×</td></tr><tr><td rowspan="1">12</td><td rowspan="1">×</td></tr><tr><td rowspan="1">13</td><td rowspan="1">√</td><td rowspan="2">√</td><td rowspan="8">×</td></tr><tr><td rowspan="1">14</td><td rowspan="1">×</td></tr><tr><td rowspan="1">15</td><td rowspan="1">√</td><td rowspan="2">×</td></tr><tr><td rowspan="1">16</td><td rowspan="1">×</td></tr><tr><td rowspan="1">17</td><td rowspan="4">$=10^{5}$</td><td rowspan="4">$=10^{5}$</td><td rowspan="1">√</td><td rowspan="2">√</td></tr><tr><td rowspan="1">18</td><td rowspan="1">×</td></tr><tr><td rowspan="1">19</td><td rowspan="1">√</td><td rowspan="2">×</td></tr><tr><td rowspan="1">20</td><td rowspan="1">×</td></tr></tbody></table></div> 

<p>其中一些简写的列意义如下：</p>
<ul><li>全朝内：若为“√”，表示该测试点保证所有的玩具小人都朝向圈内；</li>
<li>全左数：若为“√”，表示该测试点保证所有的指令都向左数，即对任意的 $1 \le i \le m$，$a_i = 0$；</li>
<li>$s_i=1$：若为“√”，表示该测试点保证所有的指令都只数 $1$ 个，即对任意的 $1 \le i \le m$，$s_i = 1$；</li>
<li>职业长度为$1$：若为“√”，表示该测试点保证所有玩具小人的职业一定是一个长度为 $1$ 的字符串。</li>
</ul><p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=260">样例数据下载</a></p>
