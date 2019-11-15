<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>      小A想买一顶新帽子，商店里有n个帽子 (1&lt;=n&lt;=100)，每顶帽子上有一个字符串，字符串的长度为len (1&lt;=len&lt;=500)。她认为每顶帽子上的字符串看起来越对称则代表这顶帽子更漂亮。根据每个字符串，我们可以算出其对称系数k (即最长对称子序列的长度) 来比较各顶帽子在小A心中的漂亮程度。</p>
<p>      例如，字符串 character (k=5) 比 pollution (k=4) 更对称，apple (k=2) 比 pear (k=1) 更对称。</p>
<p>      现在给定n个字符串，请将它们按对称系数排序后从大小输出 (k相同时按字典序排序)。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入数据第一行只有一个n，表示有个字符串。</p>
<p>接下来有n行，每行一个字符串。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出有n行，每行一个字符串，表示按对称系数从大到小排序后的字符串，对称系数相同时按字典序排序。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>pineapple</p>
<p>banana</p>
<p>peach</p>
<p>coconut</p>
<p>character</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>banana</p>
<p>character</p>
<p>pineapple</p>
<p>coconut</p>
<p>peach</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据范围：</p>
<p>1&lt;=n&lt;=100</p>
<p>1&lt;=len&lt;=500</p>
<p>1&lt;=k&lt;=len</p>
<p>提示：</p>
<p>对称系数k是指最长对称子序列的长度，非最长对称子串的长度。</p>
</div>
</div>