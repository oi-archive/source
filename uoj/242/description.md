# 题目描述

<p>土卫二上一片荒凉，但这不影响基地的建造速度。在伏特跳蚤国王的指挥下，跳蚤们愉快地和从火星抓来的特有生物 “火猩” 一起高速建造基地。</p>
<p>短短几天，基地便建造完毕，这标志着跳蚤国土卫二外区设立完毕。</p>
<p>这么大的事怎么能不庆祝呢？于是跳蚤们做了一桌丰盛的蚤餐。蚤餐的话当然少不了跳蚤的最爱 —— 仙人掌蛋糕啦！由于火猩巨大的生产力，这个蛋糕是无限大的。在切下 $n$ 刀之后，蛋糕被分为了很多块。面积有限的蛋糕块准备分给跳蚤吃，面积无限大的蛋糕块则准备分给火猩吃。这时……</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/241/dark.jpg" alt="黑恶势力登场"/></p>
<p>从某个隐蔽的角落射出了一束耀眼的光芒，这束光巧妙避开了所有蛋糕块的顶点，所经过的 $n + 1$ 个蛋糕块都被破坏了。</p>
<p>“高稳鸡光！”众蚤惊呼了起来。</p>
<p>没错，这意味有几个黑恶势力的特工混进了火箭中，也随着跳蚤大军来到了土卫二，虽然很快就被伏特跳蚤国王抓住并拿去煲汤了……</p>
<p>回过头来，伏特跳蚤国王想统计下每个被高稳鸡光破坏了的蛋糕块是准备给跳蚤吃的，还是准备给火猩吃的。</p>
<p><strong>一句话题意：</strong>平面上有 $n+1$ 条直线，前 $n$ 条直线把平面分成许多块，这些块有些面积有限，有些面积无限，而第 $n+1$ 条直线不经过前 $n$ 条直线的交点，且一定不和前 $n$ 条直线中的任意一条平行，求第 $n+1$ 条直线被前 $n$ 条直线划分成的 $n+1$ 段中哪些在面积有限的块里，哪些在面积无限的块里。</p>

# 输入格式


<p>第一行一个正整数 $n$，意义如前所述。</p>
<p>接下来 $n+1$ 行，第 $i$ 行 $4$ 个整数 $x_1, y_1, x_2, y_2$ 表示第 $i$ 条直线经过 $(x_1,y_1)$ 和 $(x_2,y_2)$ 两点。</p>
<p>保证第 $n+1$ 条直线不经过前 $n$ 条直线的交点，且一定不和前 $n$ 条直线中的任意一条平行或重合。</p>
<p>保证第 $n+1$ 条直线不与 $x$ 轴垂直，且对于第 $n + 1$ 条直线有 $x_1 &lt; x_2$。</p>

# 输出格式


<p>输出一行长度为 $n+1$ 的 01 串，第 $x$ 个数字如果为 $0$ 则表示第 $x$ 段是在面积无限的块里，如果为 $1$ 则表示第 $x$ 段是在面积有限的块里。</p>
<p>请注意，段的输出顺序必须是<strong>从左到右</strong>。由于第 $n + 1$ 条直线不与 $x$ 轴垂直，所以从左到右的顺序总是存在的。</p>

# 样例一


<h4>input</h4>
<pre>3
0 0 1 0
0 1 1 2
0 1 1 0
-5 0 5 1

</pre>

<h4>output</h4>
<pre>0010

</pre>

<h4>explanation</h4>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/242/sample1.png" alt="样例一"/></p>

# 样例二


<h4>input</h4>
<pre>3
0 0 1 0
0 1 1 1
0 2 1 2
0 0 1 1

</pre>

<h4>output</h4>
<pre>0000

</pre>

<h4>explanation</h4>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/242/sample2.png" alt="样例二"/></p>
<p>注意数据中前 $n$ 条直线可能出现互相平行的情况。</p>

# 样例三


<h4>input</h4>
<pre>4
0 0 1 0
0 1 1 1
0 0 1 1
0 1 1 2
-5 0 5 1

</pre>

<h4>output</h4>
<pre>00100

</pre>

<h4>explanation</h4>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/242/sample3.png" alt="样例三"/></p>

# 样例四


<p>见样例数据下载。</p>

# 限制与约定


<p>由于一些原因，本题使用捆绑测试。每个子任务有若干个测试点，分为 $6$ 个子任务，你只有通过一个子任务的所有测试点才能得到这个子任务的分数。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
<th>分值</th>
<th>限制</th>
</tr></thead><tbody><tr><td>1</td><td>10</td><td>$n=3$</td></tr><tr><td>2</td><td>15</td><td>$n \leq 100$</td></tr><tr><td>3</td><td>10</td><td>$n \leq 1000$</td></tr><tr><td>4</td><td>15</td><td>$n \leq 5000$</td></tr><tr><td>5</td><td>15</td><td>保证前 $n$ 条中存在两条直线 $L1$ 与 $L2$，使得其他直线要么与 $L1$ 平行，要么与 $L2$ 平行</td></tr><tr><td>6</td><td>35</td><td>无</td></tr></tbody></table></div>

<p>在所有数据中，满足 $3 \leq n \leq 10^5$，保证 $-2\times 10^6 \leq x_1, y_1, x_2, y_2 \leq 2 \times 10^6$。</p>
<p>为了避免精度问题，保证第 $n+1$ 条直线和前 $n$ 条直线的 $n$ 个交点中，两两之间的距离不小于 $0.1$。</p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=242">样例数据下载</a></p>
