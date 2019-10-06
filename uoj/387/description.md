# 题目描述

<p>提前上学之后，要做的东西就多了起来，To Do List 直接变成了 To Do Tree。</p>
<p>Mike 现在有 $n$ 个ddl，每星期 Mike 最多能肝 $m$ 个ddl，否则 Mike 会爆肝猝死。而且ddl之间有一些依赖关系，开始第 $i$ 个ddl前必须先做完第 $f_i$ 个ddl（$f_i &lt; i$），比如说，<strong>叉掉假算法</strong>之前必须先写一个<strong>靠谱的std</strong>。ddl间的依赖关系构成了一颗以 $1$ 号ddl为根的树。</p>
<p>现在Mike想知道他最少需要几星期才能肝完所有的ddl。</p>
<p><strong>注意：每星期所有ddl会在周日晚23:59:59同时被肝完，也就是说，一个星期内不能同时肝第 $f_i$ 个ddl和第 $i$ 个ddl。</strong></p>

# 输入格式


<p>第一行两个整数 $n, m$。</p>
<p>接下来一行 $n - 1$ 个整数，分别表示 $f_2,f_3,\cdots,f_n$。</p>

# 输出格式


<p>第一行输出一个整数 $t$，表示最少需要的时间。</p>
<p>接下来 $t$ 行，第 $i$ 行表示第 $i$ 星期 Mike 肝的ddl，其中第一个整数 $s_i$ 表示 Mike 这周肝的ddl个数，接下来 $s_i$ 个整数分别是 Mike 这周肝的ddl标号。相邻两个整数间用空格隔开。<strong>行末需要一个空格符。</strong></p>
<p>注意最后一行需要回车符，格式不对将会被判为$0$分。</p>

# 样例一


<h4>input</h4>
<pre>5 2
1 1 1 2

</pre>

<h4>output</h4>
<pre>3
1 1 
2 2 3 
2 4 5 

</pre>

<h4>explanation</h4>
<p>如果时刻 $2$ 没有肝掉第 $2$ 个ddl，则无法在最短时间内肝完所有ddl。</p>

# 样例二


<p>见样例数据下载。</p>

# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<p>对于所有数据，$n \leq 10^{5}, m \leq n, f_{i} &lt; i$。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th><th>分值</th><th>限制</th></tr></thead><tbody><tr><td>1</td><td>$30$</td><td>$n \leq 10$</td></tr><tr><td>2</td><td>$30$</td><td>$n \leq 16$</td></tr><tr><td>3</td><td>$6$</td><td>$m = 1$</td></tr><tr><td>4</td><td>$34$</td><td>$n \leq 10^{5}$</td></tr></tbody></table></div>

<p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=387">样例数据下载</a></p>
<p>注意：*.ans 文件中只有一行一个整数，表示最少需要的时间，输出是否合法请自行检验。</p>
