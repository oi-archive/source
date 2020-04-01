<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">若某个家族人员过于庞大，要判断两个是否是亲戚，确实还很不容易，现在给出某个亲戚关系图，求任意给出的两个人是否具有亲戚关系。</span></p><p><span style="text-decoration: underline;"><em><span style="text-decoration: underline; font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">规定：x和y是亲戚，y和z是亲戚，那么x和z也是亲戚。如果x,y是亲戚，那么x的亲戚都是y的亲戚，y的亲戚也都是x的亲戚。</span> </em></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">第一行：三个整数n,m,p，（n&lt;=5000,m&lt;=5000,p&lt;=5000），分别表示有n个人，m个亲戚关系，询问p对亲戚关系。</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">以下m行：每行两个数Mi，Mj，1&lt;=Mi，Mj&lt;=N，表示Ai和Bi具有亲戚关系。</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">接下来p行：每行两个数Pi，Pj，询问Pi和Pj是否具有亲戚关系。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &#39;Segoe UI&#39;, &#39;Lucida Grande&#39;, Helvetica, Arial, &#39;Microsoft YaHei&#39;, FreeSans, Arimo, &#39;Droid Sans&#39;, &#39;wenquanyi micro hei&#39;, &#39;Hiragino Sans GB&#39;, &#39;Hiragino Sans GB W3&#39;, FontAwesome, sans-serif; font-size: 15px; line-height: 24px; background-color: rgba(255, 255, 255, 0.8);">P行，每行一个’Yes’或’No’。表示第i个询问的答案为“具有”或“不具有”亲戚关系。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="font-family: Monaco, Menlo, Consolas, 'Courier New', FontAwesome, monospace;">6 5 3
1 2
1 5
3 4
5 2
1 3
1 4
2 3
5 6</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="font-family: Monaco, Menlo, Consolas, 'Courier New', FontAwesome, monospace;">Yes
Yes
No</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>题目中已有，不重复解释。</p>
</div>
</div>