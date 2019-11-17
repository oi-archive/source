# 题目描述

<p>ns 在园子里过着快乐而充实的生活。突然有一天，从天而降 $n$ 根柱子，这 $n$ 根柱子在学堂路上排成一排，第 $i$ 根柱子高度为 $h_i$（即$h_i$ 为原始高度）米，然而，当有人站在第 $i$ 根柱子上的时候，第 $i$ 根柱子的高度会下降 $t_i$（即当有人在上面时候 $h_i-t_i$ 就是当前高度）米，离开之后又会恢复。ns 对这些柱子非常感兴趣，他可以从一根柱子跳到任意一个（包括他原本站着的柱子）原始高度不超过他所在柱子当前高度的柱子上，如果有多个柱子都满足，他会随机等概率地跳到一个满足条件的柱子上，如果没有柱子满足，他就会跳到地上。</p>
<p>ns 想知道，如果他从第 $i$ 个柱子开始，期望跳多少次可以跳到地上。</p>

# 输入格式


<p>第一行一个整数 $n$，表示柱子的数量。</p>
<p>第二行 $n$ 个空格隔开的整数 $h_i$，表示每根柱子的高度（单位：米）。</p>
<p>第三行 $n$ 个空格隔开的整数 $t_i$，表示有人站在第 $i$ 根柱子上的时候高度会下降 $t_i$ 米。</p>

# 输出格式


<p>输出一行 $n$ 个浮点数，每两个浮点数用一个空格隔开，第 $i$ 个数表示ns从第 $i$ 根柱子开始，期望跳多少步可以跳到地上，<strong>如果期望步数为无穷</strong>，输出 $0$ ；如果你输出的每个浮点数与标准答案的误差（此处误差定义为你的答案与标准答案差的绝对值）均不超过 $0.001$ ，你的答案将被视为正确。</p>
<p>注意，我们会用一个特殊的程序来判断你的答案正确与否，你输出每个浮点数的字符串长度应该不超过 $20$ 。</p>
<p><strong>定义无穷可以参与运算，无穷+X=无穷，无穷-X=无穷，无穷*X=无穷，无穷/X=无穷（X为任一实数，在除法中不为0）</strong></p>

# 样例一


<h4>输入</h4>
<pre>4
4 2 2 3
2 1 1 2

</pre>

<h4>输出</h4>
<pre>2.000 1.000 1.000 1.000

</pre>


# 样例二


<h4>输入</h4>
<pre>4
4 2 2 3
0 1 1 0

</pre>

<h4>输出</h4>
<pre>2.833 1.000 1.000 2.500

</pre>


# 样例三


<h4>输入</h4>
<pre>4
4 2 2 3
0 0 0 0

</pre>

<h4>输出</h4>
<pre>0 0 0 0

</pre>


# 数据范围


<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>
<p>输入格式见前文，输入的每个数都是整数，具体各测试点满足下列限制：</p>
<div>
<table class="table table-bordered text-center"><thead><tr><th class="text-center">编号</th>
    <th class="text-center">$n$</th>
    <th class="text-center">$h_i$</th>
    <th class="text-center">$t_i$</th>
    <th class="text-center">特殊性</th>
    </tr></thead><tbody><tr><td>$1$</td>
    <td rowspan="2" style="vertical-align:middle;">$1 \leq n \leq 10$</td>
    <td rowspan="20" style="vertical-align:middle;">$1 \leq h_i \leq 10^5$</td>
    <td rowspan="20" style="vertical-align:middle;">$0 \leq t_i \leq h_i$</td>
    <td>$t_i&gt;0$</td>
    </tr><tr><td>$2$</td>
    <td>无</td>
    </tr><tr><td>$3$</td>
    <td rowspan="6" style="vertical-align:middle;">$1 \leq n \leq 10^2$</td>
    <td>$t_i&gt;0$</td>
    </tr><tr><td>$4$</td>
    <td>$t_i=0$</td>
    </tr><tr><td>$5$</td>
    <td>$t_i=h_i$</td>
    </tr><tr><td>$6$</td>
    <td rowspan="3" style="vertical-align:middle;">无</td>
    </tr><tr><td>$7$</td>
    </tr><tr><td>$8$</td>
    </tr><tr><td>$9$</td>
    <td rowspan="4" style="vertical-align:middle;">$1 \leq n \leq 10^3$</td>
    <td>$t_i&gt;0$</td>
    </tr><tr><td>$10$</td>
    <td>$t_i=0$,$h_i$全不相同</td>
    </tr><tr><td>$11$</td>
    <td rowspan="2" style="vertical-align:middle;">无</td>
    </tr><tr><td>$12$</td>
    </tr><tr><td>$13$</td>
    <td rowspan="4" style="vertical-align:middle;">$1 \leq n \leq 10^5$</td>
    <td>$h_i$全部相同</td>
    </tr><tr><td>$14$</td>
    <td>$t_i&gt;0$</td>
    </tr><tr><td>$15$</td>
    <td rowspan="2" style="vertical-align:middle;">无</td>
    </tr><tr><td>$16$</td>
    </tr><tr><td>$17$</td>
    <td rowspan="4" style="vertical-align:middle;">$1 \leq n \leq 10^6$</td>
    <td>$t_i=h_i$</td>
    </tr><tr><td>$18$</td>
    <td>$t_i&gt;0$</td>
    </tr><tr><td>$19$</td>
    <td rowspan="2" style="vertical-align:middle;">无</td>
    </tr><tr><td>$20$</td>
    </tr></tbody></table></div>


# 下载


<p><a href="/download.php?type=problem&amp;id=161">样例下载</a></p>
