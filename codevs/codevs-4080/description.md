<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">对于一个递归函数w(a,b,c)</p><p style="">如果a&lt;=0 or b&lt;=0 or c&lt;=0就返回值1.<br>如果a&gt;20 or b&gt;20 or c&gt;20就返回w(20,20,20)<br>如果a&lt;b并且b&lt;c 就返回w(a,b,c-1)+w(a,b-1,c-1)-w(a,b-1,c)<br>其它别的情况就返回w(a-1,b,c)+w(a-1,b-1,c)+w(a-1,b,c-1)-w(a-1,b-1,c-1)</p><p style="">这是个简单的递归函数，但实现起来可能会有些问题。当a,b,c均为15时，调用的次数将非常的多。你要想个办法才行.</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">会有若干行.</span><br style=""><span style="">并以-1，-1，-1结束.</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &#39;Lucida Grande&#39;, Lucida, &#39;Lucida Sans Unicode&#39;, &#39;Lucida Sans&#39;, Tahoma, &#39;Segoe UI&#39;, Verdana, 微软雅黑, &#39;Microsoft YaHei&#39;, 宋体; font-size: 14px; line-height: 21px; background-color: rgb(255, 255, 255);">输出若干行</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre style="">1 1 1
2 2 2
-1 -1 -1</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>w(1, 1, 1) = 2</p><p>w(2, 2, 2) = 4</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>by HZ幻想<br></p>
</div>
</div>