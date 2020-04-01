<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>灵梦有n个单词想要背，但她想通过一篇文章中的一段来记住这些单词。</p>
<p>    文章由m个单词构成，她想在文章中找出连续的一段，其中包含最多的她想要背的单词（重复的只算一个）。并且在背诵的单词量尽量多的情况下，还要使选出的文章段落尽量短，这样她就可以用尽量短的时间学习尽可能多的单词了。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行一个数n，</p>
<p>接下来n行每行是一个长度不超过10的字符串，表示一个要背的单词。</p>
<p>接着是一个数m，</p>
<p>然后是m行长度不超过10的字符串，每个表示文章中的一个单词。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件共2行。第1行为文章中最多包含的要背的单词数，第2行表示在文章中包含最多要背单词的最短的连续段的长度。</p>
<p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>hot</p>
<p>dog</p>
<p>milk</p>
<p>5</p>
<p>hot</p>
<p>dog</p>
<p>dog</p>
<p>milk</p>
<p>hot</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据 n&lt;=50，m&lt;=500；</p>
<p>对于60%的数据 n&lt;=300，m&lt;=5000；</p>
<p>对于100%的数据 n&lt;=1000，m&lt;=100000；</p>
<p> </p>
</div>
</div>