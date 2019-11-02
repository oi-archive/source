<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Magic Land 上的人们总是提起那个传说：他们的祖先 John 在那个东方岛屿<br>帮助 Koishi 与其姐姐Satori最终战平。而后，Koishi恢复了读心的能力„„ <br> <br>如今，在John 已经成为传说的时代，再次造访那座岛屿的人们却发现 Koishi<br>遇到了新麻烦。 <br> 这次她遇到了 Flandre Scarlet——她拥有可以使用禁忌魔法而不会受到伤害<br>的能力。 <br> 为了说明什么是禁忌魔法及其伤害，引入以下概念： <br>1．字母集 A上的每个非空字符串对应了一个魔法。 <br>其中 A是包含了前alphabet个小写字母的集合。 <br>2．有一个集合 T，包含了 N个字母集 A上的字符串 <br>T中的每一串称为一个禁忌串（Taboo string） <br>3．一个魔法，或等价地，其对应的串 s因为包含禁忌而对使用者造成的伤<br>害按以下方式确定： <br> 把s分割成若干段，考虑其中是禁忌串的段的数目，不同的分割可<br>能会有不同的数目，其最大值就是这个伤害。</p>
<p><br>由于拥有了读心的能力，Koishi总是随机地使用 Flandre Scarlet的魔法，可<br>以确定的是，她的魔法正好对应字母集 A上所有长度为 len的串。 <br>但是，Flandre Scarlet所使用的一些魔法是带有禁忌的，由于其自身特性，<br>她可以使用禁忌魔法而不受到伤害，而 Koishi 就不同了。可怜的 Koishi每一次<br>使用对方的魔法都面临着受到禁忌伤害的威胁。 <br> <br> 你现在需要计算的是如果 Koishi 使用对方的每一个魔法的概率是均等的，那<br>么每一次随机使用魔法所受到的禁忌伤害的期望值是多少。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含三个正整数N、len、alphabet。 <br>接下来 N行，每行包含一个串 Ti，表示禁忌串。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个非负实数，表示所受到禁忌伤害的期望值。 保留10位小数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 4 2 <br>aa <br>abb</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0.7500000000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的数据中len ≤ 10，alphabet ≤ 2； <br>70%的数据：len ≤50； <br>100%的数据中N ≤ 5，len ≤109<br>，1 ≤ alphabet ≤ 26。 <br>在所有数据中，有不少于 40%的数据中：N = 1。 <br>数据保证每个串Ti的长度不超过15，并且不是空串。 <br>数据保证每个 Ti均仅含有前alphabet个小写字母。 <br>数据保证集合 T中没有相同的元素，即对任意不同的i 和 j，有 Ti≠Tj。</p>
</div>
</div>