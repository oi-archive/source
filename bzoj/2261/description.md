
# Description

<div class="content"><p><font face="Times New Roman" size="3">激光是能量高度聚集的一种电磁波。激光的强度可以用每秒经过的量子数来衡量。 <br/>
尹教授研究室有一套超高能量激光产生器。说明书上写着：对于任何一个正整数 k，它都会产生强度&gt;k的激光。 <br/>
<br/>
然而尹教授对这个限制表示十分不满，于是开发了一个强度调节装置。 <br/>
该装置由 n 个端口和 m 个通道构成。端口从 1 到 n 编号。 <br/>
每个通道连接两个端口，且有各自的内部能量流动上限。(用每秒经过的量子数来衡量)可能有多条通道连接两端口。 <br/>
<br/>
使用时，可以选择某一个端口作为能量输入端，输入超高能量的激光，再选择另一个端口作为输出端。 <br/>
激光在此装置中可能被任意分散和汇聚，由于是超高强度激光，能量在流动时一定会尽量充满通道上限。 <br/>
<br/>
尹教授想知道，通过切换不同的输入和输出端，整个系统可以输出哪些正整数强度的激光。 <br/>
<br/>
<br/>
</font></p>
<p></p></div>

# Input

<div class="content"><p><font face="Times New Roman" size="3">第一行: n m 分别表示端口和通道的总数 <br/>
接下来 m 行: x y z 表示从 x 端口到 y 端口有一个上限为 z 的通道。 <br/>
<br/>
<br/>
</font></p>
<p></p></div>

# Output

<div class="content"><p><font face="Times New Roman" size="3">从小到大输出所有可行的激光强度。 <br/>
用换行符隔开。 <br/>
</font></p>
<p></p><p></p>
<pre></pre>
<p></p>
<pre>	</pre></div>

# Sample Input

<div class="content"><span class="sampledata">3 3                                          <br/>
1 2 1                                        <br/>
1 3 2                                        <br/>
2 3 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
<br/>
3<br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p><p></p><br/>
<p>对于全部的数据： 2≤n≤200 上限均不超过 50000，单个输入文件不超过1MB</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

