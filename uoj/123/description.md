# 题目描述

<p>小 Q 最近发现了一款新游戏，游戏的目标是从一个新手修炼成为武功高强的大侠。</p>
<p>面对错综复杂的游戏世界，小 Q 要对他面临的每件事情做出谨慎的选择。例如，是否参加一个陌生人邀请的比武；同意或是拒绝用宝剑交换他人的武功秘籍……而小 Q 做出的每一个选择都有可能影响到他以后的发展：面对一个高手，若主动与之比武，很可能会损失惨重；但若不去比武，也许今后就再也见不到这个高手了。</p>
<p>对着这个游戏，小 Q 玩了很多次仍然玩不出他想要的结局，于是他费尽千辛万苦找到了游戏的剧本。令人惊讶的是，游戏的剧本并不像我们平时见到的剧本，反而很像代码。这个剧本是这样描述的：</p>
<p>量：有 $2$ 种量，常数和变量。</p>
<p>常数：一个整数。</p>
<p>变量：初始值为 $0$ 的可变整数，不同变量用不同正整数区分。</p>
<p>事件：整个剧本由若干个事件构成。所有的事件按照给定的顺序从 $1$ 开始依次编号。事件共有 $3$ 种：普通事件、选择跳转和条件跳转。</p>
<p>执行位置：一个整数，表示接下来将会执行的事件编号，如果不存在这个编号的事件则停止，即游戏到了一个结局。最初的时候执行位置为 $1$。</p>
<p>普通事件：一个变量增加或减少一个量的值。之后执行位置增加 $1$。</p>
<p>选择跳转：两个整数。执行到这里时玩家需要在这两个整数中选择一个，之后执行位置将被修改为这个整数。</p>
<p>条件跳转：两个量和两个整数。执行到这里时，若第一个量小于第二个量，则执行位置将被修改为第一个整数，否则将被修改为第二个整数。</p>
<p>小 Q 认为，整个游戏是希望一个叫做“成就值”的变量（编号为 $1$）最大。</p>

# 输入格式


<p>所有输入数据 <samp>train1.in ~ train10.in</samp> 见数据下载。</p>
<p>输入的第一行包含两个正整数 $n,m$，表示事件的个数和变量的个数。</p>
<p>接下来有 $n$ 行，每行描述一个事件。这些事件按照给出的顺序依次编号为 $1$ 到 $n$。</p>
<p>描述量和事件的格式如下（“格式” 中 “<samp>#</samp>”表示空格）。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>类型</th><th>格式</th><th>例子</th></tr></thead><tbody><tr><td>常数</td><td><samp>c#整数</samp></td><td><samp>c -2</samp></td></tr><tr><td>变量</td><td><samp>v#正整数</samp></td><td><samp>v 5</samp></td></tr><tr><td>普通事件</td><td><div><samp>变量#+#量</samp></div><div><samp>变量#-#量</samp></div></td><td><div><samp>v 1 + c -1</samp></div><div><samp>v 2 - v 2</samp></div></td></tr><tr><td>选择跳转</td><td><samp>s#整数1#整数2</samp></td><td><samp>s 10 20</samp></td></tr><tr><td>条件跳转</td><td><samp>i#量1#量2#整数1#整数2</samp></td><td><samp>i c 99 v 2 0 1</samp></td></tr></tbody></table></div>


# 输出格式


<p>针对给定的 10 个输入文件 <samp>train1.in ~ train10.in</samp>，你需要分别提交你的输出文件 <samp>train1.out ~ train10.out</samp>。</p>
<p>每个文件需要输出若干行，每行输出一个字符“1”或“2”，表示执行过程中遇到的每个选择跳转所作的选择。</p>
<p>输出的行数需要严格等于此次游戏执行过程中遇到的选择跳转的个数。</p>

# 样例一


<h4>input</h4>
<pre>11 2
v 2 + c 19
i v 2 c 3 7 3
s 4 7
v 1 + c 13
v 2 - c 3
i c 0 c 1 2 0
i v 2 c 5 12 8
s 9 12
v 1 + c 23
v 2 - c 5
i c 0 c 1 7 0

</pre>

<h4>output</h4>
<pre>1
1
1
2
1
1

</pre>

<h4>explanation</h4>
<p>根据样例输出的方案，执行位置进行了如下的变化：</p>
<p>1 → 2 → 3 → 4 → 5 → 6 → 2 → 3 → 4 → 5 → 6 → 2 → 3 → 4 → 5 → 6 → 2 → 3 → 7 → 8 → 9 → 10 → 11 → 7 → 8 → 9 → 10 → 11 → 7 → 12</p>
<p>当执行位置变成 $12$ 时，剧本结束。最终变量 $1$ 的值为 $85$。</p>
<p>事件 $1$ 为变量 $2$ 增加 $19$，可以认为是得到了 $19$ 单位的初始资金。</p>
<p>事件 $6$ 为无条件跳转到事件 $2$，可以看出这里是一个循环。从事件 $2$ 和事件 $3$ 可以看出，如果变量 $2$ 小于 $3$（资金不足一次购买）或者选择放弃则会跳出循环。</p>
<p>循环内的事件 $4$ 和事件 $5$ 为花费 $3$ 的资金得到 $13$ 的成就值。</p>
<p>事件 $7$ 到 $11$ 也是一个类似的循环，只是参数有所不同。为花费 $5$ 的资金得到 $23$ 的成就值。</p>

# 评分方式


<p>对于每组数据，我们采用如下方式评分：如果你的输出不合法，得 $0$ 分。如果你的输出执行了超过 $10^6$ 行剧本,得 $0$ 分。如果你的输出能让剧本正常结束，得 $1$ 分。如果你的输出能让剧本正常结束，且结束时成就值为正数，得 $2$ 分。我们设置了 $8$ 个评分参数 $a_3, a_4, \dots, a_{10}$。如果你的输出能让剧本正常结束，且结束时成就值不小于 $a_s$，得 $s$ 分。如果以上条目有多项满足，则取满足条件中的最高得分。</p>
<p>形式化地讲，设在你的方案中，变量 $1$ 最终的值为 $v_1$。当你的输出合法时，你的分数将会由下表给出：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>得分</th><th>条件</th><th>得分</th><th>条件</th></tr></thead><tbody><tr><td>10</td><td>$v_1 \geq a_{10}$</td><td>5</td><td>$a_5 \leq v_1 &lt; a_6$</td></tr><tr><td>9</td><td>$a_9 \leq v_1 &lt; a_{10}$</td><td>4</td><td>$a_4 \leq v_1 &lt; a_5$</td></tr><tr><td>8</td><td>$a_8 \leq v_1 &lt; a_9$</td><td>3</td><td>$a_3 \leq v_1 &lt; a_4$</td></tr><tr><td>7</td><td>$a_7 \leq v_1 &lt; a_8$</td><td>2</td><td>$0 &lt; v_1 &lt; a_3$</td></tr><tr><td>6</td><td>$a_6 \leq v_1 &lt; a_7$</td><td>1</td><td>$v_1 \leq 0$</td></tr></tbody></table></div>

<p>在终端中先切换到该试题的目录下：（windows用户请使用cmd）</p>
<p><code>cd train</code></p>
<p>我们提供checker这个工具来测试你的输出文件是否是可接受的。使用这个工具的方法是，在终端中运行</p>
<p><code>./checker_linux64 &lt;case_no&gt;</code></p>
<p>其中<code>case_no</code>是测试数据的编号。例如</p>
<p><code>./checker_linux64 3</code></p>
<p>将测试 <samp>train3.out</samp> 是否可以接受。（windows用户请使用<code>checker_win32 3</code>）（什么你是windows 64位？放心吧可以运行win32应用程序的。）</p>
<p>当然我们有对应的linux 32位版本：<code>checker_linux32</code>。如果linux用户发现无法运行程序，请尝试执行<code>chmod +x checker_linux64</code>或<code>chmod +x checker_linux32</code>后重试。</p>
<p>其它操作系统请安装 <a href="//nodejs.org/">node.js</a> 然后使用 <code>node checker.js &lt;case_no&gt;</code> 运行checker。</p>
<p>在你调用这个程序后，checker将根据你给出的输出文件给出测试的结果。</p>

# 更多功能


<p>checker 还可以检查任意输入输出文件的测试结果,方法是在终端中运行:</p>
<p><code>./checker_linux64 &lt;input_filename&gt; &lt;output_file_name&gt;</code></p>
<p>其中 <code>input_file_name</code> 和 <code>output_file_name</code> 分别是输入输出文件的名称。</p>
<p>例如：</p>
<p><code>./checker_linux64 train3.in train3.out</code></p>
<p>将测试测试 <samp>train3.out</samp> 是否可以接受。</p>
<p>使用 <code>-w</code> 可以输出每步运行的结果。用法是：</p>
<p><code>./checker_linux64 -w &lt;input_file_name&gt; &lt;output_file_name&gt;</code></p>
<p>或者</p>
<p><code>./checker_linux64 -w &lt;case_no&gt;</code></p>
<p>例如</p>
<p><code>./checker_linux64 -w train3.in train3.out</code></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=123">输入数据及checker下载</a></p>
