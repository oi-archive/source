# 题目描述


<div>
USACO/window(译 by Felicia Crazy)
<hr/>
</div>
<p>
描述
</p>
<p>
 
</p>
<p>
你刚刚接手一项窗体界面工程。窗体界面还算简单，而且幸运的是，你不必显示实际的窗体。有 <span style="font-family:&#39;Times New Roman&#39;;">5 </span>种基本操作：
</p>
<ol>
<li>
创建一个新窗体
</li>
<li>
将窗体置顶
</li>
<li>
将窗体置底
</li>
<li>
删除一个窗体
</li>
<li>
输出窗体可见部分的百分比（就是，不被其它窗体覆盖的部分）。
</li>
</ol>
<p>
在输入文件中，操作以如下的格式出现。
</p>
<ul>
<li>
创建一个新窗体：<span style="font-family:&#39;Times New Roman&#39;;">w(I,x,y,X,Y)</span> 
</li>
<li>
将窗体置顶： <span style="font-family:&#39;Times New Roman&#39;;">t(I)</span> 
</li>
<li>
将窗体置底： <span style="font-family:&#39;Times New Roman&#39;;">b(I)</span> 
</li>
<li>
删除一个窗体：<span style="font-family:&#39;Times New Roman&#39;;">d(I)</span> 
</li>
<li>
输出窗体可见部分的百分比：<span style="font-family:&#39;Times New Roman&#39;;">s(I)</span> 
</li>
</ul>
<span style="font-family:&#39;Times New Roman&#39;;">I </span>是每个窗体唯一的标识符。表示符可以是 <span style="font-family:&#39;Times New Roman&#39;;">&#39;a&#39;..&#39;z&#39;, &#39;A&#39;..&#39;Z&#39; </span>和 <span style="font-family:&#39;Times New Roman&#39;;">&#39;0&#39;..&#39;9&#39; </span>中的任何一个。输入文件中没有多余的空格。
<p>
（<span style="font-family:&#39;Times New Roman&#39;;">x,y</span>）和（<span style="font-family:&#39;Times New Roman&#39;;">X,Y</span>）是窗体的对角。当你创建一个窗体的时候，它自动被<span style="font-family:&#39;Times New Roman&#39;;">“</span>置顶<span style="font-family:&#39;Times New Roman&#39;;">”</span>。你不能用已经存在的标识符来创建窗体，但是你可以删除一个窗体后再用已删除窗体的标识符来创建窗体。坐标用正整数来表示，并且所有的窗体面积都不为 <span style="font-family:&#39;Times New Roman&#39;;">0</span>（<span style="font-family:&#39;Times New Roman&#39;;">x &lt;&gt; X </span>且 <span style="font-family:&#39;Times New Roman&#39;;">y &lt;&gt; Y</span>）。<span style="font-family:&#39;Times New Roman&#39;;">x </span>坐标和 <span style="font-family:&#39;Times New Roman&#39;;">y </span>坐标在 <span style="font-family:&#39;Times New Roman&#39;;">1 —— 32767 </span>的范围内。
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">PROGRAM NAME: windowus</span> 
</h3>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">INPUT FORMAT(file windowus.in)</span> 
</h3>
<p>
输入文件包含给你的解释程序的一系列命令，每行一个。当输入文件结束时，停止程序。
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">OUTPUT FORMAT(file windowus.out)</span> 
</h3>
<p>
只对于 <span style="font-family:&#39;Times New Roman&#39;;">s() </span>命令进行输出。当然，输入文件可能有许多 <span style="font-family:&#39;Times New Roman&#39;;">s() </span>命令，所以输出文件应该是一个百分比的序列，每行一个，百分比是窗体可见部分的百分比。百分比应该四舍五入到三位小数。
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE INPUT (file windowus.in)</span> 
</h3>
<pre><span style="font-family:&#39;Times New Roman&#39;;">w(a,10,132,20,12)
w(b,8,76,124,15)
s(a)</span></pre>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE OUTPUT (file windowus.out)</span> 
</h3>
<pre><span style="font-family:&#39;Times New Roman&#39;;">49.167</span></pre>
<p>
 
</p>
<p>
<br/>
</p>
