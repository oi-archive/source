
# Description

<div class="content"><div>这是一枚平凡的骰子。它是一个均质凸多面体，表面有n个端点，有f个面，每一面是一个凸多边形，且任意两面不</div>
<div>共面。将这枚骰子抛向空中，骰子落地的时候不会发生二次弹跳（这是一种非常理想的情况）。你希望知道最终每</div>
<div>一面着地的概率。每一面着地的概率可以用如下的方法计算：我们假设O为骰子的重心，并以O为球心，做半径为1</div>
<div>的单位球面（记为S）。我们知道S的表面积即单位球的表面积，为4*pi，这里pi为圆周率。对于骰子的某一面C来</div>
<div>说，球面S上存在一块区域T满足：当下落时若骰子所受重力方向与S的交点落在T中，则C就是最终着地的一面。那</div>
<div>么C着地的概率为区域T的面积除以4*pi。为了能更好地辅助计算球面上一块区域的面积，我们给出单位球面S上三</div>
<div>角形的面积计算公式。考虑单位球面S上的三个两两相交的大圆，交点依次为A，B和C。则曲面三角形ABC的面积为A</div>
<div>rea(ABC)=alpha+beta+gamma-pi，其中alpha，beta和gamma分别对应了三个二面角的大小。如下图所示。</div>
<div> </div>
<div>我们保证：每一面着地的时候，重心的垂心都恰好在这一面内。也就是说不会出现摆不稳的情况。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行输入两个整数，分别表示端点总数n与表面总数f，分别从1开始编号。之后n行，每行有三个浮点数x，y和z</div>
<div>，给出了每一个端点的坐标。之后f行依次描述了每一块表面，首先给出不小于3的整数d，表示这一面的端点个数</div>
<div>，之后d个整数按照逆时针方向（视角在骰子的外面）给出了每一个端点的编号。</div>
<div>4&lt;=n&lt;=50且4&lt;=m&lt;=50，所有坐标的绝对值都在10000以内</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出f行，第i行有一个浮点数，表示第i个面着地的概率。本题中您的输出应该保留距离答案最近的7位小数，即在</div>
<div>需要保留7位小数的前提之下与标准答案最接近。数据保证可以避免对小数点后第八位四舍五入后产生的精度误差</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">8 6<br/>
1 0 0<br/>
1 1 0<br/>
1 0 1<br/>
1 1 1<br/>
0 0 0<br/>
0 1 0<br/>
0 0 1<br/>
0 1 1<br/>
4 1 2 4 3<br/>
4 2 6 8 4<br/>
4 6 5 7 8<br/>
4 5 1 3 7<br/>
4 3 4 8 7<br/>
4 1 5 6 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.1666667<br/>
0.1666667<br/>
0.1666667<br/>
0.1666667<br/>
0.1666667<br/>
0.1666667</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By AHdoc命题 鸣谢Loi_DQS上传">By AHdoc命题 鸣谢Loi_DQS上传</a></p></div>

