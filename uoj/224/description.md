# 题目描述

<p>随着人类计算机技术的发展，计算机的能力不断提升，让跳蚤国王非常羡慕。</p>
<p>终于有一天,跳蚤国王发布政令：大力发展跳蚤国的计算机产业！然而，跳蚤国尚未进行工业革命，无法制造出电子计算机所需的元器件。但是跳蚤国王想出了一个绝妙的想法：把每只跳蚤作为一个计算节点，每只跳蚤只完成一个特定的小任务。</p>
<p>跳蚤国王带领 $n$ 只跳蚤来到了一片旷野上，把跳蚤作为计算节点在旷野上排列好，并编号为 $1$ 到 $n$。每个计算节点会把某几个（也有可能是 $0$ 个）计算节点的结果作为输入，计算得到输出。除此之外，跳蚤国王还有一个巨型的终端，可以从终端输入和输出数据，这台终端和所有计算节点组成了一台计算机。</p>
<p>记第 $t$ 个计算节点的输出为 $x_t$，该节点的操作可分为以下几种类型：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>名称</th>
<th>操作符（类型）</th>
<th>操作数</th>
<th>计算结果</th>
</tr></thead><tbody><tr><td>输入节点</td><td><samp>I</samp></td><td>无</td><td>从终端读入一个实数作为 $x_t$</td></tr><tr><td>输出节点</td><td><samp>O</samp></td><td>$i$</td><td>$x_t = x_i$，并将 $x_t$ 输出到终端</td></tr><tr><td>加法节点</td><td><samp>+</samp></td><td>$i,j$</td><td>$x_t = x_i + x_j$</td></tr><tr><td>偏移节点</td><td><samp>C</samp></td><td>$i,c$</td><td>$x_t = x_i + c$</td></tr><tr><td>取反节点</td><td><samp>-</samp></td><td>$i$</td><td>$x_t = -x_i$</td></tr><tr><td>左移节点</td><td><samp>&lt;</samp></td><td>$i,k$</td><td>$x_t = x_i \cdot 2^k$</td></tr><tr><td>右移节点</td><td><samp>&gt;</samp></td><td>$i,k$</td><td>$x_t = x_i / 2^k$</td></tr><tr><td>S型节点</td><td><samp>S</samp></td><td>$i$</td><td>$x_t = s(x_i)$</td></tr><tr><td>比较节点</td><td><samp>P</samp></td><td>$i,j$</td><td>\begin{equation}x_t = \begin{cases}-1 &amp; x_i \lt x_j \\ 0 &amp; x_i = x_j \\ 1 &amp; x_i \gt x_j \end{cases}\end{equation}</td></tr><tr><td>Max节点</td><td><samp>M</samp></td><td>$i,j$</td><td>\begin{equation}x_t = \begin{cases}x_i &amp; x_i \gt x_j \\ x_j &amp; x_i \le x_j \end{cases}\end{equation}</td></tr><tr><td>乘法节点</td><td><samp>*</samp></td><td>$i,j$</td><td>$x_t = x_i \cdot x_j$</td></tr></tbody></table></div>

<p>其中，$s(x)$ 的定义如下：（$e$ 为自然常数,其值约为 $2.718281828459045\dots$）
\begin{equation}
s(x) = \frac{1}{1 + e^{-x}}
\end{equation}
$s(x)$ 的函数图像如下图所示：</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/224/w.png" alt="sigmoid"/></p>
<p>上述表格中的操作数 $i, j$ 均要小于当前节点的编号 $t$，这样随着跳蚤国王的一声令下，跳蚤就可以按编号从小到大的顺序，依次获得输入然后计算输出。每个跳蚤的计算能力都是有限的，他们仅可以精确到十进制小数点后 $90$ 位，超过的部分将会被四舍五入。同理，上述表格中的操作数 $c$ 的小数部分也不能超过 $90$ 位。另外，左移节点和右移节点中的操作数 $k$ 必须是非负整数，且不能超过 $10000$。</p>
<p>把跳蚤排列好后，野心勃勃的跳蚤国王决心测试一下这台由跳蚤组成的计算机的计算能力，于是蝈蝈大臣给跳蚤国王献上了 $10$ 个计算任务。完成每个计算任务均需要从终端获取输入，进行中间计算，再用输出节点将结果输出。具体任务说明如下:</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>编号</th>
<th>输入</th>
<th>输入限制</th>
<th>输出</th>
</tr></thead><tbody><tr><td>1</td><td>$a,b$</td><td><div>$\lvert a \rvert, \lvert b \rvert \le 10^9$</div><div>小数部分不超过 $9$ 位</div></td><td>$-2a-2b$</td></tr><tr><td>2</td><td>$a$</td><td><div>$\lvert a \rvert \le 10^9$</div><div>小数部分不超过 $9$ 位</div></td><td>$\frac{1}{1+e^{17a}}$</td></tr><tr><td>3</td><td>$a$</td><td><div>$\lvert a \rvert \le 10^9$</div><div>小数部分不超过 $9$ 位</div></td><td>\begin{equation}\begin{cases}-1 &amp; a \lt 0 \\ 0 &amp; a = 0 \\ 1 &amp; a \gt 0\end{cases}\end{equation}</td></tr><tr><td>4</td><td>$a$</td><td><div>$\lvert a \rvert \le 10^9$</div><div>小数部分不超过 $9$ 位</div></td><td>$\lvert a \rvert$，即 $a$ 的绝对值</td></tr><tr><td>5</td><td>$a_1, \dots, a_{32}$</td><td>$a_1, \dots, a_{32} \in \{0, 1\}$</td><td>把 $a_1, \dots, a_{32}$ 从左到右看成一个二进制整数，高位在左低位在右，输出该整数的值</td></tr><tr><td>6</td><td>$a$</td><td><div>$0 \le a \lt 2^{32}$</div><div>$a$ 为整数</div></td><td>输出 $32$ 个整数，从高位到低位输出 $a$ 的二进制表示（不足 $32$ 位的在高位补 $0$）</td></tr><tr><td>7</td><td>$a,b$</td><td><div>$0 \le a, b \lt 2^{32}$</div><div>$a,b$ 均为整数</div></td><td>$a, b$ 按位异或的结果</td></tr><tr><td>8</td><td>$a$</td><td><div>$\lvert a \rvert \le 10^9$</div><div>小数部分不超过 $9$ 位</div></td><td>$\frac{a}{10}$</td></tr><tr><td>9</td><td>$a_1, \dots, a_{16}$</td><td><div>$\lvert a_1 \rvert, \dots, \lvert a_{16} \rvert \le 10^9$</div><div>小数部分不超过 $9$ 位</div></td><td>输出 $16$ 个实数，表示 $a_1, \dots, a_{16}$ 从小到大排序后的结果</td></tr><tr><td>10</td><td>$a,b,m$</td><td><div>$0 \le a, b \lt 2^{32}$</div><div>$1 \le m \lt 2^{32}$</div><div>$a,b,m$ 均为整数</div></td><td>$a \cdot b$ 除以 $m$ 的余数</td></tr></tbody></table></div>

<p>跳蚤国王发现自己没有足够的能力设计这样的计算机。于是他找到了来参加 NOI 的你。请你依次设计每个计算节点的类型及操作数，完成蝈蝈大臣给的这 $10$ 个计算任务，且要求使用的计算节点数尽量少。</p>

# 输入格式


<p>所有输入数据 nodes1.in~nodes10.in 见数据下载，分别对应 $10$ 个计算任务。</p>
<p>每组输入数据仅包含一个整数，表示需要解决的计算任务编号。</p>

# 输出格式


<p>输出文件为 nodes1.out~nodes10.out，分别对应相应的输入文件。</p>
<p>对于每组输入数据，你需要依次输出若干行，第 $i$ 行描述第 $i$ 个计算节点。</p>
<p>描述每个计算节点时，首先一个字符表示该计算节点的类型，接下来若干个数按顺序表示该计算节点的内置参数。字符与数，数与数之间均用空格隔开。</p>
<p>输出的行数不能超过 $10^4$ 行。</p>

# 样例一


<h4>input</h4>
<pre>1

</pre>

<h4>output</h4>
<pre>I
+ 1 1
- 2
I
+ 4 4
- 5
+ 3 6
- 7
- 8
O 9

</pre>

<h4>explanation</h4>
<p>该样例输出为第一个计算任务一个可能的构造。共用了 $10$ 个计算节点，可获得 $3$ 分。</p>

# 子任务及部分分


<p>我们提供了十个评分文件 nodes1.ans~nodes10.ans，分别对应每个计算任务。</p>
<p>每个评分文件共 10 行，第 i 行一个评分参数 $w_i$，具体意义将在下面给出。</p>
<p>本题中，每个测试点单独进行评分，每个测试点 $10$ 分。</p>
<p>如果选手的输出格式不合法或者参数不符合题目约定,则得 $0$ 分。</p>
<p>否则，按照以下规则判定选手的输出是否正确：</p>
<p>首先测评器会生成若干组输入数据，并将输入数据代入你构造的计算机。</p>
<p>如果在代入某一组输入数据时：你构造的计算机的计算过程中，某个计算节点的计算结果的绝对值超过 $10^{1000}$，则得 $0$ 分；你构造的计算机的输出中的某个值与预期的输出值相差超过 $10^{-9}$，则认为你的输出不正确，得 $0$ 分。</p>
<p>否则，我们认为你的计算机能完成给定的计算任务，并按照以下规则得分。</p>
<p>对于每个测试点，我们设置了 $10$ 个评分参数 $w_1 , w_2 , w_3 , \dots , w_9 , w_{10}$。</p>
<p>假设共使用了 $n$ 个计算节点,你的分数将会由下表给出：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>得分</th>
<th>条件</th>
<th>得分</th>
<th>条件</th>
</tr></thead><tbody><tr><td>$10$</td><td>$n \le w_{10}$</td><td>$5$</td><td>$n \le w_5$</td></tr><tr><td>$9$</td><td>$n \le w_{9}$</td><td>$4$</td><td>$n \le w_4$</td></tr><tr><td>$8$</td><td>$n \le w_{8}$</td><td>$3$</td><td>$n \le w_3$</td></tr><tr><td>$7$</td><td>$n \le w_{7}$</td><td>$2$</td><td>$n \le w_2$</td></tr><tr><td>$6$</td><td>$n \le w_{6}$</td><td>$1$</td><td>$n \le w_1$</td></tr></tbody></table></div>

<p>若不符合表中所有条件，得 0 分；若符合表中的多个条件，则取分数最高的。</p>
<p>除此之外，使用比较节点、Max 节点和乘法节点的代价是极为昂贵的。因此，这三种节点每使用<strong>一种</strong>，就会从你这个测试点的得分中倒扣 4 分。</p>
<p>注意这里是按使用节点的种类数计算扣分，与使用次数无关。例如多次使用比较节点，只会扣除 $4$ 分；又如同时使用了比较节点和乘法节点，即使各只使用了一次，也会扣除 8 分。</p>
<p>一个测试点至多被扣到 $0$ 分，即使分数不够扣除，也不会出现负数。</p>

# 如何测试你的输出


<p>在终端中先切换到该试题的目录下：（windows用户请使用cmd）（假设你把输入输出文件、checker 什么的都放在了 nodes 这个文件夹下）</p>
<p><code>cd nodes</code></p>
<p>我们提供checker这个工具来测试你的输出文件是否是可接受的。使用这个工具的方法是，在终端中运行</p>
<p><code>./checker_linux64 &lt;case_no&gt;</code></p>
<p>其中<code>case_no</code>是测试数据的编号。例如</p>
<p><code>./checker_linux64 3</code></p>
<p>将测试 nodes3.out 是否可以接受。（windows用户请使用<code>checker_win32 3</code>）（什么你是windows 64位？放心吧可以运行win32应用程序的。）</p>
<p>当然我们有对应的 linux 32 位版本：<code>checker_linux32</code>。如果 linux 用户发现无法运行程序，请尝试执行 <code>chmod +x checker_linux64</code> 或 <code>chmod +x checker_linux32</code> 后重试。</p>
<p>其它操作系统请安装 <a href="//nodejs.org/">node.js</a> 然后使用 <code>node checker.js &lt;case_no&gt;</code> 运行checker。</p>
<p>在你调用这个程序后，checker 将根据你给出的输出文件给出测试的结果。</p>
<p>另外,你还可以在终端中使用命令</p>
<p><code>./checker –f &lt;file_name&gt;</code></p>
<p>来运行 <code>&lt;file_name&gt;</code> 表示的计算机，并通过终端进行交互。</p>
<p><strong>注意: checker 测试你构造的计算机时，使用的数据跟最终测试时可能不同。</strong></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=224">输入数据及checker下载</a></p>
