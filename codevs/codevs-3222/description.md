<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>看见盟军的质子撞击炮轰得这么有型，芳朗天皇看不下去了。他找到了他可爱的发明家，搞了一个超能波毁灭装置（话说这个东西是以奥米茄百合子复制人作为能量源，真™不人道）。这个东东和撞击炮不一样，它打出来是一发炮弹，然后是范围伤害。假设毁灭装置能够消灭所有的在他攻击范围内的东西，又能够实施精确的打击（就是想打哪里就打哪里，不会偏），给出攻击范围，给出敌方的建筑物价值，问怎样轰击才能达到最大的效果。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>前5行是攻击范围，空格表示攻击不到，“.”表示可以击毁。（每行的元素个数不明，以回车结束）</p>
<p>第6行是n m，表示敌方的基地大小</p>
<p>下面是个n*m的矩阵，表示敌方的每个建筑的价值。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个n，表示最大的价值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>  .//空格空格点回车</p>
<p> ...//空格点点点回车</p>
<p>.....//点点点点点回车</p>
<p> ...//空格点点点回车</p>
<p>  .//空格空格点回车</p>
<p>7 6</p>
<p>1 7 9 0 1 4 3</p>
<p>2 9 4 9 2 2 5</p>
<p>9 9 9 9 9 8 3</p>
<p>1 4 6 1 4 1 1</p>
<p>1 0 8 7 1 4 3</p>
<p>5 3 6 2 3 5 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>95</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>纯模拟，n，m&lt;=20</p>
<p>我只会告诉你前五行每行元素不超过10个</p>
<p>数据不会非常强，但可能很刁钻。</p>
<p>边角的处理的话，打在基地圈外面的不造成伤害，</p>
<p><span style="text-decoration: line-through;">我可没说所有的建筑价值都是正数</span></p>
</div>
</div>