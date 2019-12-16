<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在桌面上有一排硬币，共<span style="font-family: 'Times New Roman';">N</span><span style="">枚，每一枚硬币均为正面朝上。现在要把所有的硬币翻转成反面朝上，规则是每次可翻转任意</span><span style="font-family: 'Times New Roman';">N-1</span><span style="">枚硬币（正面向上的被翻转为反面向上，反之亦然）。求一个最短的操作序列（将每次翻转</span><span style="font-family: 'Times New Roman';">N-1</span><span style="">枚硬币成为一次操作）。</span></p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入只有一行，包含一个自然数<span style="font-family: 'Times New Roman';">N</span>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件的第一行包含一个整数<span style="font-family: 'Times New Roman';">S</span><span style="font-family: 宋体;">，表示最少需要的操作次数。接下来的</span><span style="font-family: 'Times New Roman';">S</span><span style="font-family: 宋体;">行每行分别表示每次操作后桌上硬币的状态（一行包含</span><span style="font-family: 'Times New Roman';">N</span><span style="font-family: 宋体;">个整数（</span><span style="font-family: 'Times New Roman';">0</span><span style="font-family: 宋体;">或</span><span style="font-family: 'Times New Roman';">1</span><span style="font-family: 宋体;">），表示每个硬币的状态：</span><span style="font-family: 'Times New Roman';">0</span><span style="font-family: 宋体;">&mdash;&mdash;正面向上，和</span><span style="font-family: 'Times New Roman';">1</span><span style="font-family: 宋体;">&mdash;&mdash;反面向上，不允许出现多余空格）。</span></p>
<p class="p0">对于有多种操作方案的情况，则只需输出一种。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div>
<p>4</p>
<p>0111</p>
<p>1100</p>
<p>0001</p>
<p>1111</p>
<p> </p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N<span style="">为不大于</span><span style="font-family: 'Times New Roman';">100</span><span style="">的</span>偶数</p>
</div>
</div>