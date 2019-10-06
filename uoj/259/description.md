# 题目描述

<p>给定无向图 $G=(V,E)$，$\lvert V\rvert=n$，$\lvert E\rvert=m$，$V$ 中的点编号为 $1,2,...,n$。求有多少个子集 $V&#39;\subseteq V$ 满足 $\lvert V&#39;\rvert=k$ 且 $\forall (u,v)\in E,u\not\in V&#39;\lor v\not\in V&#39;$。由于答案可能很大，只需输出答案对 $p$ 取模的结果。</p>

# 输入格式


<p>本题为提交答案题。所有输入数据 subset1.in ~ subset10.in 见输入数据下载。</p>
<p>输入第 $1$ 行包含 $4$ 个用空格分隔的正整数 $n, m, k, p$，分别表示 $\lvert V \rvert, \lvert E \rvert$，要求的 $\lvert V&#39; \rvert$ 的大小以及模数。</p>
<p>随后 $m$ 行，每行包含 $2$ 个用空格分隔的正整数 $a_i$，$b_i$，描述 $G$ 中的边 $(a_i,b_i)\in E$。</p>

# 输出格式


<p>针对给定的 $10$ 个输入文件 subset1.in ~ subset10.in，你需要分别提交你的输出文件 subset1.out ~ subset10.out。</p>
<p>输出文件共 $1$ 行，包含 $1$ 个整数，表示子集 $V&#39;$ 的个数对 $p$ 取模的值。</p>

# 样例一


<h4>input</h4>
<pre>6 9 2 10000
1 2
1 3
1 4
4 3
2 5
5 6
3 5
3 6
6 4

</pre>

<h4>output</h4>
<pre>6

</pre>

<h4>explanation</h4>
<p>共有 $6$ 个这样的子集 $V&#39;$，分别是：$\{1,5\}$，$\{1,6\}$，$\{2,3\}$，$\{2,4\}$，$\{2,6\}$，$\{4,5\}$。</p>

# 样例二


<h4>input</h4>
<pre>17 16 5 10000
1 2
1 3
2 4
2 5
3 6
3 7
5 8
5 9
7 10
7 11
8 12
8 13
10 14
10 15
12 16
15 17

</pre>

<h4>output</h4>
<pre>1528

</pre>


# 评分方式


<p>本题共有 $10$ 个测试点，每个测试点都有一定分值。对于每个测试点，如果选手的输出与标准答案一致，则得到该测试点的分值，否则不得分。每个测试点的分值由下表给出：</p>
<table border="1" align="center" width="50%" class="table table-bordered table-condensed"><tbody><tr><th width="30%" style="text-align:center;">测试点编号</th>
        <th width="20%" style="text-align:center;">分值</th>
        <th width="30%" style="text-align:center;">测试点编号</th>
        <th width="20%" style="text-align:center;">分值</th>
    </tr><tr><td style="text-align:center;">1</td>
        <td style="text-align:center;">$5$</td>
        <td style="text-align:center;">6</td>
        <td style="text-align:center;">$11$</td>
    </tr><tr><td style="text-align:center;">2</td>
        <td style="text-align:center;">$6$</td>
        <td style="text-align:center;">7</td>
        <td style="text-align:center;">$9$</td>
    </tr><tr><td style="text-align:center;">3</td>
        <td style="text-align:center;">$14$</td>
        <td style="text-align:center;">8</td>
        <td style="text-align:center;">$13$</td>
    </tr><tr><td style="text-align:center;">4</td>
        <td style="text-align:center;">$8$</td>
        <td style="text-align:center;">9</td>
        <td style="text-align:center;">$7$</td>
    </tr><tr><td style="text-align:center;">5</td>
        <td style="text-align:center;">$12$</td>
        <td style="text-align:center;">10</td>
        <td style="text-align:center;">$15$</td>
    </tr></tbody></table>
# 如何测试你的输出


<p>在终端中先切换到该试题的目录下：（windows用户请使用cmd）</p>
<p><code>cd subset</code></p>
<p>我们提供 checker 这个工具来测试你的输出文件是否正确。使用这个工具的方法是，在终端中运行</p>
<p><code>./checker &lt;case_no&gt;</code></p>
<p>其中 <code>case_no</code> 是测试数据的编号。例如</p>
<p><code>./checker 3</code></p>
<p>将测试 subset3.out 是否正确。（windows用户请使用 <code>checker 3</code>）</p>
<p>在你调用这个程序后，checker 将根据你给出的输出文件给出测试的结果。</p>

# 来源


<p>WrongAnswer</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=259">输入数据及checker下载</a></p>
