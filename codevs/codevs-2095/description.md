<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>你刚刚接手一项窗体界面工程。窗体界面还算简单，而且幸运的是，你不必显示实际的窗体。有 5 种基本操作：</p>
<pre>创建一个新窗体
将窗体置顶
将窗体置底
删除一个窗体
输出窗体可见部分的百分比（就是，不被其它窗体覆盖的部分）。
</pre>
<p>在输入文件中，操作以如下的格式出现。</p>
<pre>创建一个新窗体：w(I,x,y,X,Y)
将窗体置顶： t(I)
将窗体置底： b(I)
删除一个窗体：d(I)
输出窗体可见部分的百分比：s(I)
</pre>
<p>I 是每个窗体唯一的标识符，标识符可以是 'a'..'z', 'A'..'Z' 和 '0'..'9' 中的任何一个。输入文件中没有多余的空格。</p>
<p>（x,y）和（X,Y）是窗体的对角。当你创建一个窗体的时候，它自动被“置顶”。你不能用已经存在的标识符来创建窗体，但是你可以删除一个窗体后再用已删除窗体的标识符来创建窗体。坐标用正整数来表示，并且所有的窗体面积都不为 0（x &lt;&gt; X 且 y &lt;&gt; Y）。x 坐标和 y 坐标在 1 —— 32767 的范围内。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入文件包含给你的解释程序的一系列命令，每行一个。当输入文件结束时，停止程序。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>只对于 s() 命令进行输出。当然，输入文件可能有许多 s() 命令(不超过500次)，所以输出文件应该是一个百分比的序列，每行一个，百分比是窗体可见部分的百分比。百分比应该四舍五入到三位小数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>w(a,10,132,20,12)
w(b,8,76,124,15)
s(a)</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>49.167</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见描述</p>
</div>
</div>