# 题目描述

<p>在 2111 年，第 128 届全国青少年信息学奥林匹克冬令营前夕，Z君找到了 2015 年，第 32 届冬令营的题目来练习。</p>
<p>他打开了第三题 “未来程序” 这道题目：</p>
<p>“本题是一道提交答案题，一共 10 个测试点。</p>
<p>对于每个测试点，你会得到一段程序的源代码和这段程序的输入。你要运行这个程序，并保存这个程序的输出。</p>
<p>遗憾的是这些程序都效率极其低下，无法在比赛的 5 个小时内得到输出。”</p>
<p>Z君想了一下，决定用 2111 年的计算机来试着运行这个题目，但是问题来了，Z君已经找不到 96 年前的那次比赛的测试数据了……</p>
<p>没有给出输入数据的提交答案题就不成其“提交答案题”之名，为了解决这个问题，Z君决定将这个题目改造成传统题。</p>
<p>Z君知道 96 年前的计算机的性能比现在差多了，所以这道题的测试数据中，输入数据的规模被设计成很小，从而，做这道题的选手只需要暴力模拟源代码的工作流程就可以通过它。</p>
<p>现在这道题摆到了你的面前。</p>
<p>本题是一道传统题，一共有 10 个测试点。</p>
<p>对于每个测试点，你的程序会得到一段程序的源代码和这段程序的输入。你的程序需要运行这段程序，并输出这段程序的输出。</p>

# 关于给出的源代码的约定


<p>Z君是一名C++选手。为了简化这个问题，Z君在给出的源代码中去掉了C++语言的大量特性。从而这个源代码具有以下特点：</p>
<ul><li>第一行必定为 “<samp>#include&lt;iostream&gt;</samp>” （不含引号）<ul><li>这个库中只会调用到对象 <samp>cin</samp>，<samp>cout</samp>，<samp>endl</samp>，<samp>cin</samp> 的 <samp>&gt;&gt;(int)</samp> 函数和 <samp>cout</samp> 的 <samp>&lt;&lt;(int)</samp> 函数。这两个函数分别用于输入和输出一个整数，返回值分别 <samp>cin</samp> 和 <samp>cout</samp>。</li>
</ul></li>
<li>第二行必定为 “<samp>#include&lt;cstdio&gt;</samp>” （不含引号）<ul><li>这个库中只会调用到 <samp>putchar</samp> 函数。<samp>putchar(c)</samp> 会输出 ASCII 码为 $c$ 的字符，并返回 $c$。</li>
</ul></li>
<li>第三行必定为 “<samp>using namespace std;</samp>” （不含引号）<ul><li>对象 <samp>cin</samp> 的调用不再需要通过 <samp>std::cin</samp> 进行，<samp>cout</samp> 和 <samp>endl</samp> 同理。</li>
</ul></li>
<li><samp>int main()</samp> 没有任何参数。</li>
<li>所有的变量都是 <samp>int</samp> 或 <samp>int</samp> 数组（含高维数组）类型。<ul><li>对象 <samp>cin</samp>, <samp>cout</samp>, <samp>endl</samp> 是例外，注意 <samp>putchar</samp> 的参数也是int类型的。我们保证在运行时这个参数的值在 $0 \sim 127$ 中。</li>
<li>在运行时，不会出现数组越界问题。</li>
<li>没有维度的范围为 $1$。也即，不会出现 <samp>int a[1][1][1][1][1];</samp> 这样的情况。</li>
<li>维度的范围直接由十进制常量给出。也即，不会出现 <samp>int a[(100+100)*2];</samp> 这样的情况。</li>
</ul></li>
<li>所有的函数都是 <samp>int</samp> 类型，函数的参数只可能是 <samp>int</samp> 类型<ul><li>注意函数的返回值可以被丢弃。</li>
<li>当没有显式地返回值时，返回 $0$。</li>
</ul></li>
<li><samp>bool</samp> 型被认为是一种特殊的 <samp>int</samp> 型<ul><li><samp>==</samp> 在两个参数相同时返回 $1$，否则返回 $0$。</li>
<li><samp>!=</samp> 在两个参数相同时返回 $0$，否则返回 $1$。</li>
<li><samp>&lt;</samp> 在第一个参数小于第二个参数时返回 $1$，否则返回 $0$。</li>
<li><samp>&lt;=</samp> 在第一个参数小于等于第二个参数时返回 $1$，否则返回 $0$。</li>
<li><samp>&gt;</samp> 在第一个参数大于第二个参数时返回 $1$，否则返回 $0$。</li>
<li><samp>&gt;=</samp> 在第一个参数大于等于第二个参数时返回 $1$，否则返回 $0$。</li>
<li><samp>&amp;&amp;</samp> 在两个参数都不为 $0$ 时返回 $1$，否则返回0。</li>
<li><samp>||</samp> 在两个参数都为 $0$ 时返回 $0$，否则返回 $1$。</li>
<li><samp>^</samp> 在两个参数中只有一个为 $0$ 时返回 $1$，其他时候返回 $0$。</li>
<li><samp>!</samp> 在参数为 $0$ 时返回 $1$，否则返回 $0$。</li>
<li>由于 <samp>bool</samp> 型被 <samp>int</samp> 型取代了，因此所有的表达式都应该被完全计算：例如在表达式 <samp>(a &amp;&amp; (b = c))</samp>中，即使 <samp>a</samp> 已经被确定是 $0$，仍然需要计算 <samp>(b = c)</samp> 的值，尽管无论 <samp>(b = c)</samp> 的值如何，整个表达式的值都是 $0$。</li>
</ul></li>
<li>可能用到的运算符及其优先级如下：（从高到低排列）<ol><li><samp>()</samp>, <samp>[]</samp></li>
<li><samp>!</samp>, <samp>+</samp>（正号）, <samp>-</samp>（负号）</li>
<li><samp>*</samp>, <samp>/</samp>, <samp>%</samp></li>
<li><samp>+</samp>（加法）, <samp>-</samp>（减法）</li>
<li><samp>&lt;=</samp>, <samp>&gt;=</samp>, <samp>&lt;</samp>, <samp>&gt;</samp></li>
<li><samp>==</samp>, <samp>!=</samp></li>
<li><samp>^</samp></li>
<li><samp>&amp;&amp;</samp></li>
<li><samp>||</samp></li>
<li><samp>=</samp></li>
<li><samp>cout</samp> 的 <samp>&lt;&lt;</samp> 与 <samp>cin</samp> 的 <samp>&gt;&gt;</samp>。</li>
</ol></li>
<li>所有 <samp>int</samp> 常量以十进制形式给出</li>
<li>Z君没有对源代码进行混淆，所以源代码是可读的，你不必担心出现大量嵌套的花括号或此类的“垃圾代码”</li>
<li>运行时使用的变量占用的空间的峰值不超过 $8\texttt{MB}$。也即，$2^{21}$ 个 <samp>int</samp></li>
<li>调用函数的深度不会超过 $10^3$ 层</li>
<li>可能出现连续赋值，例如 <samp>a = (b = (c = 3) + 2) % c</samp><ul><li>之前对 <samp>c</samp> 的赋值将会反映到之后对 <samp>c</samp> 的引用上</li>
<li><samp>=</samp> 是右结合的，<samp>a = b = c</samp> 会被看作 <samp>a = (b = c)</samp></li>
<li>赋值的返回值为赋值以后的值</li>
</ul></li>
<li>可能出现的程序流程控制语句：<ul><li><samp>if (statement) statement [else statement]</samp></li>
<li><samp>while (statement) statement</samp></li>
<li><samp>for ([statement]; [statement]; [statement]) statement</samp></li>
<li>那些作为条件的 <samp>statement</samp> 的返回值应当被视为 <samp>bool</samp> 型的。具体的来说，若返回值为 $0$，则为 <samp>false</samp>，若返回值非 $0$，则为 <samp>true</samp>。在 <samp>for</samp> 循环中，当第二个 <samp>[statement]</samp> 取空时，视为 <samp>true</samp>。</li>
</ul></li>
<li>空白字符只有新行符（即 <samp>\n</samp>）和空格。</li>
<li>声明变量时默认初始值为 $0$，声明变量的同时不会进行赋值。</li>
<li>没有注释</li>
<li>所有的右花括号后没有分号</li>
<li>没有用来连接语句的逗号</li>
<li>没有函数和变量重名</li>
</ul>
# 输入格式


<p>输入文件分为两个部分。</p>
<p>第一行，有一个整数 $N$。它描述了源代码对应的输入文件 <samp>program.in</samp> 中包含的整数数目。</p>
<p>以下 $N$ 个整数构成了源代码对应的输入文件 <samp>program.in</samp>。</p>
<p>这之后的部分构成了源代码 <samp>program.cpp</samp>。</p>

# 输出格式


<p>输出文件是将 <samp>program.cpp</samp> 编译后输入 <samp>program.in</samp> 后所得到的输出。</p>

# 样例一


<h4>input</h4>
<pre>2
1 2
#include&lt;iostream&gt;
#include&lt;cstdio&gt;
using namespace std;
int main()
{int a, b; cin &gt;&gt; a &gt;&gt; b; cout &lt;&lt; a + b &lt;&lt; endl;}

</pre>

<h4>output</h4>
<pre>3

</pre>


# 样例二


<h4>input</h4>
<pre>10
9
6 1 7 5 1 7 2 2 4
#include&lt;iostream&gt;
#include&lt;cstdio&gt;
using namespace std;
int n, a[100];


int main()
{
    cin &gt;&gt; n;
    int i, j, this_VARIABLE_is_NOT_used;
    for (i = 1; i &lt;= n; i = i + 1) cin &gt;&gt; a[i];
    for (i = 1; i &lt;= n; i = i + 1)
    for (j = i + 1; j &lt;= n; j = j + 1)
    if (a[i] &gt; a[j])
    {
        int t;
        t = a[i];
        a[i] = a[j];
        a[j] = t;
    }
    for (i = 1; i &lt;= n; i = i + 1)
    {
        cout &lt;&lt; a[i];
        if (i == n) cout &lt;&lt; endl; else putchar(32);
    }
    return 0;
}

</pre>

<h4>output</h4>
<pre>1 1 2 2 4 5 6 7 7

</pre>


# 限制与约定


<p>输入的所有 <samp>program.cpp</samp> 都是手打的，每个输入文件的大小不超过 $7\texttt{KB}$。</p>
<p>测试点#1的 <samp>program.cpp</samp> 见样例数据及附加文件下载。</p>
<p>测试点#2到#4的 <samp>program.cpp</samp> 符合以下格式：</p>
<pre><code class="sh_cpp">#include&lt;iostream&gt;
#include&lt;cstdio&gt;
using namespace std;
int main()
{
    cout &lt;&lt; &lt;1&gt; &lt;&lt; endl;
}</code></pre>
<p>在#2中：<samp>&lt;1&gt;</samp> 处是一个仅包含加、减、乘、除、模运算和自然数常数的没有括号的表达式。</p>
<p>在#3和#4中：<samp>&lt;1&gt;</samp> 处是一个不保证以上性质的表达式。</p>
<p>测试点#5中：没有除 <samp>main</samp> 以外的函数，并且整个程序中只有顺序结构。</p>
<p>测试点#6和#7中：没有除 <samp>main</samp> 以外的函数。</p>
<p>测试点#8中：所有的变量都是全局变量。</p>
<p>测试点#9和#10不保证任何特别的性质。</p>
<p>所有 <samp>program.cpp</samp> 都可以用 MinGW GCC 4.7.2 编译运行。这就是说，所有的 <samp>program.cpp</samp> 中都没有语法错误。然而由于编译命令的不同，直接编译得到的 <samp>program.exe</samp> 在运行时有可能会因未为声明的变量和未设置返回值的函数设置 $0$ 的缺省值以及 <samp>bool</samp> 类型的处理方式不同而与标程产生不同的输出。</p>
<p>为了更准确地说明程序可能出现的要素，也作为提示，下面给出了一个上下文无关文法，其初始符号为 <samp><strong>PROGRAM</strong></samp>。保证每个 <samp>program.cpp</samp> 都可被下面的文法生成，但是并非每个可被生成的程序都是合法的程序。</p>
<pre><strong>PROGRAM</strong> ::= # include &lt; iostream &gt; # include &lt; cstdio &gt; using namespace std ; <strong>FUNC_AND_VAR</strong>

<strong>FUNC_AND_VAR</strong> ::=
| ε
| int <strong>NAME</strong> ( <strong>OPTPARAMS</strong> ) { <strong>STATEMENTS</strong> } <strong>FUNC_AND_VAR</strong>
| int <strong>DEFINEVAR</strong> <strong>DEFINEVARS</strong> ; <strong>FUNC_AND_VAR</strong>

<strong>OPTPARAMS</strong> ::=
| ε
| int <strong>NAME</strong> <strong>PARAMS</strong>

<strong>PARAMS</strong> ::=
| ε
| , int <strong>NAME</strong> <strong>PARAMS</strong>

<strong>STATEMENTS</strong> ::=
| ε
| <strong>STATEMENT</strong> <strong>STATEMENTS</strong>

<strong>STATEMENT</strong> ::=
| <strong>EXPRESSION</strong> ;
| { <strong>STATEMENTS</strong> }
| int <strong>DEFINEVAR</strong> <strong>DEFINEVARS</strong> ;
| if ( <strong>EXPRESSION</strong> ) <strong>STATEMENT</strong>
| if ( <strong>EXPRESSION</strong> ) <strong>STATEMENT</strong> else <strong>STATEMENT</strong>
| for ( <strong>STATEMENT_IN_FOR</strong> ; <strong>OPTEXPRESSION</strong> ; <strong>STATEMENT_IN_FOR</strong> ) <strong>STATEMENT</strong>
| while ( <strong>EXPRESSION</strong> ) <strong>STATEMENT</strong>
| return <strong>EXPRESSION</strong> ;

<strong>STATEMENT_IN_FOR</strong> ::=
| <strong>OPTEXPRESSION</strong>
| int <strong>DEFINEVAR</strong> <strong>DEFINEVARS</strong>

<strong>OPTEXPRESSION</strong> ::=
| ε
| <strong>EXPRESSION</strong>

<strong>EXPRESSION</strong> ::=
| <strong>UNIT9</strong>
| <strong>EXPRESSION</strong> &lt;&lt; <strong>UNIT9</strong>
| <strong>EXPRESSION</strong> &gt;&gt; <strong>UNIT9</strong>

<strong>UNIT0</strong> ::=
| <strong>INT_CONSTANT</strong>
| <strong>UNIT0</strong> [ <strong>EXPRESSION</strong> ]
| ( <strong>EXPRESSION</strong> )
| <strong>NAME</strong> ( <strong>OPTARGUS</strong> )    // 注：此处的 <strong>NAME</strong> 是一个函数名
| <strong>NAME</strong>    // 注：此处的 <strong>NAME</strong> 是一个变量名
| cin
| cout
| endl

<strong>UNIT1</strong> ::=
| <strong>UNIT0</strong>
| + <strong>UNIT1</strong>
| - <strong>UNIT1</strong>
| ! <strong>UNIT1</strong>

<strong>UNIT2</strong> ::=
| <strong>UNIT1</strong>
| <strong>UNIT2</strong> * <strong>UNIT1</strong>
| <strong>UNIT2</strong> / <strong>UNIT1</strong>
| <strong>UNIT2</strong> % <strong>UNIT1</strong>

<strong>UNIT3</strong> ::=
| <strong>UNIT2</strong>
| <strong>UNIT3</strong> + <strong>UNIT2</strong>
| <strong>UNIT3</strong> - <strong>UNIT2</strong>

<strong>UNIT4</strong> ::=
| <strong>UNIT3</strong>
| <strong>UNIT4</strong> &lt; <strong>UNIT3</strong>
| <strong>UNIT4</strong> &lt;= <strong>UNIT3</strong>
| <strong>UNIT4</strong> &gt; <strong>UNIT3</strong>
| <strong>UNIT4</strong> &gt;= <strong>UNIT3</strong>

<strong>UNIT5</strong> ::=
| <strong>UNIT4</strong>
| <strong>UNIT5</strong> == <strong>UNIT4</strong>
| <strong>UNIT5</strong> != <strong>UNIT4</strong>

<strong>UNIT6</strong> ::=
| <strong>UNIT5</strong>
| <strong>UNIT6</strong> ^ <strong>UNIT5</strong>

<strong>UNIT7</strong> ::=
| <strong>UNIT6</strong>
| <strong>UNIT7</strong> &amp;&amp; <strong>UNIT6</strong>

<strong>UNIT8</strong> ::=
| <strong>UNIT7</strong>
| <strong>UNIT8</strong> || <strong>UNIT7</strong>

<strong>UNIT9</strong> ::=
| <strong>UNIT8</strong>
| <strong>UNIT8</strong> = <strong>UNIT9</strong>

<strong>OPTARGUS</strong> ::=
| ε
| <strong>EXPRESSION</strong> <strong>ARGUS</strong>

<strong>ARGUS</strong> ::=
| ε
| , <strong>EXPRESSION</strong> <strong>ARGUS</strong>

<strong>DEFINEVARS</strong> ::=
| ε
| , <strong>DEFINEVAR</strong> <strong>DEFINEVARS</strong>

<strong>DEFINEVAR</strong> ::=
| <strong>NAME</strong>
| <strong>DEFINEVAR</strong> [ <strong>INT_CONSTANT</strong> ]

<strong>NAME</strong> ::= 仅包含大小写字母、数字、下划线的非空字符串，且不以数字开头。

<strong>INT_CONSTANT</strong> ::= 仅包含数字的非空字符串，且不以0开头，或这个字符串就是0。
</pre>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 来源


<p>中国国家集训队互测2015 - By 卢啸尘</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=98">样例数据及附加文件下载</a></p>
