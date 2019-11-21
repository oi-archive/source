<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="font-family: impact, chicago;"><strong><span style="font-family: impact, chicago;">Teacher Egg</span></strong><strong><span style="font-family: impact, chicago;">经常跟</span></strong><strong><span style="font-family: impact, chicago;">Teacher Cao</span></strong><strong><span style="font-family: impact, chicago;">玩一个游戏：对于一个给定的</span></strong><strong><span style="font-family: impact, chicago;">y*x</span></strong><strong><span style="font-family: impact, chicago;">的矩阵，矩阵中的每个元素</span></strong><strong><span style="font-family: impact, chicago;">a[i,j]</span></strong><strong><span style="font-family: impact, chicago;">均为非负整数。游戏规则如下：</span></strong></span></p><p style=""><span style="font-family: impact, chicago;"><strong><span style="font-family: 'Courier New';">1.</span></strong><strong><span style="">每次取数时须从每行各取走一个元素，共</span></strong><strong><span style="font-family: 'Courier New';">y</span></strong><strong><span style="">个。</span></strong><strong><span style="font-family: 'Courier New';">x</span></strong><strong><span style="">次后取完矩阵所有元素；</span></strong></span></p><p style=""><span style="font-family: impact, chicago;"><strong><span style="font-family: 'Courier New';">2.</span></strong><strong><span style="">每次取走的各个元素只能是该元素所在行的行首或行尾；</span></strong></span></p><p style=""><span style="font-family: impact, chicago;"><strong><span style="font-family: 'Courier New';">3.</span></strong><strong><span style="">每次取数都有一个得分值，为每行取数的得分之和，每行取数的得分</span></strong><strong><span style="font-family: 'Courier New';">=</span></strong><strong><span style="">被取走的元素值×</span></strong><strong><span style="font-family: 'Courier New';">2ⁿ</span></strong><strong><span style="">，其中</span></strong><strong><span style="font-family: 'Courier New';">n</span></strong><strong><span style="">表示第</span></strong><strong><span style="font-family: 'Courier New';">n</span></strong><strong><span style="">次取数（从</span></strong><strong><span style="font-family: 'Courier New';">1</span></strong><strong><span style="">开始编号）；</span></strong></span></p><p style=""><span style="font-family: impact, chicago;"><strong><span style="font-family: 'Courier New';">4.</span></strong><strong><span style="">游戏结束总得分为</span></strong><strong><span style="font-family: 'Courier New';">x</span></strong><strong><span style="">次取数得分之和。</span></strong></span></p><p style=""><span style="font-family: impact, chicago;"><strong><span style="font-family: 'Courier New';"><strong style=""><span style="font-family: 'Courier New';">Teacher Egg</span></strong></span></strong><strong><span style="">想请你帮忙写一个程序，对于任意矩阵，可以求出取数后的最大得分。</span></strong></span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: impact, chicago;"><strong><span style="font-family: impact, chicago;">输入文件</span></strong><strong><span style="font-family: impact, chicago;">game.in</span></strong><strong><span style="font-family: impact, chicago;">包括</span></strong><strong><span style="font-family: impact, chicago;">n+1</span></strong><strong><span style="font-family: impact, chicago;">行：</span></strong></span></p><p style=""><span style="font-family: impact, chicago;"><strong><span style="">第</span></strong><strong><span style="font-family: 'Courier New';">1</span></strong><strong><span style="">行为两个用空格隔开的整数</span></strong><strong><span style="font-family: 'Courier New';">n</span></strong><strong><span style="">和</span></strong><strong><span style="font-family: 'Courier New';">m</span></strong><strong><span style="">。</span></strong></span></p><p style=""><span style="font-family: impact, chicago;"><strong><span style="">第</span></strong><strong><span style="font-family: 'Courier New';">2~n+1</span></strong><strong><span style="">行为</span></strong><strong><span style="font-family: 'Courier New';">n*m</span></strong><strong><span style="">矩阵，其中每行有</span></strong><strong><span style="font-family: 'Courier New';">m</span></strong><strong><span style="">个用单个空格隔开的非负整数。</span></strong></span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="line-height:24px"><span style="font-family: impact, chicago; font-size: 20px;"><strong><span style="font-family: impact, chicago;">输出文件</span></strong><strong><span style="font-family: impact, chicago;">game.out</span></strong><strong><span style="font-family: impact, chicago;">仅包含</span></strong><strong><span style="font-family: impact, chicago;">1</span></strong><strong><span style="font-family: impact, chicago;">行，为一个整数，即输入矩阵取数后的最大得分。</span></strong></span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: impact, chicago;">2 3<br></span></p><p><span style="font-family: impact, chicago;">1 2 3</span></p><p><span style="font-family: impact, chicago;">3 4 2</span><span style="font-family: impact, chicago;"></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: impact, chicago;">82</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: impact, chicago;">数据范围：</span></p><p><span style="font-family: impact, chicago;">    用长整型就OK了 O(∩_∩)O哈哈~</span></p><p><span style="font-family: impact, chicago;"><br></span></p><p><span style="font-family: impact, chicago;">提示：</span></p><p><span style="font-family: impact, chicago;">    不会的看题解去吧 ε=ε=ε=(~￣▽￣)~</span></p>
</div>
</div>