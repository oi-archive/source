<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>纳米猿很牛逼，他从来都是自己做计算器的！</p>
<p>这次，他的计算器的等于键突然弹出来，不知飞到哪里去了。没了等于键，整只计算器就算废掉了嘛。</p>
<p>呵呵，所以“凌凌扒”的第二个任务就是：</p>
<p>做一个简单、够用的计算器，只需要有加（<span style="font-family: 'Times New Roman';">+</span><span style="">）减（</span><span style="font-family: 'Times New Roman';">-</span><span style="">）乘（</span><span style="font-family: 'Times New Roman';">*</span><span style="">）整除（</span><span style="font-family: 'Times New Roman';">/</span><span style="">）和求余（</span><span style="font-family: 'Times New Roman';">%</span><span style="">）的运算。如果运算中出现数学错误（如除</span><span style="font-family: 'Times New Roman';">0</span><span style="">等），输出“</span><span style="font-family: 'Times New Roman';">Error!</span><span style="">”。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第<span style="font-family: 'Times New Roman';">1</span><span style="">行为一个整数</span>N，表示有N行运算命令；</p>
<p>第<span style="font-family: 'Times New Roman';">2</span><span style="">行为一个整数</span>A，表示原始数；</p>
<p>第<span style="font-family: 'Times New Roman';">3</span><span style="">行至第</span><span style="font-family: 'Times New Roman';">2+</span>N行为运算命令，每行包括一个运算符和一个非负整数B。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一个整数，为最后计算的结果。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>8</p>
<p>+ 2</p>
<p>- 3</p>
<p>* 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>14</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30<span style="">％的数据满足：</span>N&lt;10,0&lt;A&lt;10,<span style="">运算符只包括加、减</span><span style="font-family: 'Times New Roman';">,0&lt;</span>B&lt;10</p>
<p>50<span style="">％的数据满足：</span>N&lt;100,0&lt;A&lt;100,<span style="">运算符只包括加、减、乘</span><span style="font-family: 'Times New Roman';">,0&lt;</span>B&lt;100</p>
<p>80<span style="">％的数据满足：</span>N&lt;10000,-10000&lt;A&lt;10000,<span style="">运算符包括加、减、乘、整除、求余</span><span style="font-family: 'Times New Roman';">,-10000&lt;</span>B&lt;10000</p>
<p>100<span style="">％的数据满足：</span>N&lt;100000,-200000&lt;A&lt;200000,<span style="">运算符包括加、减、乘、整除、求余</span><span style="font-family: 'Times New Roman';">,-200000&lt;</span>B&lt;200000</p>
<p>保证运算过程中数不超过<span style="font-family: 'Times New Roman';">10^9</span></p>
<p> </p>
<p><span style="font-family: Helvetica;">提示：只管mod和div，不用处理负数的情况</span></p>
</div>
</div>