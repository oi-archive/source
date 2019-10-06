# 题目描述

<p>时针指向午夜十二点，约定的日子——2月28日终于到来了。随着一声枪响，伏特跳蚤国王率领着他的跳蚤大军们包围了 picks 博士所在的实验室。</p>
<p>当然，picks 博士不会坐以待毙，他早就率领着他的猴子们在实验室外修筑了许多的坚固防御工事。</p>
<p>经过跳蚤侦察兵的勘察，跳蚤国王发现 picks 博士的防御工事有着 $n$ 处薄弱点，于是他把他的跳蚤大军分成了 $n$ 支小队，并打算让它们分别进攻每一个薄弱点。但是因为战场混乱，这 $n$ 支小队的位置被打乱了，重新整队之后，跳蚤国王发现第 $i$ 个位置的小队编号为 $A_i$（<strong>显然 $A$ 是一个排列</strong>）。</p>
<p>经过计算，跳蚤国王发现，让第 $i$ 个位置的小队编号为 $B_i$ 时，他的军队可以发挥出最大的战斗力（<strong>保证 $B$ 也是一个排列</strong>）。</p>
<p>跳蚤国王可以发出指令来改变小队们的排列顺序，每一次，他都会报出一个整数 $i(1 \leq i &lt; n)$。<strong>如果排在第 $i$ 个位置的小队编号大于第 $i+1$ 个位置的小队，那么这两支小队会交换顺序，否则这一个命令将会被忽略</strong>。</p>
<p>现在跳蚤国王希望他的军队能够发挥出最强大的战斗力，于是他想要知道是否存在一种指令序列，使得小队们可以按照排列 $B$ 的方式排列。</p>
<p>但是因为小队数目实在是太多，跳蚤国王一时间也没有看出答案。于是他派跳蚤绑架来了你——这附近最著名的民间科学家来帮他计算这个问题的答案。</p>

# 输入格式


<p>输入数据第一行包含一个正整数 $n$。</p>
<p>接下来两行每行 $n$ 个正整数，分别描述排列 $A$ 和排列 $B$。</p>

# 输出格式


<p>对于每组数据，如果存在这样的指令序列，输出“YES”，否则输出“NO”(<strong>引号不输出，请注意大小写</strong>)。</p>

# 样例一


<h4>input</h4>
<pre>3
2 3 1
2 1 3
</pre>

<h4>output</h4>
<pre>YES
</pre>

<h4>explanation</h4>
<p>只要报出2，也就是交换第2个位置和第3个位置的小队即可。</p>

# 样例二


<h4>input</h4>
<pre>3
2 1 3
3 1 2
</pre>

<h4>output</h4>
<pre>NO
</pre>

<h4>explanation</h4>
<p>注意只有相邻的满足前一个数大于后一个数的情况下才可以交换。</p>

# 样例三


<h4>input</h4>
<pre>5
4 1 2 5 3
1 2 4 3 5
</pre>

<h4>output</h4>
<pre>YES
</pre>

<h4>explanation</h4>
<p>步骤如下(每次交换的两个数加粗表示)：</p>
<p><strong>4 1</strong> 2 5 3</p>
<p>1 <strong>4 2</strong> 5 3</p>
<p>1 2 4 <strong>5 3</strong></p>
<p>1 2 4 3 5</p>

# 样例四


<h4>input</h4>
<pre>5
1 5 3 4 2
1 2 4 3 5
</pre>

<h4>output</h4>
<pre>NO
</pre>


# 样例五


<h4>input</h4>
<pre>8
8 2 7 4 5 3 6 1 
2 8 5 7 4 3 6 1 
</pre>

<h4>output</h4>
<pre>NO
</pre>


# 样例六


<p>见样例数据下载。这组数据符合子任务 2 的限制与约定。</p>

# 样例七


<p>见样例数据下载。这组数据符合子任务 3 的限制与约定。</p>

# 限制与约定


<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th><th>分值</th><th colspan="2">限制与约定</th></tr></thead><tbody><tr><td>1</td><td>24</td><td colspan="2">$n \le 8$</td></tr><tr><td>2</td><td>32</td><td colspan="2">$n \le 1000$</td></tr><tr><td>3</td><td>44</td><td colspan="2">$n \le 100000$</td></tr></tbody></table><p>对于所有数据，$1 \le n \le 100000$，保证输入的$A$和$B$均为一个排列。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=180">样例数据下载</a></p>
