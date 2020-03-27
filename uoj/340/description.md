# 题目描述


# 题目背景


<p>&#34;A fight? Count me in!&#34; 要打架了，算我一个。</p>
<p>&#34;Everyone, get in here!&#34; 所有人，都过来！</p>

# 题目描述


<p>小Y是一个喜欢玩游戏的OIer。一天，她正在玩一款游戏，要打一个Boss。</p>
<p>虽然这个Boss有 $10^{100}$ 点生命值，但它只带了一个随从——一个只有 $m$ 点生命值的“恐怖的奴隶主”。</p>
<p>这个“恐怖的奴隶主”有一个特殊的技能：每当它被扣减生命值但没有死亡（死亡即生命值 $\leq 0$），且Boss的随从数量小于上限 
$k$，便会召唤一个新的具有 $m$ 点生命值的“恐怖的奴隶主”。</p>
<p>现在小Y可以进行 $n$ 次攻击，每次攻击时，会从Boss以及Boss的所有随从中的等概率随机选择一个，并扣减 $1$ 点生命值，她想知道进行 $n$ 次攻击后扣减Boss的生命值点数的期望。为了避免精度误差，你的答案需要对 $998244353$ 取模。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>输入第一行包含三个正整数 $T, m, k$，$T$ 表示询问组数，$m, k$ 的含义见题目描述。</p>
<p>接下来 $T$ 行，每行包含一个正整数 $n$，表示询问进行 $n$ 次攻击后扣减Boss的生命值点数的期望。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>输出共 $T$ 行，对于每个询问输出一行一个非负整数，表示该询问的答案对 $998244353$ 取模的结果。</p>
<p>可以证明，所求期望一定是一个有理数，设其为 $p / q$（$\mathrm{gcd}(p,q) = 1$），那么你输出的数 $x$ 要满足 $p \equiv qx \pmod{998244353}$。</p>

# 样例一


<h4>input</h4>
<pre><code class="sh_plain">3 2 6
1
2
3</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">499122177
415935148
471393168</code></pre>
<h4>explanation</h4>
<p>对于第一次询问，第一次攻击有 $\frac{1}{2}$ 的概率扣减Boss的生命值，有 $\frac{1}{2}$ 的概率扣减随从的生命值，所以答案为 $\frac{1}{2}$。$1 \equiv 2 * 499122177 \pmod{998244353}$。</p>
<p>对于第二次询问，如果第一次攻击扣减了Boss的生命值，那么有 $\frac{1}{2}$ 的概率第二次攻击仍扣减Boss的生命值，有 $\frac{1}{2}$ 的概率第二次攻击扣减随从的生命值；如果第一次攻击扣减了随从的生命值，那么现在又新召唤了一个随从（“恐怖的奴隶主”），于是有 $\frac{1}{3}$ 的概率第二次攻击扣减Boss的生命值，有 $\frac{2}{3}$ 的概率第二次攻击扣减随从的生命值。所以答案为 $\frac{1}{2}*\frac{1}{2}*2+\frac{1}{2}*\frac{1}{2}*1+\frac{1}{2}*\frac{1}{3}*1+\frac{1}{2}*\frac{2}{3}*0 = \frac{11}{12}$。$11 \equiv 12 * 415935148\pmod{998244353}$。</p>

# 样例二


<p>见“样例数据下载”</p>
<p>该组样例的数据范围（除询问组数 $T$ 外）同第7、8个测试点。</p>

# 提示


<p>题目顺序可能与难度无关。</p>

# 限制与约定


<p>在所有测试点中，$1 \leq T \leq 1000, 1 \leq n \leq {10}^{18}, 1 \leq m \leq 3, 1 \leq k \leq 8$。</p>
<p>各个测试点的分值和数据范围如下：</p>
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点编号</th><th rowspan="1">分值</th><th rowspan="1">$T=$</th><th rowspan="1">$n\leq$</th><th rowspan="1">$m=$</th><th rowspan="1">$k=$</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">3</td><td rowspan="4">10</td><td rowspan="2">10</td><td rowspan="1">1</td><td rowspan="1">1</td></tr><tr><td rowspan="1">2</td><td rowspan="1">8</td><td rowspan="3">2</td><td rowspan="1">8</td></tr><tr><td rowspan="1">3</td><td rowspan="1">7</td><td rowspan="8">${10}^{18}$</td><td rowspan="1">3</td></tr><tr><td rowspan="1">4</td><td rowspan="1">12</td><td rowspan="1">7</td></tr><tr><td rowspan="1">5</td><td rowspan="1">30</td><td rowspan="1">20</td><td rowspan="6">3</td><td rowspan="1">5</td></tr><tr><td rowspan="1">6</td><td rowspan="1">10</td><td rowspan="1">500</td><td rowspan="1">6</td></tr><tr><td rowspan="1">7</td><td rowspan="1">10</td><td rowspan="1">200</td><td rowspan="2">7</td></tr><tr><td rowspan="1">8</td><td rowspan="1">5</td><td rowspan="1">1000</td></tr><tr><td rowspan="1">9</td><td rowspan="1">10</td><td rowspan="1">100</td><td rowspan="2">8</td></tr><tr><td rowspan="1">10</td><td rowspan="1">5</td><td rowspan="1">500</td></tr></tbody></table><p><strong>时间限制</strong>：$2\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=340">样例数据下载</a></p>
