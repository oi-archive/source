<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一天，同志们在一起交流自己的志向。N个人有N种志向，比如A,B,C,...,小X也不例外。</p>
<p>现在，她想请你帮助她在一大串连着的志向中找出和她一样的，进行累计。当然啦，这不包括小X自己。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>三行，第一行是小X的志向，为A-Z中的一个字母。</p>
<p>第二行是一个正整数N，表示不包括小X的总人数。</p>
<p>第二行是同志们的志向，是一大串几乎都是A-Z中的字母的字符串，共N个,但有极小的可能出现小写字母,小X要求你把小写字母过滤掉。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行，表示志向与小X相同的人数，且一定不大于N。</p>
<p>P.S.如果小X的志向就是小写字母，你应当输出"I do not like lowercase letters!"。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>A</p>
<p>3</p>
<p>ABC</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>0&lt;=N&lt;=10000且N为整数[实际上没那么大]</p>
<p><strong>注意过滤掉输入数据的小写字母，如果小X的志向就是小写字母，你应当直接输出"I do not like lowercase letters!",注意"!"后什么也没有。</strong></p>
</div>
</div>