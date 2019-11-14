<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小G是一个出色的诗人，经常作诗自娱自乐。但是，他一直被一件事情所困扰，那就是诗的排版问题。</p><p>一首诗包含了若干个句子，对于一些连续的短句，可以将它们用空格隔开并放在一行中，注意一行中可以放的句子数目是没有限制的。小G给每首诗定义了一个行标准长度（行的长度为一行中符号的总个数），他希望排版后每行的长度都和行标准长度相差不远。显然排版时，不应改变原有的句子顺序，并且小G不允许把一个句子分在两行或者更多的行内。在满足上面两个条件的情况下，小G对于排版中的每行定义了一个不协调度, 为这行的实际长度与行标准长度差值绝对值的P次方，而一个排版的不协调度为所有行不协调度的总和。</p><p>小G最近又作了几首诗，现在请你对这首诗进行排版，使得排版后的诗尽量协调（即不协调度尽量小），并把排版的结果告诉他。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>本题中包含多组测试数据。</p><p>输入文件中的第一行为一个整数T，表示诗的数量。</p><p>接下来为T首诗，这里一首诗即为一组测试数据。每组测试数据中的第一行为三个由空格分隔的正整数N，L，P，其中：N表示这首诗句子的数目，L表示这首诗的行标准长度，P的含义见问题描述。</p><p>从第二行开始，每行为一个句子，句子由英文字母、数字、标点符号等符号组成（ASCII码33～127，但不包含'-'）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每组测试数据，若最小的不协调度不超过10^18，则第一行为一个数，表示不协调度。接下来若干行，表示你排版之后的诗。注意：在同一行的相邻两个句子之间需要用一个空格分开。</p><p>如果有多个可行解，它们的不协调度都是最小值，则输出任意一个解均可。若最小的不协调度超过10^18，则输出&amp;ldquo;Too hard to arrange&amp;rdquo;（不含引号）。每组测试数据结束后输出&amp;ldquo;--------------------&amp;rdquo;（不含引号），共20个&amp;ldquo;-&amp;rdquo;，&amp;ldquo;-&amp;rdquo;的ASCII码为45，请勿输出多余的空行或者空格。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p><p>4 9 3</p><p>brysj,</p><p>hhrhl.</p><p>yqqlm,</p><p>gsycl.</p><p>4 9 2</p><p>brysj,</p><p>hhrhl.</p><p>yqqlm,</p><p>gsycl.</p><p>1 1005 6</p><p>poet</p><p>1 1004 6</p><p>poet</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>108</p><p>brysj,</p><p>hhrhl.</p><p>yqqlm,</p><p>gsycl.</p><p>--------------------</p><p>32</p><p>brysj, hhrhl.</p><p>yqqlm, gsycl.</p><p>--------------------</p><p>Too hard to arrange</p><p>--------------------</p><p>1000000000000000000</p><p>poet</p><p>--------------------</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】</p><p>前两组输入数据中每行的实际长度均为6，后两组输入数据每行的实际长度均为4。一个排版方案中每行相邻两个句子之间的空格也算在这行的长度中（可参见样例中第二组数据）。每行末尾没有空格。</p><p> </p><p>总共10个测试点，数据范围满足：</p><table border="1" cellpadding="0" cellspacing="0"><tbody><tr><td width="95"><p>测试点</p></td><td width="95"><p>T</p></td><td width="95"><p>N</p></td><td width="95"><p>L</p></td><td width="95"><p>P</p></td></tr><tr><td width="95"><p>1</p></td><td width="95"><p>&lt;=10</p></td><td width="95"><p>&lt;=18</p></td><td width="95"><p>&lt;=100</p></td><td width="95"><p>&lt;=5</p></td></tr><tr><td width="95"><p>2</p></td><td width="95"><p>&lt;=10</p></td><td width="95"><p>&lt;=2000</p></td><td width="95"><p>&lt;=60000</p></td><td width="95"><p>&lt;=10</p></td></tr><tr><td width="95"><p>3</p></td><td width="95"><p>&lt;=10</p></td><td width="95"><p>&lt;=2000</p></td><td width="95"><p>&lt;=60000</p></td><td width="95"><p>&lt;=10</p></td></tr><tr><td width="95"><p>4</p></td><td width="95"><p>&lt;=5</p></td><td width="95"><p>&lt;=100000</p></td><td width="95"><p>&lt;=200</p></td><td width="95"><p>&lt;=10</p></td></tr><tr><td width="95"><p>5</p></td><td width="95"><p>&lt;=5</p></td><td width="95"><p>&lt;=100000</p></td><td width="95"><p>&lt;=200</p></td><td width="95"><p>&lt;=10</p></td></tr><tr><td width="95"><p>6</p></td><td width="95"><p>&lt;=5</p></td><td width="95"><p>&lt;=100000</p></td><td width="95"><p>&lt;=3000000</p></td><td width="95"><p>2</p></td></tr><tr><td width="95"><p>7</p></td><td width="95"><p>&lt;=5</p></td><td width="95"><p>&lt;=100000</p></td><td width="95"><p>&lt;=3000000</p></td><td width="95"><p>2</p></td></tr><tr><td width="95"><p>8</p></td><td width="95"><p>&lt;=5</p></td><td width="95"><p>&lt;=100000</p></td><td width="95"><p>&lt;=3000000</p></td><td width="95"><p>&lt;=10</p></td></tr><tr><td width="95"><p>9</p></td><td width="95"><p>&lt;=5</p></td><td width="95"><p>&lt;=100000</p></td><td width="95"><p>&lt;=3000000</p></td><td width="95"><p>&lt;=10</p></td></tr><tr><td width="95"><p>10</p></td><td width="95"><p>&lt;=5</p></td><td width="95"><p>&lt;=100000</p></td><td width="95"><p>&lt;=3000000</p></td><td width="95"><p>&lt;=10</p></td></tr></tbody></table><p>所有测试点中均满足句子长度不超过30。</p>
</div>
</div>