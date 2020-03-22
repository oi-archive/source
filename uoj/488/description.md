# 题目描述

<p>通常，人们习惯将所有 $n$ 位二进制串按照字典序排列，例如所有 2 位二进制串按字典序从小到大排列为：00，01，10，11。</p>
<p>格雷码（Gray Code）是一种特殊的 $n$ 位二进制串排列法,它要求相邻的两个二进制串间<strong>恰好</strong>有一位<strong>不同</strong>，特别地，第一个串与最后一个串也算作相邻。</p>
<p>所有 2 位二进制串按格雷码排列的一个例子为：00，01，11，10。</p>
<p>$n$ 位格雷码不止一种，下面给出其中一种格雷码的生成算法： </p>
<ol><li>1 位格雷码由两个 1 位二进制串组成，顺序为：0，1。 </li>
<li>$n + 1$ 位格雷码的前 $2^n$ 个二进制串，可以由依此算法生成的 $n$ 位格雷码（总共 $2^n$ 个 $n$ 位二进制串）按<strong>顺序</strong>排列，再在每个串前加一个前缀 0 构成。 </li>
<li>$n + 1$ 位格雷码的后 $2^n$ 个二进制串，可以由依此算法生成的 $n$ 位格雷码（总共 $2^n$ 个 $n$ 位二进制串）按<strong>逆序</strong>排列，再在每个串前加一个前缀 1 构成。 </li>
</ol><p>综上，$n+ 1$ 位格雷码，由 $n$ 位格雷码的 $2^n$ 个二进制串按顺序排列再加前缀 0，和 按逆序排列再加前缀 1 构成，共 $2^{n+1}$ 个二进制串。另外，对于 $n$ 位格雷码中的 $2^n$ 个二进制串，我们按上述算法得到的排列顺序将它们从 $0∼2^n −1$ 编号。</p>
<p>按该算法，2 位格雷码可以这样推出： </p>
<ol><li>已知 1 位格雷码为 0，1。 </li>
<li>前两个格雷码为 <strong><em>0</em></strong>0，<strong><em>0</em></strong>1。后两个格雷码为 <strong><em>1</em></strong>1，<strong><em>1</em></strong>0。合并得到 00，01，11，10， 编号依次为 0∼3。 </li>
</ol><p>同理，3 位格雷码可以这样推出： </p>
<ol><li>已知 2 位格雷码为：00，01，11，10。 </li>
<li>前四个格雷码为：<strong><em>0</em></strong>00，<strong><em>0</em></strong>01，<strong><em>0</em></strong>11，<strong><em>0</em></strong>10。后四个格雷码为：<strong><em>1</em></strong>10，<strong><em>1</em></strong>11，<strong><em>1</em></strong>01， <strong><em>1</em></strong>00。合并得到：000，001，011，010，110，111，101，100，编号依次为 0∼7。 </li>
</ol><p>现在给出 $n,k$，请你求出按上述算法生成的 $n$ 位格雷码中的 $k$ 号二进制串。</p>

# 输入格式


<p>仅一行两个整数 $n,k$，意义见题目描述。</p>

# 输出格式


<p>仅一行一个 $n$ 位二进制串表示答案。</p>

# 样例1


<h4>input</h4>
<pre><code class="sh_plain">2 3</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">10</code></pre>

# explaination


<p>2 位格雷码为：00，01，11，10，编号从 0∼3，因此 3 号串是 10。</p>

# 样例2


<h4>input</h4>
<pre><code class="sh_plain">3 5</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">111</code></pre>

# 限制与约定


<p>对于 $50\%$ 的数据：$n \leq 10$ </p>
<p>对于 $80\%$ 的数据：$k \leq 5 \times 10^6$</p>
<p>对于 $95\%$ 的数据：$k \leq 2^{63} -1$</p>
<p>对于 $100\%$ 的数据：$1 \leq n \leq 64,0 \leq k &lt; 2^n-1$</p>
<p><strong>时间限制:</strong> $1\texttt{s}$</p>
<p><strong>空间限制:</strong> $256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=488">样例数据下载</a></p>
