# 题目描述

<p>这是一道<strong>交互题</strong>。</p>
<p>我们需要处理这样一类表达式：它由 $n$ 个元素和 $n-1$ 个运算符构成，两个相邻元素之间有且仅有一个运算符，且表达式中没有括号。例如 $a + b \times c$ 就是一个这样的表达式。</p>
<p>这些运算符一共有 $k$ 种，每种的优先级都不同。为了方便，我们用 $1$ 到 $k$ 的整数来表示这些运算符，并且数字越大的优先级越高。</p>
<p>这些运算符都满足交换律和结合律，即对任意的元素 $a,b,c$ 和运算符 $\sim$，满足：</p>
<p>\begin{eqnarray}
a \sim b &amp; = &amp; b \sim a\\
a \sim (b \sim c) &amp; = &amp; (a \sim b) \sim c
\end{eqnarray}</p>
<p>我们记一开始的表达式为第 $0$ 个版本。</p>
<p>有 $m$ 个操作，每个操作为以下几种之一：</p>
<ul><li>元素修改：对某一个版本，修改某个位置上的元素；</li>
<li>运算符修改：对某一个版本，修改某两个元素之间的运算符；</li>
<li>翻转：对某一个版本，将第 $l$ 个元素到第 $r$ 个元素之间的所有元素（包括第 $l$ 个和第 $r$ 个元素）和运算符翻转。</li>
</ul><p>我们记第 $i$ 次操作之后得到的表达式为第 $i$ 个版本。</p>
<p>在每个操作之后，你需要求出当前表达式的值。</p>
<p>你只能通过调用一个函数 <samp>F(a,b,op)</samp>  来得到 <samp>a op b</samp> 的结果，且调用这个函数的次数有一定限制。</p>

# 任务描述


<p>你需要实现以下几个函数：</p>
<ul><li>init(test_id, n, m, k, a, ops)<ul><li>我们首先会调用这个函数。其中：</li>
<li>test_id 为测试点编号，n, m, k 意义见题目描述；</li>
<li>a 为一个大小为 $n$ 的数组，a[i]  表示最初表达式里的第 $i$ 个元素的值（下标从 $0$ 开始）；</li>
<li>ops 为一个大小为 n 的数组，ops[i]  表示第 $i$ 个元素与第 $i-1$ 个元素之间的运算符；</li>
<li>注意 ops[0] 没有意义，请不要尝试去访问它。</li>
</ul></li>
<li>modify_data(id, pos, x)<ul><li>元素修改操作：对第 id 个版本，修改第 $\mathrm{pos}$（$0 \leq \mathrm{pos} &lt; n$）个元素为 $x$，并将修改后的表达式作为一个新的版本。你需要返回修改后表达式的值。</li>
</ul></li>
<li>modify_op(id, pos, new_op)<ul><li>运算符修改操作：对第 id 个版本，修改第 $\mathrm{pos}$（$1 \leq \mathrm{pos} &lt; n$）和第 $\mathrm{pos}-1$ 个元素之间的运算符为 $\mathrm{new\_op}$，并将修改后的表达式作为一个新的版本。你需要返回修改后表达式的值。</li>
</ul></li>
<li>reverse(id,l,r)<ul><li>翻转操作：对第 id 个版本，将第 $l$ 个元素到第 $r$ 个元素之间的所有元素（包括第 $l$ 个和第 $r$ 个元素，$0 \leq l \leq r &lt; n$）和运算符翻转，并将修改后的表达式作为一个新的版本。你需要返回修改后表达式的值。</li>
</ul></li>
</ul><p>其中表达式里的元素（init 函数中 a 数组里的元素，modify_data 中的 $x$，和每次返回的表达式的值）均为 Data 类型，这种类型在交互库里提供了定义。</p>
<p>你可以调用一个函数 F 来得到两个元素做某个运算的结果：</p>
<ul><li>F(a,b,op)<ul><li>返回将 $a,b$ 两个元素做运算 $\mathrm{op}$（$1 \leq \mathrm{op} \leq k$）之后的值。</li>
</ul></li>
</ul><p>请注意：Data 类型中的变量 $x$ 只对交互库有意义，你不需要也不应该访问这个变量。另外请保证传入函数 F 的 $a,b$ 和三种操作函数的返回值为 init、modify_data 或 F 中提供的元素，否则，在使用下发的交互库进行测试时，会发生未知行为（如返回错误的结果，或运行错误等），在最终评测时，该测试点会被判为 0 分。</p>

# 实现细节


<p>本题只支持 C/C++/Pascal。</p>
<p>你需要且只能提交一个源文件 expr.cpp/c/pas 实现上述函数，并遵循下面的命名和接口。</p>
<h4>C/C++</h4>
<p>你需要包含头文件expr.h。</p>
<p>Data 类型的定义：</p>
<pre><code class="sh_cpp">typedef struct {
    int x;
} Data;</code></pre>
<p>最终评测时，Data 类型的定义与题面中给出的一样。
 
你需要实现的函数：</p>
<pre><code class="sh_cpp">void init(
    int test_id, int n, int m, int k,
    const Data *a, const int *ops
);
Data modify_data(int id, int pos, Data x);
Data modify_op(int id, int pos, int new_op);
Data reverse(int id, int l, int r);</code></pre>
<p>函数 F 的接口信息如下：</p>
<pre><code class="sh_cpp">Data F(Data a, Data b, int op);</code></pre>
<p>你需要在本题目录下使用如下命令编译得到可执行程序：</p>
<p>对于C语言：<samp>gcc grader.c expr.c -o expr -O2 -lm</samp></p>
<p>对于C++语言：<samp>g++ grader.cpp expr.cpp -o expr -O2 -lm</samp></p>
<h4>Pascal</h4>
<p>你需要使用单元graderhelperlib。</p>
<p>Data 类型的定义：</p>
<pre><code class="sh_pascal">type Data = record
    x : longint;
end;</code></pre>
<p>最终评测时，Data 类型的定义与题面中给出的一样。
你需要实现的函数：</p>
<pre><code class="sh_pascal">procedure init(
    test_id, n, m, k : longint;
    const a : array of Data;
    const ops : array of longint
);
function modify_data(
    id, pos : longint;
    x : Data
) : Data;
function modify_op(
    id, pos, new_op : longint
) : Data;
function reverse(id, l, r : longint) : Data;</code></pre>
<p>函数 F 的接口信息如下：</p>
<pre><code class="sh_pascal">function F(
    a, b : Data;
    op : longint
) : Data;</code></pre>
<p>你需要在本题目录下使用命令编译得到可执行程序：<samp>fpc grader.pas -o&#34;expr&#34; -O2</samp></p>

# 如何开始答题


<p>本题提供了针对每种语言的样例源代码 expr_sample.cpp/c/pas，选择你所需的语言，将其复制为 expr.cpp/c/pas，按照本节前文中提到的方式进行编译，即能通过编译得到可执行程序。</p>
<p>注意：你只能选择一种语言进行作答，即你本题的试题目录下不能同时存在多个语言的 expr.cpp/c/pas。</p>
<p>接下来你需要修改这个文件的实现，以达到题目的要求。</p>

# 如何测试你的程序


<p>样例交互库将从文件 expr.in 读入以下格式的数据。</p>
<p>第 1 行包含 $4$ 个整数 $\mathrm{test\_id}, n, m, k$，需保证 $n,m$ 不超过 $20000$，$k$ 不超过 $100$。</p>
<p>第 2 行仅包含 $1$ 个整数 $\mathrm{lim}$，表示 F 函数的调用次数的限制，需保证 $\mathrm{lim}$ 不超过 $10^7$。</p>
<p>第 3 行包含 $n-1$ 个整数，第 $i$（$1 \leq i &lt; n$）个整数表示第 $i$ 个运算符。</p>
<p>接下来 $m$ 行，每行先是一个整数 $\mathrm{id}$，然后是对第 $\mathrm{id}$ 个版本的一个操作。接下来 $2$ 或 $3$ 个整数，描述一个操作。每个操作必须为下列之一：</p>
<ul><li>1 pos：修改第 $\mathrm{pos}$（$0 \leq \mathrm{pos} &lt; n$）个元素</li>
<li>2 pos new_op：修改第 $\mathrm{pos}$（$1 \leq \mathrm{pos} &lt; n$）和第 $\mathrm{pos} - 1$ 个元素之间的运算符为 $\mathrm{new\_op}$。</li>
<li>3 l r：将第 $l$ 个元素到第 $r$ 个元素之间的所有元素（包括第 $l$ 个和第 $r$ 个元素）和运算符翻转。</li>
</ul><p>读入完成之后，交互库将调用 init 函数。然后再根据数据调用 $m$ 次 modify_data，modify_op 或 reverse 函数。最后交互库将会用某种（选手们不必知道的）方式来计算你的所有函数返回值的校验和，并输出到文件 expr.out 中。交互库还会输出你调用 F 函数的次数。</p>
<p>如果传入 F 函数的参数非法（op 不在 $1$ 到 $k$ 的范围内，或 $a,b$ 不是由交互库提供的元素），那么交互库会将校验和输出为非法值 $-1$。（因此该测试点得 0 分），然后在下面一行输出错误的详细信息。</p>
<p>如果要使用自己的输入文件进行测试，请保证输入文件按照以上格式，否则不保证程序能正确运行。</p>

# 评分方法


<p>最终评测时只会收取 expr.cpp/c/pas，修改本题目录中的其他文件对评测无效。</p>
<p>题目首先会受到和传统题相同的限制。例如编译错误会导致整道题目得 0 分，运行错误、超过时间限制、超过空间限制等会导致相应测试点得 0 分等。</p>
<p>你只能访问自己定义的和交互库给出的变量及其对应的内存空间，尝试访问其他空间将可能导致编译错误或运行错误。</p>
<p>若程序正常结束，则会开始检验正确性。如果答案不正确，或 F 函数的调用次数超过了测试点的限制，该测试点得 0 分。否则该测试点得满分。</p>
<p>题目中所给的时间、空间限制为你的代码和交互库加起来可以使用的时间和空间。我们保证，对于任何合法的数据，任何语言任何版本的交互库（包括下发给选手的和最终评测时用的），正常运行所用的时间不会超过 $0.2\texttt{s}$，正常运行所用的空间不会超过 $64\texttt{MB}$，也就是说，选手实际可用的时间至少为 $0.8\texttt{s}$，实际可用的空间至少为 $960\texttt{MB}$。
 </p>

# 样例一


<h4>input</h4>
<pre>0 5 5 2
1000
2 1 1 1
0 1 1
1 2 2 2
2 3 1 3
0 3 0 3
0 3 1 1

</pre>

<h4>output</h4>
<pre>120400404

</pre>


# explanation


<p>这是使用试题目录中的 grader 和正确的源程序得到的输出中的校验和。若你的程序得到了不同的校验和，那么你的程序在本样例下是错误的。
我们用 + 和 × 表示这两种运算符，用小写字母表示元素，则每一个版本的表达式为如下形式：</p>
<ul><li>第0个版本：$a \times b+c+d+e$</li>
<li>第1个版本：$a \times f+c+d+e$</li>
<li>第2个版本：$a \times f×c+d+e$</li>
<li>第3个版本：$a \times d+c \times f+e$</li>
<li>第4个版本：$d+c+b \times a+e$</li>
<li>第5个版本：$a \times b+c+d+e$</li>
</ul>
# 样例二


<p>见样例及测评库下载。
 </p>

# 限制与约定


<p>对于所有数据，$\mathrm{lim} = 10^7$。</p>
<p>各测试点满足以下约定：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>$\mathrm{test\_id}$</th><th>$n$</th><th>$m$</th><th>$k$</th><th>其他约定</th></tr></thead><tbody><tr><td>1</td><td>$10$</td><td>$10$</td><td>$1$</td><td rowspan="2">无</td></tr><tr><td>2</td><td>$1000$</td><td>$1000$</td><td>$5$</td></tr><tr><td>3</td><td>$10000$</td><td>$10000$</td><td>$1$</td><td rowspan="2">没有 reverse 操作，第 $i$ 个操作的 id 为 $i-1$</td></tr><tr><td>4</td><td>$20000$</td><td>$20000$</td><td>$1$</td></tr><tr><td>5</td><td>$10000$</td><td>$10000$</td><td>$1$</td><td rowspan="2">第 $i$ 个操作的 id 为 $i-1$</td></tr><tr><td>6</td><td>$20000$</td><td>$20000$</td><td>$1$</td></tr><tr><td>7</td><td>$10000$</td><td>$10000$</td><td>$1$</td><td rowspan="2">无</td></tr><tr><td>8</td><td>$20000$</td><td>$20000$</td><td>$1$</td></tr><tr><td>9</td><td>$15000$</td><td>$15000$</td><td>$3$</td><td rowspan="2">第 $i$ 个操作的 id 为 $i-1$</td></tr><tr><td>10</td><td>$15000$</td><td>$15000$</td><td>$5$</td></tr><tr><td>11</td><td>$15000$</td><td>$15000$</td><td>$3$</td><td rowspan="2">无</td></tr><tr><td>12</td><td>$15000$</td><td>$15000$</td><td>$5$</td></tr><tr><td>13</td><td>$15000$</td><td>$15000$</td><td>$50$</td><td rowspan="4">第 $i$ 个操作的 id 为 $i-1$</td></tr><tr><td>14</td><td>$20000$</td><td>$20000$</td><td>$50$</td></tr><tr><td>15</td><td>$20000$</td><td>$20000$</td><td>$100$</td></tr><tr><td>16</td><td>$20000$</td><td>$20000$</td><td>$100$</td></tr><tr><td>17</td><td>$15000$</td><td>$15000$</td><td>$50$</td><td rowspan="4">无</td></tr><tr><td>18</td><td>$20000$</td><td>$20000$</td><td>$50$</td></tr><tr><td>19</td><td>$20000$</td><td>$20000$</td><td>$100$</td></tr><tr><td>20</td><td>$20000$</td><td>$20000$</td><td>$100$</td></tr></tbody></table></div>


<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$1\texttt{GB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=173">样例及测评库下载</a></p>
