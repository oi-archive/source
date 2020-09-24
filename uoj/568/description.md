# 题目描述

<p>研究蘑菇的专家安德鲁在研究新加坡的本地蘑菇。</p>
<p>作为研究的一部分，安德鲁采集了 $n$ 个蘑菇，编号为 $0$ 到 $n - 1$。每个蘑菇均为两种蘑菇种类之一，称为 $A$ 或 $B$。</p>
<p>安德鲁知道<strong>蘑菇 $0$ 属于种类 $A$</strong>，但是由于这两种蘑菇看起来很相似，他不知道蘑菇 $1$ 到 $n-1$ 属于哪一种。</p>
<p>幸运的是,安德鲁的实验室里有一台机器可以帮助他。在使用这台机器时,需要将两个或者多个蘑菇放到机器里,并摆成一排（以任意顺序），然后打开机器。接下来，这台机器会计算所有不属于同一种类的<strong>相邻</strong>蘑菇对的个数。例如,如果你把种类为 $[A,B,B,A]$ 的蘑菇（按照这个顺序）放到机器中，结果应该是 $2$。</p>
<p>但是，因为机器操作非常昂贵，机器只能使用有限的次数。此外，在机器的所有使用中，放置到机器中的蘑菇总数不能超过 $100000$。请使用这台机器帮助安德鲁来数一数他采集了多少个种类为 $A$ 的蘑菇。</p>

# 实现细节


<p>你需要实现以下函数：</p>
<pre><code class="sh_cpp">int count_mushrooms(int n)</code></pre>
<ul><li>$n$：安德鲁采集到的蘑菇数量。</li>
<li>该函数应该被调用恰好一次，而且要返回种类为 $A$ 的蘑菇的个数。</li>
</ul><p>以上函数可以调用以下函数：</p>
<pre><code class="sh_cpp">int use_machine(int[] x)</code></pre>
<ul><li>$x$：一个长度介于 $2$ 和 $n$ 的数组（包括 $2$ 和 $n$），按顺序给出放在机器中的蘑菇的编号</li>
<li>$x$ 的元素必须是在 $0$ 到 $n-1$ 之间（包括 $0$ 和 $n - 1$）<strong>互不相同</strong>的整数</li>
<li>假设数组 $x$ 的长度为 $d$。那么，此函数返回不同的下标 $j$ 的个数，满足 $0 \le j \le d-2$ 并且 $x[j]$ 和 $x[j+1]$ 属于不同种类。</li>
<li>该函数最多可以被调用 $20000$ 次。</li>
<li>在对函数 <code>use_machine</code> 的所有调用中，所有被传到该函数 <code>use_machine</code> 的 $x$ 的总长度不能超过 $100000$。</li>
</ul>
# 例子


<h4>例一</h4>
<p>考虑以下场景：有 $3$ 个蘑菇，种类依次为 $[A, B, B]$。函数 <code>count_mushrooms</code> 用以下方式调用</p>
<pre><code class="sh_cpp">count_mushrooms(3)</code></pre>
<p>该函数可以调用 <code>use_machine([0, 1, 2])</code>，在该场景下调用返回 $1$。 函数接着调用 <code>use_machine([2, 1])</code>，该调用返回 $0$。</p>
<p>此时，已经有足够的信息来推出只有 $1$ 个 $A$ 类蘑菇。所以，函数 <code>count_mushrooms</code> 应该返回 $1$。</p>
<h4>例二</h4>
<p>考虑一个例子：有 $4$ 个蘑菇，种类依次为 $[A, B, A, A]$。函数 <code>count_mushrooms</code> 被调用如下：</p>
<pre><code class="sh_cpp">count_mushrooms(4)</code></pre>
<p>该函数可以调用 <code>use_machine([0, 2, 1, 3])</code>，该调用返回 $2$。接着调用 <code>use_machine([1, 2])</code>，该调用返回 $1$。</p>
<p>此时，已有足够的信息推出：有 $3$ 个 $A$ 类蘑菇。因此，函数 count_mushrooms 应该返回 $3$。</p>

# 评测程序示例


<p>评测程序示例读入一个整数数组 ，该数组给出了蘑菇的种类。对于所有 $0 \le i \le n - 1$，$s[i] = 0$ 表示蘑菇 $i$ 的种类是 $A$，$s[i] = 1$ 表示蘑菇 $i$ 的种类是 $B$。 评测程序示例读取如下格式的输入数据：</p>
<ul><li>第 1 行：$n$</li>
<li>第 2 行： $s[0] s[1] \dots s[n-1]$</li>
</ul><p>评测程序示例的输出为如下格式：</p>
<ul><li>第 1 行: <code>count_mushrooms</code> 的返回值。</li>
<li>第 2 行: 调用 <code>use_machine</code> 的次数。</li>
</ul><p>注意评测程序示例不是自适应的。</p>
<p>如果你要提交 hack，一种格式是：</p>
<ul><li>第 1 行：<samp>plain</samp> （仅一个字符串）</li>
<li>第 2 行：$n$</li>
<li>第 3 行： $s[0] s[1] \dots s[n-1]$</li>
</ul>
# 限制与约定


<p>$2 \le n \le 20000$。</p>
<p>在所有测试用例中，如果对函数 <code>use_machine</code> 的调用不符合上面所述的要求，或者 <code>count_mushrooms</code> 的返回值不正确，你的解答得分将为 $0$。否则，令 $Q$ 为所有测试样例中对函数 <code>use_machine</code> 的最大调用次数。那么，得分将按照以下表格进行计算：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>条件</th>
<th>得分</th>
</tr></thead><tbody><tr><td>$20000 &lt; Q$</td>
<td>$0$</td>
</tr><tr><td>$10010 &lt; Q \le 20000$</td>
<td>$10$</td>
</tr><tr><td>$904 &lt; Q \le 10010$</td>
<td>$25$</td>
</tr><tr><td>$226 &lt; Q \le 904$</td>
<td>$\left\lfloor \frac{226}{Q} \cdot 100 \right\rfloor$</td>
</tr><tr><td>$Q \le 226$</td>
<td>$100$</td>
</tr></tbody></table></div>
<p>在有些测试用例上，评测程序的行为是自适应的。也就是说，在这些测试用例中，评测程序并没有一个固定的蘑菇种类序列。相反，评测程序中所给出的回答可能依赖于此前对 <code>use_machine</code> 的调用。但是可以保证，评测程序中所给出的回答满足：在每次交互之后，至少存在一个蘑菇种类序列，它能够与当前所给出过的所有回答都相符。</p>
<p><strong>时间限制</strong>：$2\texttt{s}$</p>
<p><strong>空间限制</strong>：$2\texttt{GB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=568">样例及测评库下载</a></p>
