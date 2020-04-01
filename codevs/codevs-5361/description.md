<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style=""><strong style=""><span style="">   </span></strong><span style=""><strong style=""><span style=""> SQZ</span></strong><strong style="">是</strong><strong style=""><span style="">810</span></strong><strong style="">班的一个优等生，经常能解开许多难题。一天，一位好学的同学来找他，说是要问一道化学难题。</strong><br></span></span></p><p style=""><span style=""><strong style=""><span style="font-family: Arial, sans-serif;">    SQZ</span></strong><strong style="">对化学可是如鱼得水，很快便有了思路。但是</strong><strong style=""><span style="font-family: Arial, sans-serif;">SQZ</span></strong><strong style="">由于吃了太多鸡翅导致大脑回路堵塞，信息传递不畅，无法计算分子的分子量。在这道题目中，分子量必不可少。所以，</strong><strong style=""><span style="font-family: Arial, sans-serif;">SQZ</span></strong><strong style="">想到了你，他请你来帮忙，计算分子的分子量。</strong></span></p><p style=""><span style=""><strong style="">分子输入格式：</strong><strong style=""><span style="font-family: Arial, sans-serif;">A1B1A2B2</span></strong><strong style="">……</strong><strong style=""><span style="font-family: Arial, sans-serif;">AnBn</span></strong><strong style="">，其中</strong><strong style=""><span style="font-family: Arial, sans-serif;">Ai</span></strong><strong style="">表示原子</strong><strong style=""><span style="font-family: Arial, sans-serif;">(</span></strong><strong style="">或原子团</strong><strong style=""><span style="font-family: Arial, sans-serif;">)</span></strong><strong style="">，由一个大写字母或一个大写字母和一个小写字母组成，如：</strong><strong style=""><span style="font-family: Arial, sans-serif;">Cu,C,H,Ar</span></strong><strong style="">，</strong><strong style=""><span style="font-family: Arial, sans-serif;">Bi</span></strong><strong style="">表示原子个数（</strong><strong style=""><span style="font-family: Arial, sans-serif;">Bi</span></strong><strong style="">为</strong><strong style=""><span style="font-family: Arial, sans-serif;">1</span></strong><strong style="">时可省略，</strong><span style=""><strong>Bi&lt;9</strong></span><strong style="">）。原子团输入时需要加括号</strong><strong style=""><span style="font-family: Arial, sans-serif;">(</span></strong><strong style="">相应</strong><strong style=""><span style="font-family: Arial, sans-serif;">B</span></strong><strong style="">为</strong><strong style=""><span style="font-family: Arial, sans-serif;">1</span></strong><strong style="">时可省略</strong><strong style=""><span style="font-family: Arial, sans-serif;">)</span></strong><strong style="">，如</strong><strong style=""><span style="font-family: Arial, sans-serif;">:Ca(OH)2,CaCO3</span></strong><strong style="">。特殊的，CaCO3与Ca(CO3)都是合法的。并且，括号不会出现嵌套。</strong></span></p><p style=""><span style=""><strong style="">   【友情提示：测试数据中的原子及原子量不一定真实存在哦!】</strong></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><strong style=""><span style="font-family: Arial, sans-serif;">    </span></strong><strong style="">第一行为一个数</strong><strong style=""><span style="font-family: Arial, sans-serif;">m</span></strong><strong style="">，后面</strong><strong style=""><span style="font-family: Arial, sans-serif;">m</span></strong><strong style="">行，每行一个原子和它对应的原子量（保证满足计算分子量的需要）。</strong></p><p style=""><strong style=""><span style="font-family: Arial, sans-serif;">    </span></strong><strong style="">第</strong><strong style=""><span style="font-family: Arial, sans-serif;">m+2</span></strong><strong style="">行为一个数</strong><strong style=""><span style="font-family: Arial, sans-serif;">n</span></strong><strong style="">，表示有几个分子需要计算分子量，第二行至第</strong><strong style=""><span style="font-family: Arial, sans-serif;">n+1</span></strong><strong style="">行每一行一个分子。</strong></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-top: 0px; margin-bottom: 10px; white-space: normal; box-sizing: border-box;"><strong><span style="box-sizing: border-box; font-family: Arial, sans-serif;">&nbsp; &nbsp; n</span><span style="box-sizing: border-box; font-family: 宋体;">行，每行一个数，表示对应分子的分子量。</span></strong></p><p style="margin-top: 0px; margin-bottom: 10px; white-space: normal; box-sizing: border-box;"><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><strong style=""><span style="font-family: Arial, sans-serif;">3</span></strong></p><p style=""><strong style=""><span style="font-family: Arial, sans-serif;">C 12</span></strong></p><p style=""><strong style=""><span style="font-family: Arial, sans-serif;">O 16</span></strong></p><p style=""><strong style=""><span style="font-family: Arial, sans-serif;">H 1</span></strong></p><p style=""><strong style=""><span style="font-family: Arial, sans-serif;">2</span></strong></p><p style=""><strong style=""><span style="font-family: Arial, sans-serif;">CO2</span></strong></p><p style=""><strong style=""><span style="font-family: Arial, sans-serif;">H2O</span></strong></p><p style=""><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: Arial, sans-serif;">44</span></p><p style=""><span style="font-family: Arial, sans-serif;">18</span></p><p style=""><br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong style=""><span style="font-family: Arial, sans-serif;">100%</span></strong><strong style="">的数据，分子式长度不超过</strong><strong style=""><span style="font-family: Arial, sans-serif;">100</span></strong><strong style="">，</strong><strong style=""><span style="font-family: Arial, sans-serif;">m&lt;=5,n&lt;=30;</span></strong></p>
</div>
</div>