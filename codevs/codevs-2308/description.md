<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Sheng bill不仅有惊人的心算能力，还可以轻松地完成各种统计。在昨天的比赛中，你凭借优秀的程序与他打成了平局，这导致Sheng bill极度的不满。于是他再次挑战你。这次你可不能输！</p>
<p>这次，比赛规则是这样的：</p>
<p>给N个长度相同的字符串（由小写英文字母和′?′组成），S1,S2,...,SN，求与这N个串中的刚好K个串匹配的字符串T的个数（答案模1000003）。</p>
<p>若字符串Sx（1 ≤ x ≤ N）和T匹配，满足以下条件：</p>
<p>1. Sx.length = T.length。</p>
<p>2. 对于任意的1 ≤ i ≤ Sx.length，满足Sx[i]=′?′或者Sx[i]= T[i]。</p>
<p>其中T只包含小写英文字母。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>本题包含多组数据。</p>
<p>第一行：一个整数T，表示数据的个数。</p>
<p>对于每组数据：</p>
<p>第一行：两个整数，N和K（含义如题目表述）。</p>
<p>接下来N行：每行一个字符串。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每组数据，输出方案数目（共T行）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>2 1</p>
<p>a?</p>
<p>?b</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>50</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，T ≤ 5，N ≤ 5，字符串长度≤ 20；</p>
<p>对于70%的数据，T ≤ 5，N ≤ 13，字符串长度≤ 30；</p>
<p>对于100%的数据，T ≤ 5，N ≤ 15，字符串长度≤ 50。</p>
</div>
</div>