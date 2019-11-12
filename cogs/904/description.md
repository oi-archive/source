# 题目描述


<div>
USACO/fence3(译 by Felicia Crazy)
<hr/>
</div>
<p>
描述
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">农夫约翰已经决定建造电网。他已经把他的农田围成一些奇怪的形状，现在必须找出安放电源的最佳位置。 </span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">对于段电网都必须从电源拉出一条电线。电线可以穿过其他电网或者跨过其他电线。电线能够以任意角度铺设，从电源连接到一段电网的任意一点上（也就是，这段电网的端点上或者在其之间的任意一点上）。这里所说的“一段电网”指的是呈一条线段状的电网，并不是连在一起的几段电网。若几段电网连在一起，那么也要分别给这些电网提供电力。 </span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">已知所有的 F（1 &lt;= F &lt;= 150）段电网的位置（电网总是和坐标轴平行，并且端点的坐标总是整数，0 &lt;= X,Y &lt;= 100）。你的程序要计算连接电源和每段电网所需的电线的最小总长度，还有电源的最佳坐标。 </span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">电源的最佳坐标可能在农夫约翰的农田中的任何一个位置，并不一是整数。</span> 
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">PROGRAM NAME: fence3 </span> 
</h3>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">INPUT FORMAT  (file fence3.in)</span> 
</h3>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">第一行包括 F ——电网的数量。 <br/>
下面的 F 行每行包括两个 X，Y 对，表示这段电网的两个端点。</span> 
</p>
<h3>
OUTPUT FORMAT(file fence3.out)
</h3>
<p>
只有一行，输出三个浮点数，每个保留一位小数，相邻两个之间留一个空格。假定你的电脑的输出库会正确地对小数进行四舍五入。
</p>
<p>
这三个数是：
</p>
<ul>
<li>
<span style="font-family:&#39;Times New Roman&#39;;">电源最佳坐标的 X 值， </span> 
</li>
<li>
<span style="font-family:&#39;Times New Roman&#39;;">电源最佳坐标的 Y 值，和 </span> 
</li>
<li>
<span style="font-family:&#39;Times New Roman&#39;;">需要的电线的总长度（要最小）。 </span> 
</li>
</ul>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE INPUT (file fence3.in) </span> 
</h3>
<span style="font-family:宋体;">3 <br/>
0 0 0 1 <br/>
2 0 2 1 <br/>
0 3 2 3 </span> 
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE OUTPUT (file fence3.out) </span> 
</h3>
<span style="font-family:宋体;">1.0 1.6 3.7 </span> 
<p>
 
</p>
