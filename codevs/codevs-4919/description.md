<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">给你N个数，有两种操作</p><p style="">1：给区间[a,b]内的所有数都增加X</p><p style="">2：询问区间[a,b]能被7整除的个数</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行一个正整数n，接下来n行n个整数，再接下来一个正整数Q，表示操作的个数. 接下来Q行每行若干个整数。如果第一个数是add，后接3个正整数a,b,X，表示在区间[a,b]内每个数增加X,如果是count，表示统计区间[a,b]能被7整除的个数</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(88, 102, 110); font-family: &#39;Source Sans Pro&#39;, &#39;Helvetica Neue&#39;, Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px; background-color: rgb(255, 255, 255);">对于每个询问输出一行一个答案</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="font-family: Menlo, Monaco, Consolas, 'Courier New', monospace;">3
2 3 4
6
count 1 3
count 1 2
add 1 3 2
count 1 3
add 1 3 3
count 1 3</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style="">0<br style=""></p><p style="">0</p><p style="">0</p><p style="">1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="">10%:1&lt;N&lt;=10,1&lt;Q&lt;=10</p><p style="">30%:1&lt;N&lt;=10000,1&lt;Q&lt;=10000</p><p style="">100%:1&lt;N&lt;=100000,1&lt;Q&lt;=100000</p>
</div>
</div>