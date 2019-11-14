<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　有一个长度为n的序列，有三个操作1.I a b c表示将[a,b]这一段区间的元素集体增加c，2.R a b表示将[a,b]区间内所有元素变成相反数，3.Q a b c表示询问[a,b]这一段区间中选择c个数相乘的所有方案的和mod 19940417的值。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　第一行两个数n，q表示序列长度和操作个数。</span><br><span>　　第二行n个非负整数，表示序列。</span><br><span>　　接下来q行每行输入一个操作I a b c或者 R a b或者Q a b c意义如题目描述。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　对于每个询问，输出选出c个数相乘的所有方案的和mod19940417的值。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>5 5</span><br><span>1 2 3 4 5</span><br><span>I 2 3 1</span><br><span>Q 2 4 2</span><br><span>R 1 5</span><br><span>I 1 3 -1</span><br><span>Q 1 5 1</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>40</span><br><span>19940397</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>　　做完第一个操作序列变为1 3 4 4 5。</span><br><span>　　第一次询问结果为3*4+3*4+4*4=40。</span><br><span>　　做完R操作变成-1 -3 -4 -4 -5。</span><br><span>　　做完I操作变为-2 -4 -5 -4 -5。</span><br><span>　　第二次询问结果为-2-4-5-4-5=-20。</span></p>
<p><span><br></span></p>
<p><span><span>　　10%的数据n&lt;=10,q&lt;=10。</span><br><span>　　另30%的数据没有I和R操作。</span><br><span>　　另30%的数据没有I操作。</span><br><span>　　100%的数据n&lt;=50000,q&lt;=50000,初始序列的元素的绝对值&lt;=10</span><sup>9</sup><span>，I a b c中保证[a,b]是一个合法区间，|c|&lt;=10</span><sup>9</sup><span>，R a b保证[a,b]是个合法的区间。Q a b c中保证[a,b]是个合法的区间1&lt;=c&lt;=min(b-a+1,20)。</span></span></p>
<p><span><span><br></span></span></p>
<p><span><span>来源：<span>中国国家队清华集训 2012-2013 第三天</span></span></span></p>
</div>
</div>