# 题目描述

<p>小刘同学是一个喜欢氪金手游的男孩子。 </p>
<p>他最近迷上了一个新游戏，游戏的内容就是不断地抽卡。现在已知：</p>
<ul><li><p>卡池里总共有 $N$ 种卡，第 $i$ 种卡有一个权值 $W_i$，小刘同学不知道 $W_i$ 具体的值是什么。但是他通过和网友交流，他了解到 $W_i$ 服从一个分布。</p>
</li>
<li><p>具体地，对每个 $i$，小刘了解到三个参数 $p_{i,1},p_{i,2},p_{i,3}$，$W_i$ 将会以 $p_{i,j}$ 的概率取值为 $j$，保证 $p_{i,1}+p_{i,2}+p_{i,3}=1$。</p>
</li>
</ul><p>小刘开始玩游戏了，他每次会氪一元钱来抽一张卡，其中抽到卡 $i$ 的概率为：</p>
<p>$$\frac{W_i}{\sum_j W_j}$$</p>
<p>小刘会不停地抽卡，<strong>直到</strong>他手里集齐了全部 $N$ 种卡。  </p>
<p>抽卡结束之后，服务器记录下来了小刘<strong>第一次</strong>得到每张卡的时间 $T_i$。游戏公司在这里设置了一个彩蛋：公司准备了 $N−1$ 个二元组 $(u_i,v_i)$，如果对任意的 $i$，成立 $T_{u_i} \lt T_{v_i} $，那么游戏公司就会认为小刘是极其幸运的，从而送给他一个橱柜的手办作为幸运大奖。  </p>
<p>游戏公司为了降低获奖概率，它准备的这些 $(u_i,v_i)$ 满足这样一个性质：对于任意的 $\varnothing\ne S\subsetneq\{1,2,\ldots,N\}$，总能找到 $(u_i,v_i)$ 满足：$u_i\in S,v_i\notin S$ <strong>或者</strong> $u_i\notin S,v_i\in S$。  </p>
<p>请你求出小刘同学能够得到幸运大奖的概率，可以保证结果是一个有理数，请输出它对 $998244353$ 取模的结果。</p>

# 输入格式


<p>第一行一个整数 $N$，表示卡的种类数。  </p>
<p>接下来 $N$ 行，每行三个整数 $a_{i,1},a_{i,2},a_{i,3}$，而题目给出的 $p_{i,j}=\frac{a_{i,j}}{a_{i,1}+a_{i,2}+a_{i,3}}$。  </p>
<p>接下来 $N−1$ 行，每行两个整数 $u_i,v_i$，描述一个二元组（意义见题目描述）。</p>

# 输出格式


<p>输出一行一个整数，表示所求概率对 $998244353$ 取模的结果。</p>

# 样例一


<h4>input</h4>
<pre><code>2
0 0 1
1 1 0
1 2</code></pre>
<h4>output</h4>
<pre><code>524078286</code></pre>
<h4>explanation</h4>
<p>$W_2$ 以 $\frac 12$ 的概率取 $1$ 或者 $2$：</p>
<ul><li><p>如果 $W_2=1$，那么 $T_1\lt T_2$ 的概率为 $\frac 34$。</p>
</li>
<li><p>否则 $W_2=2$，$T_1\lt T_2$ 的概率为 $\frac 35$。</p>
</li>
</ul><p>综合所有情况答案为 $\frac 12\left(\frac 34+\frac 35\right)=\frac{27}{40}$，你可以验证它对 $998244353$ 取模的结果确实是所给答案。</p>

# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<p>对于 $100\%$ 的数据，$N\le 1000$，$0 \le a_{i,j}\le 10^6$。</p>
<p>每个测试点的具体限制见下表：</p>
 <div class="table-responsive"><table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>子任务编号</th><th>$N \le$</th><th>特殊性质</th><th>分值</th></tr></thead><tbody><tr><td>$1$</td><td>$15$</td><td>无</td><td>$20$</td></tr><tr><td>$2$</td><td>$200$</td><td>每个限制保证 $|u_i−v_i|=1$</td><td>$15$</td></tr><tr><td>$3$</td><td>$1000$</td><td>每个限制保证 $|u_i−v_i|=1$</td><td>$20$</td></tr><tr><td>$4$</td><td>$200$</td><td>无</td><td>$15$</td></tr><tr><td>$5$</td><td>$1000$</td><td>无</td><td>$30$</td></tr></tbody></table></div>

<p><strong>时间限制: 1s</strong></p>
<p><strong>空间限制: 512MB</strong></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=477">样例数据下载</a></p>
