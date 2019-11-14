<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>教务网站如期的在选课之日出问题了，这次的问题是登陆窗口的验证码无法显示了，同学们只能靠猜验证码来登陆选课。教务的登陆系统刚刚经过改进，改进后的验证码均为1..N的一个排列。一般的同学们在试验的时候都是按照所有排列的字典序逐个试验，但是TN发掘这样试验很乏味，所以他决定每次尝试前一个排列后面的第M个排列。</p>
<p>但是一段时间之后他发现，寻找一个排列后面的第M个排列并不是一件容易的事情，所以他希望你帮助他。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>Line 1： N (1 &lt;= N &lt;= 10000)</span><br><span>Line 2： M (M &lt;= 100)</span><br><span>Line 3： 1..N的一个排列</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>所求的排列</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>5
3
1 2 3 4 5</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>1 2 4 5 3</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>(1 &lt;= N &lt;= 10000)</span></p>
<p><span><span>(M &lt;= 100)</span></span></p>
<p><span><span>提示：m可能为负数（这时就求前m个排列）</span></span></p>
</div>
</div>