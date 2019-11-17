# 题目描述

<p>DoubleDog现在锁定了 $n$ 只SingleDog，决心去拯救它们。</p>
<p>为了能够快速到达这$n$只SingleDog的处所，DoubleDog们希望跳蚤国帮助修建一些道路，把$n$只SingleDog的处所联通。一条道路可以直接连接任意两只SingleDog的处所，所以只需要$n-1$条道路就可以让它们联通。</p>
<p>但是糟糕的天气可能会破坏一些道路。为了能够使得DoubleDog的计划尽可能地成功，跳蚤国王决定同时修建$m$个方案。每个方案都包含$n-1$条道路，任意一个方案都可以连通$n$只SingleDog的处所。</p>
<p>由于技术上的限制，跳蚤们给出了一个限制：这$m$个方案中任意两个方案不能存在两条相同的道路。</p>
<p>现在跳蚤国王想知道：最多能够选择多少个方案呢？</p>
<p>跳蚤国王把这个问题交给了你，请你求出这个最大的$m$，并告诉跳蚤国王这$m$个方案。</p>

# 输入格式


<p>一行一个正整数 $ n $ 表示SingleDog的数量，标号从$1$开始。</p>

# 输出格式


<p>输出的第一行是一个正整数 $ m $ ，表示最多能选出多少个方案。</p>
<p>接下来 $ m $ 行，每行 $ 2(n - 1) $ 个数，其中第 $ 2i - 1 $ 和第 $ 2i $ 个数表示该方案的一条道路。</p>
<p>你需要保证，这$m$行中任意一行的 $ (n-1) $条道路可以连通这$n$只SingleDog的处所，并且这$m(n-1)$条道路互不相同。（道路$(u,v)$和道路$(v,u$)被视为相同的道路）</p>
<p>如果本题有多组解，输出任意一组均可。</p>

# 样例一


<h4>input</h4>
<pre>3
</pre>

<h4>output</h4>
<pre>1
1 2 3 2
</pre>




# 样例二


<h4>input</h4>
<pre>4
</pre>

<h4>output</h4>
<pre>2
1 2 2 3 3 4
1 3 1 4 2 4
</pre>




# 限制与约定


<p>本题采用捆绑测试，对于每个子任务，只有通过其中全部数据才可以获得分数。</p>
<p>对于 $ 100\% $ 的数据，$ 3 \le n \le 2000 $ 。</p>
 <div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>子任务编号</th><th>$n\le$</th><th>约定</th><th>分值</th></tr></thead><tbody><tr><td>$1$</td><td>$6$</td><td></td><td>$17$</td></tr><tr><td>$2$</td><td>$100$</td><td></td><td>$10$</td></tr><tr><td>$3$</td><td>$2000$</td><td>$n$是素数</td><td>$44$</td></tr><tr><td>$4$</td><td>$2000$</td><td></td><td>$29$</td></tr></tbody></table></div>

<p><strong>时间限制</strong>：$\texttt{1s}$</p>
<p><strong>空间限制</strong>：$\texttt{512MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=460">样例数据下载</a></p>
