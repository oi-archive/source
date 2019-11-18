<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>假设phi(W)得到是按照以下算法编码后的结果：</p>
<p>1、 如果W的长度为1那么phi(W)即为W；</p>
<p>2、 假设需要编码的单词W = w1w2...w，并且K = N / 2<span style="">（</span>取下整）；</p>
<p>3、 phi(W) = phi(wNwN-1...wK+1) + phi(wKwK-1...w1)</p>
<p>例如，phi('Ok') = 'kO', phi('abcd') = 'cdab'.</p>
<p>你的任务就是，找到wq在经过phi(W)编码后的单词中的位置。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件encode.in的第<span style="font-family: 'Courier New';">1</span><span style="">行</span>包含<span style="font-family: 'Times New Roman';">2</span><span style="">个正整数</span><span style="font-family: 'Times New Roman';">N</span><span style="">和</span><span style="font-family: 'Times New Roman';">q</span><span style="">，</span><span style="font-family: 'Times New Roman';">N</span><span style="">为单词</span><span style="font-family: 'Times New Roman';">W</span><span style="">的长度。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件encode.out包含<span style="font-family: 'Times New Roman';">1</span><span style="font-family: 宋体;">行，即字母</span>wq在编码后单词phi(W)中的位置。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>9 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p> </p>
<p>【限制】</p>
<p>    30%<span style="">的数据满足：</span><span style="font-family: 'Times New Roman';">N&lt;=100</span><span style="">；</span></p>
<p>100%<span style="">的数据满足：</span>1 &lt;= N &lt;= 10<sup>9</sup>; 1&lt;= q &lt;= N。</p>
</div>
</div>