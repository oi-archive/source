<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>某陈痴迷于pku的ACM题库,常常彻夜奋斗刷题.他最近的目标是在NOIP08到来之前刷进RANK[排名]200.</p>
<p>//----------^_^ encourage...-----------</p>
<p>pku对用户RANK的排列基于2个参数.Solved[通过的题数]和Submissions[提交次数].而二者之比就是AC Ratio[通过率].它反映一个用户的代码质量.话说某陈的AC Ratio就快降到60%了..郁闷ing.</p>
<p>最近某陈看到pku上有一串非常搞笑的用户,他们Solved的数量相同,而Submissions是从a到b的连续整数.某陈想要知道他们的AC Ratio之和.</p>
<p>当然,某陈要求的AC Ratio并不是完全如上所述[某陈:切..要是那样我自己就会写].他讨厌误差,于是他把Solved的数量用某种诡异的算法扩大了许多许多,变成一个整数n[数据保证0&lt;n,但并不保证n&lt;=b],他要求的AC Ratio,是n除以Submissions的商向上取整.</p>
<p>请帮某陈以他的方式计算那一串用户的AC Ratio之和. </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件包含3个整数,依次为题目描述中的n,a,b.数据保证0&lt;a&lt;=b&lt;2^31,0&lt;n&lt;2^31. </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件应包含一个整数,是题目所要求的AC Ratio之和.&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>18  8 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>[18/8]+[18/9]+[18/10]=3+2+2=7</p>
<p>[x]为实数x向上取整的值,例如 [5]=[4.03]=[4.92]=5 </p>
</div>
</div>