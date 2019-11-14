<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>奶牛们打算通过锻炼来培养自己的运动细胞，作为其中的一员，贝茜选择的运动方式是每天进行<span style="font-family: Times New Roman;">N(1 &lt;= N &lt;= 10,000)</span><span style="">分钟的晨跑。在每分钟的开始，贝茜会选择下一分钟是用来跑步还是休息。</span></p>
<p> </p>
<p>    贝茜的体力限制了她跑步的距离。更具体地，如果贝茜选择在第<span style="font-family: Times New Roman;">i</span><span style="">分钟内跑步，她可以在这一分钟内跑</span><span style="font-family: Times New Roman;">D_i(1 &lt;= D_i &lt;= 1,000)</span><span style="">米，并且她的疲劳度会增加</span><span style="font-family: Times New Roman;">1</span><span style="">。不过，无论何时贝茜的疲劳度都不能超过</span><span style="font-family: Times New Roman;">M(1 &lt;= M &lt;= 500)</span><span style="">。如果贝茜选择休息，那么她的疲劳度就会每分钟减少</span><span style="font-family: Times New Roman;">1</span><span style="">，但她必须休息到疲劳度恢复到</span><span style="font-family: Times New Roman;">0</span><span style="">为止。在疲劳度为</span><span style="font-family: Times New Roman;">0</span><span style="">时休息的话，疲劳度不会再变动。晨跑开始时，贝茜的疲劳度为</span><span style="font-family: Times New Roman;">0</span><span style="">。</span></p>
<p>    还有，在<span style="font-family: Times New Roman;">N</span><span style="">分钟的锻炼结束时，贝茜的疲劳度也必须恢复到</span><span style="font-family: Times New Roman;">0</span><span style="">，否则她将没有足够的精力来对付这一整天中剩下的事情。</span></p>
<p>    请你计算一下，贝茜最多能跑多少米</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第<span style="font-family: Times New Roman;">1</span><span style="">行</span><span style="font-family: Times New Roman;">: 2</span><span style="">个用空格隔开的整数：</span><span style="font-family: Times New Roman;">N </span><span style="">和 </span><span style="font-family: Times New Roman;">M</span></p>
<p>第<span style="font-family: Times New Roman;">2..N+1</span><span style="">行</span><span style="font-family: Times New Roman;">: </span><span style="">第</span><span style="font-family: Times New Roman;">i+1</span><span style="">为</span><span style="font-family: Times New Roman;">1</span><span style="">个整数：</span><span style="font-family: Times New Roman;">D_i</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出<span style="font-family: Times New Roman;">1</span><span style="font-family: 宋体;">个整数，表示在满足所有限制条件的情况下，贝茜能跑的最大距离</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 2</p>
<p>5</p>
<p>3</p>
<p>4</p>
<p>2</p>
<p>10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>贝茜在第<span style="font-family: Times New Roman;">1</span><span style="">分钟内选择跑步（跑了</span><span style="font-family: Times New Roman;">5</span><span style="">米），在第</span><span style="font-family: Times New Roman;">2</span><span style="">分钟内休息，在第</span><span style="font-family: Times New Roman;">3</span><span style="">分钟内跑步（跑了</span><span style="font-family: Times New Roman;">4</span><span style="">米），剩余的时间都用来休息。因为在晨跑结束时贝茜的疲劳度必须为</span><span style="font-family: Times New Roman;">0</span><span style="">，所以她不能在第</span><span style="font-family: Times New Roman;">5</span><span style="">分钟内选择跑步</span></p>
</div>
</div>