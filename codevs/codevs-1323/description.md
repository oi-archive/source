<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>    话说<span style="font-family: Verdana;">Farmer Lunar</span></span><span> </span><span>加入了飞盘俱乐部，他想要从<span style="font-family: Verdana;">N</span></span><span>(1 &lt;= N &lt;=2,000)</span><span>只板猪里挑选若干只板猪组成若干支板猪飞盘队。为了方便，<span style="font-family: Verdana;">FL</span><span style="">将候选的</span><span style="font-family: Verdana;">N</span><span style="">只板猪编号为</span><span style="font-family: Verdana;">1..n</span><span style="">。待选的每一只板猪都已经接受了非常专业的培训，因此我们可以用</span></span><span>R_i (1 &lt;=R_i &lt;= 100,000)</span><span>来表示这些板猪的投飞盘的技术程度</span><span>. </span><span>FL<span style="">可以通过选择一只板猪或多只板猪来组建他的这些飞盘队。</span></span><span> </span><span>然而，<span style="font-family: Verdana;">FL</span><span style="">需要对选择加一些约束</span></span><span>. </span><span>FL<span style="">最喜欢的数字</span></span><span>F (1 &lt;= F &lt;= 1,000), </span><span>因此，<span style="font-family: Verdana;">FL</span><span style="">希望一个团队内各个奶牛的技术程度之和能够被</span><span style="font-family: Verdana;">F</span><span style="">整除，你可以认为只有当一个板猪飞盘队满足这个要求时才是一个合法的选择。</span></span></p>
<p><span>    请帮助</span><span> F</span><span>L<span style="">找出他最多有多少种不同的方案。但是，这个结果可能非常非常大，所以，为了给予你很多很多的信心，我们决定你只要输出结果关于</span></span><span>100,000,000</span><span>取模的余数即可。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>* 第一行: 两个由空格隔开的数 N 和 F</p>
<p> </p>
<p>* 第 2..N+1 行: 第i+1行包含一个整数: R_i</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p15"><span>输出文件只有一个整数</span><span>A&nbsp;</span><span>，表示<span style="font-family: Verdana;">FL</span><span style="font-family: 宋体;">最多能选择的队伍数关于</span><span style="font-family: Verdana;">100000000</span><span style="font-family: 宋体;">求余后的余数。</span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>4 5</span></p>
<p><span>1</span></p>
<p><span>2</span></p>
<p><span>8</span></p>
<p><span>2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>FL<span style="">可以选（</span><span style="font-family: Verdana;">1+2+2=5</span><span style="">），能被</span><span style="font-family: Verdana;">5</span><span style="">整除，满足</span><span style="font-family: Verdana;">FL</span><span style="">的条件，</span><span style="font-family: Verdana;">FL</span><span style="">也可以选第一个</span><span style="font-family: Verdana;">2</span><span style="">和</span><span style="font-family: Verdana;">8</span><span style="">或第二个</span><span style="font-family: Verdana;">2</span><span style="">和</span><span style="font-family: Verdana;">8</span><span style="">，这样一共有</span><span style="font-family: Verdana;">3</span><span style="">种选择的方法。</span></span></p>
<p><span><span style=""><br></span></span></p>
<p><span>5</span><span>0%<span style="">的数据，</span></span><span>1<span style="">≤</span><span style="font-family: Verdana;">n</span><span style="">≤</span><span style="font-family: Verdana;">19</span><span style="">，</span><span style="font-family: Verdana;">1</span><span style="">≤</span><span style="font-family: Verdana;">F</span><span style="">≤</span><span style="font-family: Verdana;">100</span><span style="">。</span></span></p>
<p><span>100%<span style="">的数据，</span></span><span>1<span style="">≤</span><span style="font-family: Verdana;">n</span><span style="">≤</span><span style="font-family: Verdana;">2000</span><span style="">，</span></span><span>1 &lt;= F &lt;= 1,000</span><span>。</span></p>
<p><span><br></span></p>
<p><span><br></span></p>
<p><span>By __Shi</span></p>
</div>
</div>