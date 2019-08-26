
# Description

<div class="content"><div><span style="font-size: medium">如果满足下面条件我们称这个立方体是规则的: </span></div>
<ul type="disc">
    <li><span style="font-size: medium">它的顶点中的一个是坐标为(0,0,0)的点， </span></li>
    <li><span style="font-size: medium">开始于这个顶点的位于坐标系统的正半轴， </span></li>
    <li><span style="font-size: medium">边不长于10<sup>6</sup> </span></li>
</ul>
<div><span style="font-size: medium">有一个给定的空间点的集合A，坐标为间隔为[1..10<sup>6</sup>]的整数。我们试着找出最大体积的规则立方体，它不包括集合A的任何点。如果一个点属于一个立方体之内，那么这个点属于这个立方体，它是这个立方体的点，但它的墙不是。</span></div>
<div style="margin: auto 0cm"><span style="font-size: medium"><b>任务</b></span></div>
<div><span style="font-size: medium">写一个程序: </span></div>
<ul type="disc">
    <li><span style="font-size: medium">读取来自集合A的点的坐标， </span></li>
    <li><span style="font-size: medium">找出一个最大体积的规则立方体，它不包括来自集合A的任何点， </span></li>
    <li><span style="font-size: medium">把结果输出 </span></li>
</ul></div>

# Input

<div class="content"><div style="margin: auto 0cm"><span style="font-size: medium">首行，一个非零的整数n被写出来（<i>n</i> &lt;= <i>5000</i>）。它是集合A的元素数。在文件PUS.IN接下来的n行中有三个一组的整数，其范围在[1..10<sup>6</sup>]，它们是来自集合A的点的坐标（分别为x，y，z）。每一行的数字被单空格号隔开。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">一行应该有三个被单空格号分隔的整数。这些是最大体积的规则立方体的顶点的坐标（分别为x，y，z）。我们要求坐标为正数。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
3 3 300000<br/>
2 200000 5<br/>
90000 3 2000<br/>
2 2 1000<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> <br/>
1000000 200000 1000<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

