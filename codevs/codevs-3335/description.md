<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<div>    如果罗马帝国没有覆灭，那么他们会用电子计算器。然而，罗马人用的却是罗马数字！你的任务是制造一个简单的罗马数字计算器，输入两个罗马数字，输出它们的总和。大于1000的数字都是非法的，应该输出“CONCORDIA CUM VERITATE”。</div>
<div>    输入一个数字，表示算式的数目。然后输入算式。每一个算式的格式是 一个罗马数字+另一个罗马数字= 得数 。</div>
<div>    输出是n个算式和计算结果。对于多个算式用一个空行分开。</div>
<div>    由于罗马数字有悠久的历史，所以有一些罗马数字的写作方式发生了变化。我们将使用下列的规则：</div>
<div>    1、符号的意义：I    V    X     L      C         D       M</div>
<div>                          1    5    10   50  100   500   1000</div>
<div>    2、从左到右，符号最多连续三次使用。你如果不知道这代表什么，请看下面：</div>
<div>   当一个单一的I在V或X前面，代表减去1.当一个X在L或C前面，代表减去十。当一个C在D或M前面，代表减去100。</div>
<div>    示例： II=2  IX=9   CXIII=113   LIV=54   XXXVIII=38   XCIX=99.</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行一个整数n，以下n行输入n个罗马数字算式，用如下的格式：“罗马数字+罗马数字=”。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>输入出有n行，输出n个用罗马数字表示的加法算式，格式为：&ldquo;加数+加数=总和&rdquo;。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br>VII+II=<br>XXIX+X=<br>M+I=</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>VII+II=IX<br>XXIX+X=XXXIX<br>M+I=CONCORDIA CUM VERITATE</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>为了地球的河蟹 社会的稳定 十二五计划的预期完成 全民奔小康的目标早日达到 请不要卡评测</p>
</div>
</div>