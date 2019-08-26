
# Description

<div class="content">A和B玩一个游戏:A出一个凸多边形,B会用一条直线将其分成两部分.如果它们的
面积差不超过一个数Delta,B会保留这个凸多边形,否则B会去除面积较小的一部分每次游戏前B会给出N条直线,问A应该用怎么样顺序用这N条直线割凸多边形,使得剩下的图形面积最大.注意如果直线和凸多边形不相交,则B会保留这个凸多边形.

</div>

# Input

<div class="content">第一行输入一个正整数 k，表示初始时多边形的顶点数。 
以下k 行按逆时针顺序给出多边形的顶点坐标Xi,Yi。 
第 k+2行输入一个正整数n，表示直线的数目。 
以下n 行，每行4 个整数Xi1, Yi1, Xi2, Yi2，表示直线上的不重合两点的坐标。 
最后一行输入一个小于 10000 的非负实数 delta。 
输入数据保证所有给出的坐标值都是绝对值不超过 500的整数 
</div>

# Output

<div class="content">一个实数，表示最大可能得到的面积，保留5 位小数。 
</div>

# Sample Input

<div class="content"><span class="sampledata">4 <br/>
-100 -100 <br/>
100 -100 <br/>
100 100 <br/>
-100 100 <br/>
1 <br/>
-1 0 1 0 <br/>
0 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">40000.00000 <br/>
 <br/>
精度取1e-8足够 <br/>
每组输入数据中的点保证无3 点共线 <br/>
 <br/>
</span></div>

# Hint

<div class="content"><p>对于 50%的数据 n&lt;=8 <br/>
对于 100%的数据 n&lt;=9,k&lt;=20 <br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

