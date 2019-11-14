<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小明喜欢查字典。</p>
<p>一天，他从电脑上下载了一种字典。这种字典的查询方式十分奇怪：首先将字典读入内存，保存在本地的字典消失；在内存中给每个词分布一个内存地址，然后按地址查询。然而这个字典的内存又很奇怪：每隔一定时间自动变化。小明研究了很久才知道了变化规律。现在，他给你这个变化规律，让你输出一个内存区间内的单词个数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行 n 表示有n个单词</p>
<p>接下来n行 有 Mi Xi 分别表示单词的内存地址和这个单词。</p>
<p>接下来 m 表示变化规律的种数</p>
<p>接下来m行 三个值 S1 S2 S3 表示 S1到S2的内存范围内每个单词后移S3位。（不会与之前单词有冲突，如果S3为负则前移,S2可能小于S1）</p>
<p>接下来 k 表示小明要问的内存区间个数</p>
<p>接下来k行 两个值 A1 A2 表示要查询的区间【A1,A2】之间的单词个数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>k行 每行一个值，表示之间的单词个数；</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>12343 string</p>
<p>7777 callofduty</p>
<p>1</p>
<p>7666 333333 1</p>
<p>2</p>
<p>1000 99999</p>
<p>7776 7778</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>0&lt;=n,m,k&lt;=10000</p>
<p>内存地址不超过10^6;单词字符数不超过50；</p>
<p>其实就是线段树，但数据奇弱。</p>
</div>
</div>