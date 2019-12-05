# 题目描述

<p>有 $n$ 个同学（编号为 $1$ 到 $n$ ）正在玩一个信息传递的游戏。在游戏里每人都有一个固定的信息传递对象，其中，编号为 $i$ 的同学的信息传递对象是编号为 $T_i$ 的同学。</p>
<p>游戏开始时，每人都只知道自己的生日。之后每一轮中，所有人会同时将自己当前所知的生日信息告诉各自的信息传递对象（注意：可能有人可以从若干人那里获取信息， 但是每人只会把信息告诉一个人，即自己的信息传递对象）。当有人从别人口中得知自 己的生日时，游戏结束。请问该游戏一共可以进行几轮？</p>

# 输入格式


<p>输入共2行。
第1行包含1个正整数 $n$ ，表示 $n$ 个人。</p>
<p>第2行包含 $n$ 个用空格隔开的正整数 $T_1,T_2,\cdots\cdots,T_n$ ，其中第 $i$ 个整数 $T_i$ 表示编号为 $i$ 的同学的信息传递对象是编号为 $T_i$ 的同学， $T_i \leq n$ 且 $T_i \neq i$ 。</p>
<p>数据保证游戏一定会结束。</p>

# 输出格式


<p>输出共1行，包含1个整数，表示游戏一共可以进行多少轮。</p>

# 样例一


<h4>input</h4>
<pre>5
2 4 2 3 1

</pre>

<h4>output</h4>
<pre>3

</pre>



# 数据规模与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$ 的规模</th></tr></thead><tbody><tr><td>1</td><td rowspan="3">$n \leq 200$</td></tr><tr><td>2</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="3">$n \leq 2500$</td></tr><tr><td>5</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="4">$n \leq 200000$</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$128\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=146">样例数据下载</a></p>
