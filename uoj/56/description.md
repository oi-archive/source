# 题目描述

<p>“非确定机”是现在假想中的一种计算机，它可以同时运行任意多段指令。这种计算机中允许一种新的分支指令，执行到这条指令时，程序会一分为二，同时分别执行这两个分支。</p>
<p>“非确定机”的一个神奇功能是程序反转。给定一个程序和该程序的输出，它可以用相同的时空代价得到一个符合该输出的输入。这道题目正是要你反转运行一个程序。</p>
<p>在本题中，你有一个已编译好的，包含一些算法的程序 prog。它的输入为一个有向图 $G$ 和算法编号 $k$，输出为在有向图 $G$ 上运行算法 $k$ 得到的结果。同时，你会得到 10 个由程序 prog 运行得到的输出文件。你的任务是对每个输出文件给出一个可能的输入文件。</p>
<p>为了区分，在后文中如果没有特殊说明，我们<strong>把给定的程序 prog 的输出文件称作“输入”，把你需要提交的程序 prog 的输入文件称作“输出”</strong>。</p>

# 输入格式


<p>该题为提交答案型试题。所有输入数据 nm1.in ~ nm10.in 见数据下载。</p>
<p>输入的第一行包含三个正整数 $n, k, p$，表示图 $G$ 的点数，当前使用算法和一个由 $G$ 计算出的评分参数。</p>
<p>接下来有若干行，每行包含若干个整数，其意义需要你去探究。</p>

# 输出格式


<p>针对给定的 10 个输入文件 nm1.in ~ nm10.in，你需要分别提交你的输出文件 nm1.out ~ nm10.out。</p>
<p>输出文件的第一行包含 $3$ 个整数 $n, m, k$，表示有向图 $G$ 的点数，边数和当前使用的算法。</p>
<p>接下来 $m$ 行，每行包含 $3$ 个整数 $u, v, w$，表示一条从节点 $u$ 连向节点 $v$，权值为 $w$ 的有向边。其中节点的编号用 $1$ 到 $n$ 的整数表示。要求 $w$ 必须为不超过 $20000$ 的非负整数，且不能出现重边。允许出现自环。</p>

# 程序的使用


<p>在终端中先切换到该试题的目录下：（windows用户请使用cmd）</p>
<p><code>cd game</code></p>
<p>prog 的使用方法是</p>
<p><code>./prog_linux64 &lt;output_file&gt;</code></p>
<p>程序会把 <code>&lt;output_file&gt;</code> 作为程序 prog 的输入，将运行结果输出到标准输出。例如</p>
<p><code>./prog_linux64 nm4.out</code></p>
<p>程序将会把 nm4.out 作为程序 prog 的输入。（windows用户请使用<code>prog_win32 nm4.out</code>）（什么你是windows 64位？放心吧可以运行win32应用程序的。）</p>
<p>当然我们有对应的linux 32位版本：<code>prog_linux32</code>。如果linux用户发现无法运行程序，请尝试执行<code>chmod +x prog_linux64</code>或<code>chmod +x prog_linux32</code>后重试。</p>
<p>其它操作系统请安装 <a href="//nodejs.org/">node.js</a> 然后使用 <code>node prog.js &lt;output_file&gt;</code> 运行checker。</p>
<p>如果你的文件不合法，程序将会输出错误信息。</p>

# 样例一


<h4>input</h4>
<pre>3 0 0
0 0 1
1 0 0
0 1 0

</pre>

<h4>output</h4>
<pre>3 3 0
1 3 92
2 1 12
3 2 29

</pre>

<h4>explanation</h4>
<p>在样例中，边的权值 $w$ 并不会影响到运行结果，在实际数据中也要注意可能存在这种情况。</p>

# 评分方法


<p>每个测试点单独评分。</p>
<p>如果你的输出运行后得到的 $n, k$ 与输入文件一致，得 1 分。</p>
<p>如果你的输出运行后得到的 $n, k, p$ 与输入文件一致，得 2 分。</p>
<p>如果你的输出运行后得到的所有整数中，除了 $p$ 以外均与输入文件一致，得 4 分。</p>
<p>在评测时，每个测试点会有一个评分参数 $s$。如果你的输出运行后得到的整数中，除了 $p$ 以外均与输入文件一致，且 $p$ 值与标准文件差值的绝对值不超过 $s$，得 7 分。</p>
<p>如果你的输出运行后得到的整数和输入文件全部一致，得 10 分。</p>
<p>以上条件如果满足多个，取最高分。</p>
<p>每个测试点的 $s$ 如下：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$s$</th><th>测试点编号</th><th>$s$</th></tr></thead><tbody><tr><td>1</td><td>$0$</td><td>6</td><td>$8$</td></tr><tr><td>2</td><td>$1000$</td><td>7</td><td>$20$</td></tr><tr><td>3</td><td>$0$</td><td>8</td><td>$1000$</td></tr><tr><td>4</td><td>$1000$</td><td>9</td><td>$1000$</td></tr><tr><td>5</td><td>$0$</td><td>10</td><td>$0$</td></tr></tbody></table></div>


# 如何测试你的输出


<p>程序 prog 还有测试的功能，可以根据你的输入输出文件以及 $s$ 值给出得分或错误信息。具体用法为</p>
<p><code>./prog_linux64 &lt;output_file&gt; &lt;input_file&gt; &lt;s&gt;</code></p>
<p>例如要测试测试点 6，可以使用</p>
<p><code>./prog_linux64 nm6.out nm6.in 8</code></p>

# 提示


<p>题目中大多数 $k$ 的值由两位数构成，若两种算法 $k$ 的第一位相同，表示这两种算法采用了相同的基本算法。</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=56">输入数据及 prog 下载</a></p>
