
# Description

<div class="content"><div>这只是一时的狂热还是将长久地持续下去？你并不能肯定，不过在你家乡数目持续增长的咖啡馆着实成了一种风尚。显然，人们对于咖啡是如此地着迷以至于那些靠近更多咖啡馆的公寓需要更多的租金。</div>
<div>这引起了当地一家房地产公司的注意。他们对于根据靠近大量咖啡馆来确定城市当中最有价值的区域很感兴趣。他们给你了城市地图，标记了咖啡馆的位置。假定老百姓们只会为了早点走过一定数目的街区，你需要找到能到达最多咖啡馆的位置。就像你可能知道的那样，你的家乡是按照方格网的布局设计建造的，所以街区之间按南北和东西轴线对齐。(a,b)和(c,d)两个交叉口之间的距离是|a-c|+|b-d|。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>测试数据的第一行包含四个整数dx,dy,n和q。它们分别代表城市网格的面积为dx*dy，咖啡馆的数量n，以及询问个数q。接下来的n行每行包含两个整数xi和yi；它们说明了第i个咖啡馆的位置。每个十字路口最多只有一个咖啡馆。接下来的q行每行包含了一个整数m，表示人们为了咖啡会走过的最长距离。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于测试数据的每个询问输出一行。每行输出在给定的距离m以内可以抵达咖啡馆的最大数目，紧跟着输出最佳位置。比如说样例输出说明了从最佳位置(3,4)出发，在询问要求的1的距离范围内可以抵达3个咖啡馆。如果存在多个最佳位置，选择最南边的那个（也就是y坐标最小的），如果任然多解，选择最西边的那个（也就是x坐标最小的）。</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 5 3<br/>
1 1<br/>
1 2<br/>
3 3<br/>
4 4<br/>
2 4<br/>
1<br/>
2<br/>
4<br/>
0 0 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1:<br/>
3 (3,4)<br/>
4 (2,2)<br/>
5 (3,1)</span></div>

# Hint

<div class="content"><p></p><p>0≤n≤500000,1≤dx,dy≤1000,1≤q≤20,1≤xi≤dx,1≤yi≤dy,1≤m≤1000000</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

