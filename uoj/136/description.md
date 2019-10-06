# 题目描述

<p>红包是一个萌萌的男孩子。</p>
<p>红包由于 NOI 惨挂，直到前不久依然无心写作业。如今快开学了，他决定好好完成作业。</p>
<p>对于可以交电子稿的作文，红包有特殊的完成技巧，大致流程是依次选中一段内容→按下 <kbd><kbd>Ctrl</kbd>+<kbd>C</kbd></kbd>→按下 <kbd><kbd>Ctrl</kbd>+<kbd>V</kbd></kbd> 。</p>
<p>由于红包的键盘过于奇特，只有 <kbd>↑</kbd>，<kbd>↓</kbd>，<kbd>←</kbd>，<kbd>→</kbd>，<kbd>Fn</kbd> 这 $5$ 个按键能够移动光标，导致每次选中一段内容总要费上一番功夫。</p>
<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>按键</th><th>功能</th></tr></thead><tbody><tr><td><kbd>↑</kbd></td><td>将光标向上移动一格</td></tr><tr><td><kbd>↓</kbd></td><td>将光标向下移动一格</td></tr><tr><td><kbd>←</kbd></td><td>将光标向左移动一格</td></tr><tr><td><kbd>→</kbd></td><td>将光标向右移动一格</td></tr><tr><td><kbd>Fn</kbd></td><td>依次按下最近被物理按下的两个 <kbd>↑</kbd>，<kbd>↓</kbd>，<kbd>←</kbd>，<kbd>→</kbd> 键
                        <br/>例子：若依次按下 <kbd>↓</kbd>，<kbd>Fn</kbd>，<kbd>←</kbd>，<kbd>Fn</kbd>，则第一次按下 <kbd>Fn</kbd> 后等价于按下 <kbd>↓</kbd>，第二次按下 <kbd>Fn</kbd> 后等价于依次按下 <kbd>↓</kbd>，<kbd>←</kbd> 。</td></tr></tbody></table></div>

<p>现在红包想要在按键次数尽可能少的情况下移动光标到第 $n$ 行第 $m$ 列。为了简化问题我们默认光标起始位置为第一行第一列。</p>

# 输入格式


<p>第一行一个正整数 $T$，表示数据组数。</p>
<p>接下来 $T$ 行，每行两个正整数 $n, m$，如题所述，表示光标的目标位置。</p>
<p>每组数据之间相互独立。</p>

# 输出格式


<p>对于每一个询问，输出一行一个整数 $\mathrm{ans}$，表示最小按键次数。</p>

# 样例一


<h4>input</h4>
<pre>2
1 5
3 3
</pre>

<h4>output</h4>
<pre>3
3
</pre>

<h4>explanation</h4>
<p>对于第一组输入，我们要将光标移至第一行第五列，依次按 <kbd>→</kbd>，<kbd>→</kbd>，<kbd>Fn</kbd>，即可。</p>
<p>对于第二组输入，依次按下 <kbd>→</kbd>，<kbd>↓</kbd>，<kbd>Fn</kbd>，即可。</p>

# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<p>对于所有数据，$T \le 100000$。</p>
<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n, m$ 的规模</th></tr></thead><tbody><tr><td>1</td><td>$n \leq 4$，$m \leq 4$</td></tr><tr><td>2</td><td rowspan="4">$n \leq 1000$，$m \leq 1000$</td></tr><tr><td>3</td></tr><tr><td>4</td></tr><tr><td>5</td></tr><tr><td>6</td><td>$n=1$，$m\le10^9$</td></tr><tr><td>7</td><td>$n\le10^9$，$m=1$</td></tr><tr><td>8</td><td rowspan="3">$n \leq 10^9$，$m \leq 10^9$</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=136">样例数据下载</a></p>
