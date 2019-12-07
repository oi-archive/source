<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>yjq喜欢数列。</p><p>某天的数学课上，yjq觉得老师讲的太简单了，于是在纸上玩起了数列。他在纸上写了一个长度为n的整数序列A，有正有负。他认为一个正负相间的数列是“美丽的数列”，但是他觉得只是正负相间又太无聊了，于是他加了一个条件——绝对值严格递增。</p><p>现在yjq开始寻找这个数列中最长的满足上述要求的子序列，但是因为他写的数列太长了，他没有办法很快的找到这个串。虽然yjq是神犇，但是数学课上是不可能敲代码的。于是他偷偷用手机联络你，请你帮他找出这样的子序列。</p><p>由于短信过长会被强制分条发送，而且短信费很贵（出题人很懒不想写spj），你只需要告诉他最长的子序列的长度就可以了。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入共两行。</p><p>第一行一个正整数n，表示数的个数。</p><p>第二行n个整数，为yjq写下的原序列。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出共一行。<br/></p><p>第一行为一个正整数l，表示符合要求的最长的子序列的长度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p>-1 2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据：n&lt;=1000<br></p><p>对于另外20%的数据：n&lt;=5*10<sup>5</sup>, 0&lt;=|A<sub>i</sub>|&lt;=2*10<sup>6</sup>, 整个序列绝对值递增</p><p>对于100%的数据：n&lt;=5*10<sup>5</sup>, 0&lt;=|A<sub>i</sub>|&lt;=10<sup>18</sup></p><p><sup><br></sup></p><p><span style="">hint：0既不是正数也不是负数。既然这样为什么不在造数据的时候直接不生成0呢？因为出题人是用python造的数据，而出题人实在是太懒了_(:зゝ∠)_</span></p>
</div>
</div>