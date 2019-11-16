<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">有个二百五，总有不一样的想法，最近，他正在试着去生成随机数。他偶然发现一些旧文献，关于用“中央的平方”制作的看起来似乎是随机的数字的方法（即伪随机数）。它的工作原理是这样的：</p><p style="">*选择一个开始的四位数字<br> *提取中间两个数字（十位数字和百位数字）<br> *计算出这两个数字的平方<br> *那个平方值就是随机数，并且也是新的开始编号<br> 下面是一个实例：<br> 数字    中间数   平方值<br> 7339    33     1089<br> 1089    8      64<br> 64     6      36<br> 36     3      9<br> 9      0      0<br> 0      0      0</p><p style="">根据鸽巢原理（自行Wiki），随机数肯定会在10000次以内重复，然而上面的序列只经过了六个数字就重复了（下一个号码和接下来的号码都是0）<br> 请注意，可能会有比较复杂的重复序列，就像这样：<br> 数字   中间数   平方值<br> 2245   24      576<br> 576    57      3249<br> 3249   24      576</p><p><span style="">你的任务是告诉</span><span style="">这个二百五，</span><span style="">这个所谓的</span><span style="">“</span><span style="">随机数</span><span style="">”</span><span style="">将会在多少次之后重复。第一个实例的结果是</span><span style="">6</span><span style="">，第二个实例的结果是</span><span style="">3</span><span style="">。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">*</span><span style="">一行：一个单独的数字：</span><span style="">N<br> <br> </span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: 14px;font-family: 宋体">*</span><span style="font-size: 14px;font-family: 宋体">一行：这个差劲的伪随机数系统将会在多少次变换之后重复。</span><span style="font-size: 14px;font-family: 宋体"><br/> <br/> </span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7339</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>无</p>
</div>
</div>