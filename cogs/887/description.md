# 题目描述


<p>
USACO/job(<b><b>译 <span style="font-family:&#39;Times New Roman&#39;;">by Felicia Crazy)</span></b></b><span id=".E6.8F.8F.E8.BF.B0" class="mw-headline"></span> 
</p>
<p>
<span class="mw-headline">描述</span> 
</p>
<p>
<br/>
</p>
<p>
一家工厂的流水线正在生产一种产品，这需要两种操作：操作<span style="font-family:&#39;Times New Roman&#39;;">A</span>和操作<span style="font-family:&#39;Times New Roman&#39;;">B</span>。每个操作只有一些机器能够完成。
</p>
<p>
<br/>
</p>
<center>
<p>
<img alt="" src="/images/upload/image/20120711/20120711152929_54212.gif"/> 
</p>
</center>
上图显示了按照下述方式工作的流水线的组织形式。<span style="font-family:&#39;Times New Roman&#39;;">A</span>型机器从输入库接受工件，对其施加操作<span style="font-family:&#39;Times New Roman&#39;;">A</span>，得到的中间产品存放在缓冲库。<span style="font-family:&#39;Times New Roman&#39;;">B</span>型机器从缓冲库接受中间产品，对其施加操作<span style="font-family:&#39;Times New Roman&#39;;">B</span>，得到的最终产品存放在输出库。所有的机器平行并且独立地工作，每个库的容量没有限制。每台机器的工作效率可能不同，一台机器完成一次操作需要一定的时间。
<p>
给出每台机器完成一次操作的时间，计算完成<span style="font-family:&#39;Times New Roman&#39;;">A</span>操作的时间总和的最小值，和完成<span style="font-family:&#39;Times New Roman&#39;;">B</span>操作的时间总和的最小值。
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">PROGRAM NAME: jobus</span> 
</h3>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">INPUT FORMAT(file jobus.in)</span> 
</h3>
<table border="1">
<tbody>
<tr>
<td>
<div align="center">
第一行
</div>
</td>
<td>
三个用空格分开的整数：
<ul>
<li>
<span style="font-family:&#39;Times New Roman&#39;;">N</span>，工件数量 <span style="font-family:&#39;Times New Roman&#39;;">(1&lt;=N&lt;=1000)</span>。
</li>
<li>
<span style="font-family:&#39;Times New Roman&#39;;">M1</span>，<span style="font-family:&#39;Times New Roman&#39;;">A</span>型机器的数量 <span style="font-family:&#39;Times New Roman&#39;;">(1&lt;=M1&lt;=30)</span>。
</li>
<li>
<span style="font-family:&#39;Times New Roman&#39;;">M2</span>，<span style="font-family:&#39;Times New Roman&#39;;">B</span>型机器的数量 <span style="font-family:&#39;Times New Roman&#39;;">(1&lt;=M2&lt;=30)</span>。
</li>
</ul>
</td>
</tr>
<tr>
<td>
<div align="center">
第二行<span style="font-family:&#39;Times New Roman&#39;;">…</span>等
</div>
</td>
<td>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">M1</span>个整数（表示<span style="font-family:&#39;Times New Roman&#39;;">A</span>型机器完成一次操作的时间，<span style="font-family:&#39;Times New Roman&#39;;">1..20</span>），接着是<span style="font-family:&#39;Times New Roman&#39;;">M2</span>个整数（<span style="font-family:&#39;Times New Roman&#39;;">B</span>型机器完成一次操作的时间，<span style="font-family:&#39;Times New Roman&#39;;">1..20</span>）
</p>
</td>
</tr>
</tbody>
</table>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">OUTPUT FORMAT(file jobus.out)</span> 
</h3>
<p>
只有一行。输出两个整数：完成所有<span style="font-family:&#39;Times New Roman&#39;;">A</span>操作的时间总和的最小值，和完成所有<span style="font-family:&#39;Times New Roman&#39;;">B</span>操作的时间总和的最小值（<span style="font-family:&#39;Times New Roman&#39;;">A</span>操作必须在<span style="font-family:&#39;Times New Roman&#39;;">B</span>操作之前完成）。
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE INPUT (file jobus.in)</span> 
</h3>
<pre><span style="font-family:&#39;Times New Roman&#39;;">5 2 3
1 1 3 1 4 </span></pre>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE OUTPUT (file jobus.out)</span> 
</h3>
<pre><span style="font-family:&#39;Times New Roman&#39;;">3 5</span></pre>
<p align="left">
 
</p>
<p>
 
</p>
