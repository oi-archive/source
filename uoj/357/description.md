# 题目描述

<p>小S和小M去看花火大会。</p>
<p>一共有 $n$ 个人按顺序排成一排，每个人手上有一个仅能被点燃一次的烟花。最开始时第 $K$ 个人手上的烟花是点燃的。</p>
<p>烟花最多能燃烧 $T$ 时间。每当两个人的位置重叠且其中一个人手上的烟花是点燃的时，另一个人手上的烟花可以被点燃。</p>
<p>现在小M想要知道，每个人至少需要以多快的速度 $s$ 奔跑，才能使得每个人手中的烟花都能被点燃。</p>
<p>可怜的小M当然不会啦，所以她向你求助。</p>

# 输入格式


<p>第一行三个整数 $n,K,T$。意义如题面所示。</p>
<p>接下来 $n$ 行，每行一个整数 $x_i$，表示第 $i$ 个人的位置。</p>

# 输出格式


<p>一行一个整数，表示最小的整数 $s$ 使得每个人手中的烟花都能被点燃。</p>

# 样例一


<h4>input</h4>
<pre>3 2 50
0
200
300

</pre>

<h4>output</h4>
<pre>2

</pre>


# 样例二


<h4>input</h4>
<pre>3 2 10
0
200
300

</pre>

<h4>output</h4>
<pre>8

</pre>



# 样例三


<h4>input</h4>
<pre>20 6 1
0
2
13
27
35
46
63
74
80
88
100
101
109
110
119
138
139
154
172
192

</pre>

<h4>output</h4>
<pre>6

</pre>



# 限制与约定


<p>对于所有数据，</p>
<p>$1\le K\le n\le 10^5,1\le T\le 10^9 ,0\le x_i\le 10^9 ,x_1=0,x_i \le x_j(1\le i\le j \le n)$。</p>
<div class="table-responsive">
 <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
    <th>分值</th>
    <th>$n$</th>
   </tr></thead><tbody><tr><td>1</td>
    <td>30</td>
    <td>$\le 20$</td>
   </tr><tr><td>2</td>
    <td>20</td>
    <td>$\le 1000$</td>
   </tr><tr><td>3</td>
    <td>50</td>
    <td>$\le 10^5$</td>
   </tr></tbody></table></div>

<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=357">样例数据下载</a></p>
