
# Description

<div class="content"><p>有一座三角形的山，三个顶点分别为(0,0),(w,0),(w,h) (w &gt; h)，我们需要挖管道，使得(0,0)-&gt;(w,0)这条水平线与(w,h)-&gt;(w,0)这条垂直线被挖通，挖的土需要通过所挖的管道运送出来。为了方便这个过程我们可以多挖n个辅助管道，我们需要选择n个x轴上的坐标ai，挖通三角形斜边上对应点到(ai,0)这条垂直线，挖这些管道所产生的土也需要运送出来(运送到山的表面，即斜边上或是(0,0)处)，而这些管道也能用来运送土。现在假设管道的宽度可以忽略不记，求最优的坐标选择方案，使得将土运送出来的代价和最小。</p></div>

# Input

<div class="content"><p>第一行三个整数w,h(w&gt;h),n。表示山的水平宽与垂直高，以及辅助管道个数。</p></div>

# Output

<div class="content"><p>第一行一个实数表示最小代价和。接下来n行按x坐标从小到大输出选择的管道x坐标，n&gt;10则输出前10个即可。<br/>
答案保留9位小数。数据保证没有两个管道的x坐标差值小于0.001</p></div>

# Sample Input

<div class="content"><span class="sampledata">输入1<br/>
8 4 1<br/>
<br/>
输入2<br/>
195 65 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">输出<br/>
31.500000000<br/>
3.000000000<br/>
<br/>
输出2<br/>
12220.000000000<br/>
48.000000000<br/>
108.000000000</span></div>

# Hint

<div class="content"><p></p><p>【数据范围】<br/><br/>
1 &lt;= w &lt;= 10000, 1 &lt;= n &lt;= 1000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢GyWXwshMy提供译文及数据">鸣谢GyWXwshMy提供译文及数据</a></p></div>

