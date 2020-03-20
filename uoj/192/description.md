# 题目描述

<p>在人类和跳蚤的战争初期，人们凭借着地理优势占据了上风——即使是最强壮的跳蚤，也无法一下越过那一堵坚固的城墙。</p>
<p>在经历了惨痛的牺牲后，跳蚤国王意识到再这样下去，跳蚤国必败无疑。然而为了震慑跳蚤国的老冤家——猴族，跳蚤国那世界上最跳的坦克只能留在跳蚤国本土，无法派上用场。</p>
<p>于是跳蚤国王决定利用跳蚤国最尖端的技术，创造出最强的跳蚤来挽回败局。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/192/god-create-flea.jpg" alt="上帝造跳蚤"/></p>
<p>为了避免这样的低级失误，跳蚤国王决定使用机器来帮助他创造跳蚤。他把它拥有的 $n$ 种属性放在了 $n$ 个容器中，然后他使用了 $n-1$ 条橡胶软管将这 $n$ 个容器连接成了<strong>一个树形结构</strong>（即任意两个容器之间有且只有一条简单路径）。</p>
<p>跳蚤国王的机器会使用这样的方式来创造跳蚤：跳蚤国王需要选择两个不同的容器 $u,v(u \neq v)$，那么机器就会使用 $u$ 到 $v$ 的简单路径上的所有的橡胶软管将这条路上的所有属性汇聚到一起制造跳蚤。<strong>注意：这时只有 $u$ 到 $v$ 的简单路径上的橡胶软管被用到了。</strong></p>
<p>每一条橡胶软管都有一个耐久度 $w_i$，<strong>跳蚤国王认为一个制造的方案是安全的，当且仅当所有被用到的橡胶软管的耐久度的乘积是完全平方数</strong>。</p>
<p>现在，跳蚤国王想要知道有多少种不同的制造方案是安全的。但是因为跳蚤国王日理万机，所以他让你——一个刚刚被抓来的人类俘虏来帮他计算答案。</p>
<p>两个制造方案是不同的当且仅当 $u$ 不同或者 $v$ 不同。</p>

# 输入格式


<p>第一行两个正整数$n$，表示容器的数目。</p>
<p>以下$n - 1$行，每行三个正整数$u,v,w$表示一条软管连接$u,v$，耐久度为$w$。</p>

# 输出格式


<p>输出一行一个整数表示制造方案数。</p>

# 样例一


<h4>input</h4>
<pre>5
1 2 2
1 3 6
1 4 2
4 5 3

</pre>

<h4>output</h4>
<pre>4

</pre>

<h4>explanation</h4>
<p>共有$4$种建造方案：$2 \rightarrow 4,4 \rightarrow 2,3 \rightarrow 5,5 \rightarrow 3$</p>

# 样例二


<p>见样例数据下载。</p>

# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<p>每个测试点的规模如下表所示：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$</th><th>$w$</th></tr></thead><tbody><tr><td>1</td><td rowspan="3">$n \leq 300$</td><td>$w \leq 80$</td></tr><tr><td>2</td><td rowspan="2">$w \leq 10^3$</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="2">$n \leq 3000$</td><td>$w \leq 10^7$</td></tr><tr><td>5</td><td></td></tr><tr><td>6</td><td rowspan="5">$n \leq 100000$</td><td>$w \leq 80$</td></tr><tr><td>7</td><td>$w \leq 10^7$</td></tr><tr><td>8</td><td rowspan="3"></td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>对于所有数据，$1 \leq n \leq 100000,1 \leq w \leq 10^8$，保证形成一棵树。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=192">样例数据下载</a></p>
