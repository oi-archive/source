# 题目描述

<p>由于电信技术的发展，谣言的传播变得十分迅速。</p>
<p>现在有 $n$ 个人，依次编号为 $1, \dots, n$。</p>
<p>每个人都有一个最好的朋友，第 $i$ 个人的最好的朋友为 $a_i$（$a_i \neq i$）。</p>
<p>每个人都有一个真理捍卫者，第 $i$ 个人的真理捍卫者为 $b_i$（$b_i \neq i$）。由于奇妙的原因，一个人只会是恰好一个人的真理捍卫者，即 $b_1, \dots, b_n$ 是一个 $1$ 到 $n$ 的排列。</p>
<p>对于第 $i$ 个人我们定义他的影响系数，考虑下面这个假想的谣言传播：</p>
<ol><li>一开始，第 $i$ 个人从神奇的海螺那里听说了一则谣言。</li>
<li>每次，如果第 $j$ 个人首次听说了这则谣言，那么：<ul><li>如果 $j$ 是 $i$ 的真理捍卫者，即 $j = b_i$， 那么 $j$ 会不做任何事。</li>
<li>否则， $j$ 会打电话把这则谣言告诉他最要好的朋友 $a_j$。</li>
</ul></li>
<li>如果没有人首次听说了这则谣言那么传播过程结束。</li>
<li>最终，听说了谣言的人数为第 $i$ 个人的影响系数。</li>
</ol><p>一万万年后，一位考古学家得到了 $a_1, \dots, a_n$，然而 $b_1, \dots, b_n$ 的取值在漫漫的历史长河中消失了。现在这位考古学家想求出所有人的影响系数之和的最小值与最大值，并给出相应的一组解。</p>

# 输入格式


<p>第一行一个正整数 $n$。保证 $n \geq 2$。</p>
<p>第二行包含 $n$ 个整数 $a_1, \dots, a_n$。保证 $1 \leq a_i \leq n$ 且 $a_i \neq i$。</p>

# 输出格式


<p>第一行一个整数，表示影响系数之和的最小值。</p>
<p>接下来一行 $n$ 个整数 $b_1, \dots, b_n$ 表示一组满足影响系数之和最小的解。（如果有多组输出任意一组均可）</p>
<p>接下来一行一个整数，表示影响系数之和的最大值。</p>
<p>接下来一行 $n$ 个整数 $b_1, \dots, b_n$ 表示一组满足影响系数之和最大的解。（如果有多组输出任意一组均可）</p>

# 样例一


<h4>input</h4>
<pre>5
4 1 5 3 4

</pre>

<h4>output</h4>
<pre>11
4 1 5 3 2
18
2 5 4 1 3

</pre>


# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<p>对于每个测试点，答对第一问可获得 50% 的分数，答对第二问可获得 50% 的分数。</p>
<p><strong>请注意你输出的两组解必须合法否则该测试点会被直接判0分。</strong>（如果你输出的系数之和与解不相对应，只会导致该小问 $0$ 分，该测试点不会被直接判 $0$ 分）</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$的规模</th>
</tr></thead><tbody><tr><td>1</td><td>$n \leq 8$</td></tr><tr><td>2</td><td rowspan="3">$n \leq 50$</td></tr><tr><td>3</td></tr><tr><td>4</td></tr><tr><td>5</td><td rowspan="3">$n \leq 2000$</td></tr><tr><td>6</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">$n \leq 100000$</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=115">样例数据下载</a></p>
