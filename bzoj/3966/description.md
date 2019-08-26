
# Description

<div class="content"><div>Allied Chute公司是一个建造垃圾管道的公司。垃圾管道建造在楼房中，垃圾从顶部进入，顺着管道与地下室连接。建造垃圾管道是一个高水平的工作。根据人们丢入不同种类的垃圾，垃圾管道需要有一个适当的尺寸。并且由于制作垃圾管道的费用正比于它的尺寸，公司总是想要建造尽可能的管道，尽管确定合适的尺寸十分困难。</div>
<div>为了简化这个问题，我们考虑一个二维的空间。垃圾管道是一个有着固定宽度、垂直下降的槽。物体可以看作一个多边形的模型。在物体落入管道之前它可以旋转来达到和管道最佳拟合。当它下落时，它会垂直落下并且不再旋转。下图展示了一个垃圾是怎样旋转来符合管道的。</div>
<div>你的任务是计算让一个给定的多边形物体通过的最小管道宽度。</div>
<div><img src="source/bzoj/3966/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNC82Ni5ibXA=.bmp" width="558" height="379" alt=""/></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入包含多组数据。每组数据开始于一个数字n,代表垃圾的模型—一个多边形的顶点数。</div>
<div>接下来n行每行一对整数xi和yi，按顺序给出多边形的顶点。</div>
<div>最后以一个0表示结束</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每组测试数据，输出数据编号以 及物体能够穿过垃圾管道并落下的最小宽度。输出的最小宽度并 向上舍入到最接近1/100倍数的数 ，你的答案与标准答案误差不能超过1/100。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
0 0<br/>
3 0<br/>
0 4<br/>
4<br/>
0 10<br/>
10 0<br/>
20 10<br/>
10 20<br/>
0</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 2.40<br/>
Case 2: 14.15</span></div>

# Hint

<div class="content"><p></p><div>100%的数据3&lt;=n&lt;=100</div><br/>
<div>0&lt;=xi,yi&lt;=10^4</div><br/>
<div>保证在一组数据中的所有的点互不不同，并且多边形的边不会相交（技术上，两条相邻的边不可避免的会有一个公共顶点，当然，这种情况我们不认为是相交）。</div><br/>
<div>请不要提交，尚无SPJ</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

