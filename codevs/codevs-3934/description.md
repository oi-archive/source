<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">   <span style=""> 有一个很古老的游戏叫做“接苹果”，是一个单人游戏，需要非常高的APM。</span></span></p><p><span style="">    简化后的游戏是这样的：从0时刻开始就会陆续掉下一些苹果，而你需要控制篮子左右移动来接这些苹果，篮子移动的速度为1。</span></p><p><span style="">    现在你已知共有N个苹果会落下来，第i个苹果会在Ti时刻掉落在位置Si上。如果你要接住所有的苹果，那么有时候只用一个篮子是不可能做到的，因此你需要更多的篮子，但如果篮子太多了，你会操作不过来，因此篮子的个数要尽量少。所以你需要求出接住所有苹果最少需要的篮子个数。</span></p><p><strong><span style="">    一开始你可以在任何位置。</span></strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入文件的第一行包含一个正整数N。</span></p><p><span style="">接下来N行，每行两个整数Si和Ti。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 微软雅黑, &#39;Microsoft YaHei&#39;; font-size: 18px;">输出文件的第一行包含一个正整数M，表示最少需要的篮子个数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1：</p><p><span style="font-family: arial, helvetica, sans-serif;">1</span></p><p><span style="font-family: arial, helvetica, sans-serif;">1 1</span></p><p>样例2：</p><p><span style="font-family: arial, helvetica, sans-serif;">10</span></p><p><span style="font-family: arial, helvetica, sans-serif;">4 19</span></p><p><span style="font-family: arial, helvetica, sans-serif;">2 29</span></p><p><span style="font-family: arial, helvetica, sans-serif;">4 18</span></p><p><span style="font-family: arial, helvetica, sans-serif;">9 20</span></p><p><span style="font-family: arial, helvetica, sans-serif;">4 18</span></p><p><span style="font-family: arial, helvetica, sans-serif;">5 10</span></p><p><span style="font-family: arial, helvetica, sans-serif;">3 14</span></p><p><span style="font-family: arial, helvetica, sans-serif;">4 16</span></p><p><span style="font-family: arial, helvetica, sans-serif;">9 31</span></p><p><span style="font-family: arial, helvetica, sans-serif;">5 10</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1：<br></p><p><span style="font-family: arial, helvetica, sans-serif;">1</span></p><p>样例2：</p><p><span style="font-family: arial, helvetica, sans-serif;">2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">对于30%的数据，1&lt;=N&lt;=50,1&lt;=M&lt;=4</span></p><p style=""><span style=""><span style="">对于</span>60%<span style="">的数据，</span>1&lt;=N&lt;=300</span></p><p style=""><span style=""><span style="">对于</span>80%<span style="">的数据，</span>1&lt;=N&lt;=1000</span></p><p style=""><span style=""><span style="">对于</span>100%<span style="">的数据：</span>1&lt;=N&lt;=100000<span style="">，</span>0&lt;=Si,Ti&lt;=1000000000</span></p>
</div>
</div>