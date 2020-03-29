# 题目描述

<p>这是一道<strong>交互题</strong>。</p>
<p>跳蚤国王正在带领着四万万跳蚤造计算机。</p>
<p>我们给每只跳蚤一个从 $0$ 开始的整数编号。</p>
<p>由于跳蚤国的文明比较落后，每只跳蚤只能存储一个 $0$ 或 $1$ 的值，对于第 $i$ 只跳蚤这个值记为 $v_i$。</p>
<p>对于所有编号小于 $2n$ 的跳蚤，它们的值由跳蚤国王决定。即，这 $2n$ 个值可以看作是输入。</p>
<p>我们记
\begin{equation}
F(a,b,f) = \left \lfloor \frac{f}{2 ^ {2 a + b}} \right \rfloor \mod 2
\end{equation}</p>
<p>对于编号大于等于 $2n$ 的每只跳蚤，设它的编号为 $i$ ，
你需要给它指定三个参数 $a_i, b_i, f_i$ ($0 \le a_i &lt; i, 0 \le b_i &lt; i, 0 \le f_i &lt; 16$)，则
\begin{equation}
v_i = F \left ( v_{a_i}, v_{b_i}, f_i \right ) = \left \lfloor \frac{f_i}{2 ^ {2 v_{a_i}  + v_{b_i} }} \right \rfloor \mod 2
\end{equation}
我们称第 $i$ 只跳蚤依赖于第 $a_i$ 和第 $b_i$ 只跳蚤（<strong>注意$a_i$可以等于$b_i$</strong>）。</p>
<p>下面给出了几个关于 $F$ 的例子：</p>
<div class="table-responsive">
  <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>$a$</th><th>$b$</th><th>$F(a,b,14)$</th><th>$F(a,b,8)$</th><th>$F(a,b,6)$</th></tr></thead><tbody><tr><td>$0$</td><td>$0$</td><td>$0$</td><td>$0$</td><td>$0$</td></tr><tr><td>$0$</td><td>$1$</td><td>$1$</td><td>$0$</td><td>$1$</td></tr><tr><td>$1$</td><td>$0$</td><td>$1$</td><td>$0$</td><td>$1$</td></tr><tr><td>$1$</td><td>$1$</td><td>$1$</td><td>$1$</td><td>$0$</td></tr></tbody></table></div>

<p>一开始（第 $0$ 时刻），所有编号小于 $2n$ 的跳蚤的值都同时被确定。
然后对于每只编号大于等于 $2n$ 的跳蚤，
它的值将在它依赖的跳蚤的值都确定之后立即开始确定。
由于跳蚤国的信息技术不发达，
每只跳蚤确定它的值需要1小时（注意多只跳蚤可以同时确定它们的值）。</p>
<p>下面是一个例子：（id表示编号，t表示该跳蚤的值被确定的时间，箭头表示跳蚤的依赖关系）</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/166/king.jpg" alt="例子" style="width:400px;"/></p>
<p>我们可以把编号小于 $2n$ 的跳蚤的值看作两个 $n$ 位的二进制数 $\mathrm{A}, \mathrm{B}$，
其中 $\mathrm{A} = (v_{n-1} \  v_{n-2} \  \cdots \  v_0)_2$，
$\mathrm{B} = (v_{2n-1} \  v_{2n-2} \  \cdots \  v_{n})_2$。
跳蚤国王要对 $\mathrm{A}$ 和 $\mathrm{B}$ 做一些运算，得到一个 $n$ 位二进制数，
并用 $n$ 只跳蚤表示出来。</p>
<p>由于跳蚤国王还要带着跳蚤们去舞会，你能使用的跳蚤的数量和时间都有限。
具体来说，你最多使用 $\mathrm{M}$ 只跳蚤，并要求按顺序指定 $n$ 只跳蚤，
在 $\mathrm{T}$ 小时内，你使用的所有跳蚤的值都能被确定，
且指定的 $n$ 只跳蚤的值表示的二进制数为跳蚤国王所求的答案。</p>
<p><strong>作为奖励，跳蚤国王打算送你一个UOJ抱枕。
第一个通过最后一个测试点的选手将获得一个UOJ抱枕。
如果没有选手通过最后一个测试点，则第一个得到此题最高分的选手将获得一个UOJ抱枕。</strong></p>

# 任务


<p>你需要编写一个函数 <code>build_computer</code>，来帮助跳蚤国王造计算机。</p>
<ul><li><code>build_computer(task_id, n, M, T)</code><ul><li><code>task_id</code>: 子任务编号</li>
<li><code>n</code>: 输入的$\mathrm{A}$和$\mathrm{B}$的位数</li>
<li><code>M</code>: 除了编号小于$2n$的跳蚤之外，最多能使用的跳蚤的数目</li>
<li><code>T</code>: 你使用的所有跳蚤的值都要在$\mathrm{T}$小时内被确定</li>
</ul></li>
</ul><p>你可以调用一个函数 <code>add_flea(a, b, f)</code>，
表示增加一只跳蚤，对于第 $i$ 次调用，
增加的跳蚤的编号为$2n + i - 1$，
$a_{2n+i-1}, b_{2n+i-1}, f_{2n+i-1}$分别被设置为$a, b, f$，
然后这个函数会返回$2n + i - 1$。
你最多能调用$\mathrm{M}$次 <code>add_flea</code>。</p>
<p>你还需要对每个 $[0, n-1]$ 中的整数 $i$ 调用 <code>set_output</code> 函数（可以按任意顺序调用）。
<code>set_output(i, id)</code> 表示设置输出的二进制数的第 $i$ 位为编号为 $id$ 的跳蚤的值。</p>

# 子任务


<div class="table-responsive">
  <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务编号</th><th>需要计算的表达式</th></tr></thead><tbody><tr><td>1</td><td>     $(\mathrm{A} + 1) \mod 2 ^ n$           </td></tr><tr><td>2</td><td>  $(\mathrm{A} + \mathrm{B}) \mod 2 ^ n$     </td></tr><tr><td>3</td><td> $(\mathrm{A} \times \mathrm{B}) \mod 2 ^ n$ </td></tr></tbody></table></div>

<p>设 $m$ 为 <code>add_flea</code> 的调用次数，$t$ 为所有跳蚤的值被确定的最晚时刻。</p>
<div class="table-responsive">
  <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>子任务编号</th><th>分值</th><th>$n$</th><th>$\mathrm{M}$</th><th>$\mathrm{T}$</th><th>备注</th></tr></thead><tbody><tr><td>1 </td><td>1</td><td>1 </td><td>   $1$   </td><td>      $10000$    </td><td>    $10000$ </td><td> </td></tr><tr><td>2 </td><td>1</td><td>2 </td><td>   $2$   </td><td>      $10000$    </td><td>    $10000$  </td><td>  </td></tr><tr><td>3 </td><td>1</td><td>5 </td><td>  $256$  </td><td>      $10000$    </td><td>    $10000$  </td><td>  </td></tr><tr><td>4 </td><td>1</td><td>9 </td><td>$10^5$ </td><td>$5 \times 10^5$   </td><td> $50$  </td><td> 该测试点得分为$\min \left \{ \left \lfloor \frac{5 \times 10^5 - m}{20000} \right \rfloor, 9 \right \}$分  </td></tr><tr><td>5 </td><td>1</td><td>10</td><td> $10^5$</td><td> $1.5 \times 10^6$</td><td>    $30$  </td><td> 该测试点得分为$\min \left \{30-t, 10 \right \}$分  </td></tr><tr><td>6 </td><td>2</td><td>3 </td><td>   $2$   </td><td>      $10000$    </td><td>    $10000$</td><td>      </td></tr><tr><td>7 </td><td>2</td><td>6 </td><td>  $233$  </td><td>      $10000$    </td><td>    $10000$</td><td>      </td></tr><tr><td>8 </td><td>2</td><td>13</td><td>$10^5$ </td><td> $1.2 \times 10^6$</td><td>  $100$ </td><td> 该测试点得分为$\min \left \{ \left \lfloor \frac{1.2 \times 10^6-m}{30000} \right \rfloor, 13 \right \}$分     </td></tr><tr><td>9 </td><td>2</td><td>14</td><td>$10^5$ </td><td>  $5 \times 10^6$ </td><td>  $42$</td><td>该测试点得分为$\min \left \{42-t, 14 \right \}$分          </td></tr><tr><td>10</td><td>3</td><td>4 </td><td>   $2$   </td><td>      $10000$    </td><td>    $10000$ </td><td>      </td></tr><tr><td>11</td><td>3</td><td>7 </td><td>  $233$  </td><td>      $10^6$     </td><td>  $10^6$ </td><td>      </td></tr><tr><td>12</td><td>3</td><td>8 </td><td>  $512$  </td><td>  $3 \times 10^6$ </td><td>  $255$   </td><td>    </td></tr><tr><td>13</td><td>3</td><td>17</td><td>  $1024$ </td><td>  $4 \times 10^6$ </td><td>  $94$    </td><td> 该测试点得分为$\min \left \{ \left \lfloor\frac{94-t}{2} \right \rfloor, 17 \right \}$分   </td></tr><tr><td>14</td><td>3</td><td>1 </td><td>  $1024$ </td><td>    $1920000$    </td><td> $288$   </td><td> <b>第一个通过该测试点的选手将获得一个UOJ抱枕！</b>  </td></tr></tbody></table></div>


# 实现细节


<p>本题只支持C++。</p>
<p>你只能提交一个源文件实现如上所述的 <code>build_computer</code> 函数，并且遵循下面的命名和接口。</p>
<p>你需要包含头文件 <code>king.h</code>。</p>
<pre><code class="sh_cpp">void build_computer(int task_id, int n, int M, int T);</code></pre>
<p>函数 <code>add_flea</code> 和 <code>set_output</code> 的接口信息如下。</p>
<pre><code class="sh_cpp">int add_flea(int a, int b, int f);
void set_output(int i, int id);</code></pre>

# 评测方式


<p>评测系统将读入如下格式的数据：</p>
<ol><li>第1行：子任务编号</li>
<li>第2行：$n, \mathrm{M}, \mathrm{T}$</li>
</ol><p>如果你调用 <code>add_flea</code> 的次数大于 $\mathrm{M}$，
或调用 <code>set_output</code>的次数不等于 $n$，
或没有对 $[0, n-1]$ 中的每个整数作为 <code>set_output</code> 的第一个参数调用 <code>set_output</code>，
你的程序将被判为“Incorrect”。</p>
<p>在 <code>build_computer</code> 返回后，如果在 $\mathrm{T}$ 小时后，存在一只跳蚤的值还没被确定，则评测系统输出“Incorrect”，
否则我们将用若干组输入对你造的计算机进行测试，
如果对于所有输入数据，你的输出都正确，评测系统将输出“Correct”，否则输出“Incorrect”。</p>
<p>如果评测系统第一行输出了“Correct”，则第二行将会输出 $m$ 和 $t$（定义见“子任务”），否则会输出具体的错误信息。</p>
<p><a href="/faq">交互式类型的题目怎么本地测试</a></p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>
<p><strong>在任何时候，交互库使用的内存都不会超过$128\texttt{MB}$，即选手至少有$384\texttt{MB}$的可用内存。</strong></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=166">样例及测评库下载</a></p>
