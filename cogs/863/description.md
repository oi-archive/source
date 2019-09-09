# 题目描述


<p>
USACO/spin(译 by Felicia Crazy)
</p>
<p>
描述
</p>
<div>
<div>
<div>
<p>
<span lang="EN-US"> </span> 
</p>
<p>
一架纺车有五个纺轮，这五个不透明的轮子边缘上都有一些缺口。这些缺口必须被迅速而准确地排列好。每个轮子都有一个起始标记（在<span style="font-family:&#39;Times New Roman&#39;;">0</span>度），这样所有的轮子都可以在统一的已知位置开始转动。轮子按照角度变大的方向旋转（即0经过旋转到达1的位置），所以从起始位置开始，在一定的时间内，它们依次转过1度，2度等等（虽然这些轮子很可能不会同时转过这些角度）。
</p>
<p>
这是一个整数问题。轮子不会转过<span style="font-family:&#39;Times New Roman&#39;;">1.5</span>度或<span style="font-family:&#39;Times New Roman&#39;;">23.51234123</span>度这样的角度。例如，轮子可能在一秒钟内转过<span style="font-family:&#39;Times New Roman&#39;;">20</span>到<span style="font-family:&#39;Times New Roman&#39;;">25</span>度甚至<span style="font-family:&#39;Times New Roman&#39;;">30</span>到<span style="font-family:&#39;Times New Roman&#39;;">40</span>度（如果转得快的话）。
</p>
<p>
这个问题中的所有角度都限制在 <span style="font-family:&#39;Times New Roman&#39;;">0 &lt;= </span>角度 <span style="font-family:&#39;Times New Roman&#39;;">&lt;= 359 </span>这个范围内。轮子转过 <span style="font-family:&#39;Times New Roman&#39;;">359 </span>度后接下来就是 <span style="font-family:&#39;Times New Roman&#39;;">0 </span>度。每个轮子都有一个确定的旋转速度，以角度/秒作为单位。<span style="font-family:&#39;Times New Roman&#39;;">1 &lt;= </span>速度 <span style="font-family:&#39;Times New Roman&#39;;">&lt;= 180</span>。
</p>
<p>
轮子上的缺口的起始角度和缺口大小（或长度）各由一个整数表示，都以度为单位。在一个轮子上，两个缺口之间至少有一度的间隔。
</p>
<p>
在起始位置，设时间为 <span style="font-family:&#39;Times New Roman&#39;;">0</span>，所有的轮子的起始标记排列成一条直线。你的程序必须计算，最早出现每个的轮子上的缺口同其他轮子上的缺口对准（也就是一束光可以通过五个轮子上的五个缺口）情况的时间。这些缺口在任意一个角度对准。
</p>
<span style="font-family:SimSun;"></span> 
<p>
<br/>
</p>
</div>
<div>
 
</div>
<div>
</div>
<div>
格式
</div>
<div>
PROGRAM NAME: spin
</div>
<div>
INPUT FORMAT:(file spin.in)
</div>
<div>
</div>
<div>
<p class="MsoNormal">
<span style="font-family:SimSun;"> </span> 
</p>
<p>
输入中的五行对应五个轮子。
</p>
<p>
第一个数字表示轮子的转动速度。下一个数字是缺口的数目 <span style="font-family:&#39;Times New Roman&#39;;">W</span>。<span style="font-family:&#39;Times New Roman&#39;;">1 &lt;= W &lt;= 5</span>。接下来的 <span style="font-family:&#39;Times New Roman&#39;;">W </span>对数字表示每个缺口的起始角度和长度。
</p>
<p>
<br/>
</p>
 
</div>
<div>
OUTPUT FORMAT:(file spin.out)
</div>
<div>
<p>
<br/>
</p>
<p class="MsoNormal">
<span style="font-family:SimSun;"> </span> 
</p>
<p>
只有一行，包括一个整数，表示光能够通过这五个轮子的最早时间。如果无解，输出&#39;none&#39;（小写，不含引号）。
</p>
<span style="font-family:SimSun;"></span> 
<p>
<br/>
</p>
<p>
 
</p>
<p>
SAMPLE INPUT
</p>
</div>
<div>
<div>
(file spin.in)
</div>
</div>
<pre>30 1 0 120
50 1 150 90
60 1 60 90
70 1 180 180
90 1 180 60
</pre>
<div>
 
</div>
<div>
SAMPLE OUTPUT
<div>
(file spin.out)
</div>
<div>
9
</div>
<div>
 
</div>
</div>
</div>
</div>
<p>
 
</p>
