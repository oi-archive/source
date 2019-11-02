<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一架纺车有五个纺轮（也就是五个同心圆），这五个不透明的轮子边缘上都有一些缺口。这些缺口必须被迅速而准确地排列好。每个轮子都有一个起始标记（在0度），这样所有的轮子都可以在统一的已知位置开始转动。轮子按照角度变大的方向旋转（即0经过旋转到达1的位置），所以从起始位置开始，在一定的时间内，它们依次转过1度，2度等等（虽然这些轮子很可能不会同时转过这些角度）。</p>
<p>这是一个整数问题。轮子不会转过1.5度或23.51234123度这样的角度。例如，轮子可能在一秒钟内转过20到25度甚至30到40度（如果转得快的话）。</p>
<p>这个问题中的所有角度都限制在 0 &lt;= 角度 &lt;= 359 这个范围内。轮子转过 359 度后接下来就是 0 度。每个轮子都有一个确定的旋转速度，以秒作为单位。1 &lt;= 速度 &lt;= 180。</p>
<p>轮子上的缺口的起始角度和缺口大小（或长度）各由一个整数表示，都以度为单位。在一个轮子上，两个缺口之间至少有一度的间隔。长度也包含缺口起始的角度，即0 180包括0..180共计181个角度，比一般人想象的多一个。</p>
<p>在起始位置，设时间为 0，所有的轮子的起始标记排列成一条直线。你的程序必须计算，最早出现每个的轮子上的缺口同其他轮子上的缺口对准（也就是一束光可以通过五个轮子上的五个缺口）情况的时间。这些缺口在任意一个角度对准。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入中的五行对应五个轮子。</p>
<p>第一个数字表示轮子的转动速度。下一个数字是缺口的数目 W。1 &lt;= W &lt;= 5。接下来的 W 对数字表示每个缺口的起始角度和长度。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>只有一行，包括一个整数，表示光能够通过这五个轮子的最早时间。如果无解，输出'none'（小写，不含引号）。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>30 1 0 120
50 1 150 90
60 1 60 90
70 1 180 180
90 1 180 60</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>9</pre>

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