<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一个元素均为正整数的序列，元素个数为n，同时给定m个区间，再给一个数字p。</p><p>一个区间是合法的是指该区间中的最大值不小于p。</p><p>q次修改，k x表示将第k个元素修改为x。</p><p>每次修改后，需要输出一行一个数，表示修改后，给定的m个区间中合法区间的总数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行四个数n、m、p、q。</p><p>接下来一行n个正整数表示数组中的初始元素。</p><p>接下来m行每行两个正整数表示给定的区间。</p><p>接下来q行，每行一次修改，如题面所述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>q行，每行一个数表示这次修改后合法区间的数量。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 1 3 3</p><p>1</p><p>1 1</p><p>1 2</p><p>1 3</p><p>1 2</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0</p><p>1</p><p>0</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">40%：1&lt;=n,m,p,q&lt;=10</span></p><p><span style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">80%：1&lt;=n,m,p,q&lt;=100000</span></p><p><span style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">100%：1&lt;=n,m,p,q&lt;=200000</span></p>
</div>
</div>