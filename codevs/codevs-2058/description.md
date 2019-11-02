<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>定义满足以下规则字符串为规则序列，否则不是规则序列：</p>
<p>1．空序列是规则序列；</p>
<p>2．如果S是规则序列，那么(S),[S],{S}和&lt;S&gt;也是规则序列；</p>
<p>3．如果A和B都是规则序列，那么AB也是规则序列。</p>
<p> </p>
<p>例如，下面的字符串都是规则序列：</p>
<p>()，[]，(())，([])，()[]，()[()]，{{}}&lt;&gt;，([]&lt;&gt;{{}})，&lt;&lt;{}&gt;&gt;</p>
<p> </p>
<p>而以下几个则不是：</p>
<p>(，[，]，)(，())，([()，&lt;&lt;，{(})，&lt;{}&gt;)</p>
<p> </p>
<p>现在，给你一些由"("、")"、"["、"]"、"{"、"}"、"&lt;"、"&gt;"构成的字符串，请判断该字符串是否为规则序列。</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：一个正整数N，表示测试数据组数；</p>
<p>接下来N行：每行一个括号序列(长度不超过L)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共N行：对于每一个括号序列，判断其是否规则。</p>
<p>规则输出TRUE，否则输出FALSE。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>{()}&lt;&lt;&gt;&gt;</p>
<p>{{{{{}}}}</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>TRUE</p>
<p>FALSE</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于40%数据，有N=1，0&lt;L&lt;=20;<br>对于80%数据，有0&lt;N&lt;=5，0&lt;L&lt;=10^3;<br>对于100%数据，有0&lt;N&lt;=10，0&lt;L&lt;=2*10^6。</p>
</div>
</div>