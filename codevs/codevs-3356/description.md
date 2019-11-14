<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>最后一题，不会考大家太难的问题啦，就考字符串的最长公共前缀吧。</p><p>给出一个长度为L的字符串S，给出若干个询问，以(x,y)的形式给出。对于每个询问，你需要回答，S[x..L]和S[y..L]的最长公共前缀是什么？</p><p>当然，小P不会让题目不会就这么简单，你还需要同时应对修改操作。</p><p>有两种修改操作：</p><p>1、修改操作以(x,ch)的形式给出。即把第x个字符修改成ch。</p><p>2、翻转操作以(x,y)的形式给出。即把第x个字符到第y个字符的子串翻转一下。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数L。</p><p>第二行给出一个长度为L的初始字符串。</p><p>第三行给出一个整数Q，表示操作的总数。</p><p>接下来的Q行，给出两种操作，&amp;ldquo;Q x y&amp;rdquo;表示询问操作，&amp;ldquo;C x ch&amp;rdquo;表示修改操作，&amp;ldquo;T x y&amp;rdquo;表示翻转操作。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每一个询问操作，输出他们的最长公共前缀。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p><p> abcab</p><p> 3</p><p> Q 1 4</p><p> C 5 a</p><p> Q 1 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p><p> 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1                                   L&lt;=10</p><p>&amp;middot;2                              L&lt;=100</p><p>&amp;middot;3-4                           L&lt;=50000</p><p>&amp;middot;5-10                   L&lt;=100000</p><p>总操作数Q与L正相关，不超过L的规模，其中，询问操作数不超过10%。</p>
</div>
</div>