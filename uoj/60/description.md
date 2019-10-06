# 题目描述

<p>大力水手最近和他的女朋友奥利弗分手了，他感到人生非常灰暗，于是上山来找禅师解惑。</p>
<p>大力水手问禅师：“大师，奥利弗以前经常说我是个笨蛋，让我觉得很生气。大概是因为我真的太笨了她才这么说吧。请问，怎样才能提高智商？”</p>
<p>禅师浅笑，答：“方法很简单，不过若想我教你，你先看看这张试卷。”</p>
<p>大力水手拿到试卷，共有 $n$ 道选择题，编号为 $1$ 到 $n$。第 $i$ 道题形如：（$h_i$ 为 “<samp>A</samp>” 或 “<samp>B</samp>” 或 “<samp>C</samp>” 或 “<samp>D</samp>”，$a_i, b_i, c_i, d_i$都是整数）</p>
<ul class="list-group"><li class="list-group-item">
        <h5 class="list-group-item-heading">
        $i$. 编号小于 $i$ 的题目中你一共选了几个 $h_i$？
        </h5>
        <ul class="list-inline"><li>A. $a_i$ 个</li>
              <li>B. $b_i$ 个</li>
              <li>C. $c_i$ 个</li>
            <li>D. $d_i$ 个</li>
        </ul></li>
</ul><p>大力水手问禅师：“是要我做这张试卷吗？”。禅师摆摆手，答：“多想想。”</p>
<p>大力水手注意到一张试卷可能有很多种正确答案（两种正确答案被认为是不同的当且仅当存在一道题这两份正确答案选的选项不同），于是问禅师：“是要我求这张试卷有多少种正确答案吗？”。禅师摆摆手，答：“多想想。”</p>
<p>大力水手想到，一张试卷要是正确答案有很多种，就很容易蒙对，于是问禅师：“是要我求出所有 $n$ 道选择题的试卷中，正确答案最多的试卷吗？”。禅师点点头，转身离去。</p>

# 例子


<p></p><ul class="list-group"><li class="list-group-item">
        <h5 class="list-group-item-heading">
        1. 编号小于 $1$ 的题目中你一共选了几个 <samp>B</samp>？
        </h5>
        <ul class="list-inline"><li>A. $0$ 个</li>
          <li>B. $7$ 个</li>
          <li>C. $1$ 个</li>
          <li>D. $4$ 个</li>
        </ul></li>
    <li class="list-group-item">
        <h5 class="list-group-item-heading">
        2. 编号小于 $2$ 的题目中你一共选了几个 <samp>A</samp>？
        </h5>
        <ul class="list-inline"><li>A. $3$ 个</li>
            <li>B. $2$ 个</li>
            <li>C. $1$ 个</li>
            <li>D. $4$ 个</li>
        </ul></li>
    <li class="list-group-item">
        <h5 class="list-group-item-heading">
        3. 编号小于 $3$ 的题目中你一共选了几个 <samp>D</samp>？
        </h5>
        <ul class="list-inline"><li>A. $0$ 个</li>
            <li>B. $2$ 个</li>
            <li>C. $1$ 个</li>
            <li>D. $0$ 个</li>
        </ul></li>
</ul>
共有两种正确答案。一种可能的正确答案为：第一题选 <samp>A</samp> 第二题选 <samp>C</samp> 第三题选 <samp>D</samp>。

# 输入格式


<p>共一行，包含一个正整数 $n$，表示试卷中选择题的个数。</p>

# 输出格式


<p>第一行一个整数，表示正确答案最多的试卷的正确答案数。你只用输出答案对 $998244353$（$7 \times 17 \times 2^{23} + 1$，一个质数）取模后的值。</p>
<p>接下来 $n$ 行输出一种正确答案最多的试卷。如果有多种你可以输出任意一种。</p>
<p>这 $n$ 行中的第 $i$ 行包含 $h_i, a_i, b_i, c_i, d_i$，表示第 $i$ 道选择题。$h_i$ 为 “<samp>A</samp>” 或 “<samp>B</samp>” 或 “<samp>C</samp>” 或 “<samp>D</samp>”，$a_i, b_i, c_i, d_i$ 都是整数且 $0 \leq a_i, b_i, c_i, d_i \leq 10^9$。</p>

# 样例一


<h4>input</h4>
<pre>1

</pre>

<h4>output</h4>
<pre>4
A 0 0 0 0

</pre>

<h4>explanation</h4>
<p>$n = 1$ 时正确答案最多的试卷的正确答案数为 $4$，四种正确答案分别为：第一题选 <samp>A</samp>、第一题选 <samp>B</samp>、第一题选 <samp>C</samp>、第一题选 <samp>D</samp>。</p>

# 样例二


<p>$n = 2$ 时正确答案最多的试卷的正确答案数为 $12$，但是你以为我会告诉你这张试卷长什么样吗？</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
</tr></thead><tbody><tr><td>1</td><td>$n = 2$</td></tr><tr><td>2</td><td>$n = 3$</td></tr><tr><td>3</td><td>$n = 4$</td></tr><tr><td>4</td><td>$n = 5$</td></tr><tr><td>5</td><td>$n = 6$</td></tr><tr><td>6</td><td rowspan="2">$n \leq 1000$</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">$n \leq 10^5$</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 后记


<p>大力水手对禅师说：“我明白了！碰到一道问题多想想，就能锻炼大脑并体会到无穷的乐趣。这样日复一日，智商就能渐渐提高了！”</p>
<p>禅师摆摆手，嘿嘿一笑：“你想得太多了。智商等于心智年龄除以生理年龄，所以我刚才趁你思考时已经去公安局把你的出生日期改到昨天晚上了。现在你应该是世界上智商最高的人，请叫我雷锋。”</p>
<p>从此高智商的大力水手和奥利弗过上了幸福的生活。</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=60">样例数据下载</a></p>
