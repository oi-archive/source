<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">   在异乡打拼的小李同志迷上了一款叫斯诺克的台球游戏，而且随着练习的深入，他总是能在某些神奇的时候开启外挂模式，此时小李指哪打哪，直至无球可打。现在小李想让你帮他计算下当他开启外挂模式的时候最多可以取得多少分数。</span></p>&lt;h4&gt;<span style="">  注意：台面上的球数经常会<span style=""></span>异于传统斯诺克。</span>&lt;/h4&gt;<p><span style="">  斯诺克比赛的基本规则如下：</span></p><p><span style="">  一、彩球共分8种颜色，红（1分）、黄（2分）、绿（3分）、棕（4分）、蓝（5分）、粉（6分）、黑（7分）、白（主球，控制白球大其余球）。</span></p><p><span style="">  二、当台面上有红球的时候你必须先击打一个红球，然后只能击打一个彩球（不包括红球），此时落袋的彩球将会被放回桌面，一直重复该过程。</span></p><p><span style="">  三、当打完规则二的彩球（不包括红球）发现已经没有红球时，按彩球的分值从高到低将其依次击入袋中。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>  输入仅有一行，共7个用空格隔开的整数，分别为当前台面上红、黄、绿、棕、蓝、粉、黑球的数目。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; 输出仅有一行，共1个整数，表示小李可以得到的最高得分。<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 0 1 0 3 0 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>48</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】<br></p><p>    台面上共有红球2个、绿球1个、蓝球3个、黑球2个，获得最高分的打法是红-黑-红-黑-绿-蓝-蓝-蓝-黑-黑，共可以获得48分。</p><p>【数据规模】</p><p>    保证最后得分不超过2^31-1.</p>
</div>
</div>