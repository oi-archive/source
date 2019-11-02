<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>  相信大家都知道有些赌场记忆高手，可以在知道洗牌前的扑克牌排列情况，以及看到洗牌的过程后，就可以知道洗牌后的扑克牌排列情况。我们现在用电脑来模拟一下这个过程。</p>
<p>  现在给出一副新的排列好的去掉大小王的扑克牌，其排列从上到下为黑桃A-黑桃K、红桃A-红桃K、梅花A-梅花K、方块A-方块K。现在开始洗牌，洗牌方法为把上面的若干张扑克牌移到最下面，不断重复此过程，最后请你输出洗牌后的从上到下的扑克牌顺序。</p>
<p> </p>
<p> 扑克牌表示：</p>
<p>黑桃A到黑桃K： B1 到 B10 , BJ ,BQ,BK</p>
<p>红桃A到红桃K： H1 到 H10 , HJ ,HQ,HK</p>
<p>梅花A到梅花K： M1 到 M10 ,MJ ,MQ,MK</p>
<p>方块A到方块K： F1 到 F10 , FJ ,FQ,FK</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p> </p>
<p>输入第一行为一个整数 N(1&lt;=N&lt;=30)，代表洗牌的次数</p>
<p>输入第二行为N个正整数，范围为[1,51]，用空格隔开，代表洗牌时从上面移动到下面的扑克牌数目</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出为1行，包含52个用空格隔开的字符串，每个字符串代表一张扑克牌，输出行的最左和最右不能有空格。</p>

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
<p>1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>B4 B5 B6 B7 B8 B9 B10 BJ BQ BK H1 H2 H3 H4 H5 H6 H7 H8 H9 H10 HJ HQ HK M1 M2 M3 M4 M5 M6 M7 M8 M9 M10 MJ MQ MK F1 F2 F3 F4 F5 F6 F7 F8 F9 F10 FJ FQ FK B1 B2 B3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N(1&lt;=N&lt;=30)</p>
</div>
</div>