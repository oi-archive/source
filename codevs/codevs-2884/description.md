<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>现在,我们有一个用卡片组成的等式(卡片仅仅是数字和=号)</span><br><span>虽然是等式 但是它却是错误的.....</span><br><br><span>后来你觉得,</span><br><span>似乎在这个等式</span><span>左侧的某个地方添上<strong>一个加号“+”</strong></span><br><span>就可以使等式成立...</span><br><br><span>但是,,等到你要将之付诸行动的时候,</span><br><span>你却不懂得怎么做..</span><br><br><span>所以你决定求助于万能的计算机...</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>一行，一个等式</span><br><span>保证每个数字不会超过 maxlongint OR int</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>一行，</span><br /><span>如果可以成功使等式成立，</span><br /><span>就输出成立的等式，（如果存在多个等式成立就输出加号&lsquo;+&rsquo;最靠左的一个）</span><br /><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 如 输入221=23，则输出2+21=23，而不输出22+1=23</span></p>
<p><span>否则输出"Impossible!"(不含引号)</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>样例1</pre>
<pre>11=2</pre>
<pre>样例2</pre>
<pre>222=222</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>样例1</pre>
<pre>1+1=2</pre>
<pre>样例2</pre>
<pre>Impossible!</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>不要想得太复杂，蠢蠢的字符串操作。</p>
<p>注意请原始输出：如99=018输出9+9=018；像卡片一样哦，喵~</p>
</div>
</div>