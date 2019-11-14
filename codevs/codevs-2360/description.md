<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>最近在JLOI网上的一个流行游戏中，选手要回答很难的问题。假如在规定时间内不能回答，系统将给出1个提示，之后再依次给出第2，3个提示。出现在答案中的是字母和下列字符：</p>
<p>'.',',',':',';','!','?','-'和空格（空格不会在开头和结尾出现）</p>
<p>字母是指：小写字母'a'...'z' 大写字母 'A'...'Z'，其中aeiouAEIOU是元音字母。</p>
<p> </p>
<p>生成提示的规则：</p>
<p>第1个提示：简单的将所有字母换成'.'即可；</p>
<p>第2个提示：从第1个提示而来，将所有<strong>字母</strong>的个数求出，再将总个数除以三，得到的最接近商的自然数N，将第1个提示中的前N个字母显示；</p>
<p>第3个提示：从第2个提示而来，将剩下的元音字母显示。假如没有可显示的元音字母，则从第1个提示而来，即我们将前2/3的字母显示（同样如不能被3整除则取最接近的整数）。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>仅一行，给出问题，问题字符数最多不超过50。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>三行：按规则输出的三行提示。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>Upomoc! Lpv s nm pkrl sv smglsnk. </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>......! ... . .. .... .. ........</p>
<p>Upomoc! Lp. . .. .... .. ........</p>
<p>Upomoc! Lpv s nm pkrl s. ........</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>问题字符数最多不超过50</p>
</div>
</div>