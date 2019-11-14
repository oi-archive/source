
# Description

<div class="content"><p><span style="font-size: medium">Bessie and the rest of Farmer John&#39;s cows are taking a trip this winter to go skiing. One day Bessie finds herself at the top left corner of an R (1 &lt;= R &lt;= 100) by C (1 &lt;= C &lt;= 100) grid of elevations E (-25 &lt;= E &lt;= 25). In order to join FJ and the other cows at a discow party, she must get down to the bottom right corner as quickly as she can by travelling only north, south, east, and west. Bessie starts out travelling at a initial speed V (1 &lt;= V &lt;= 1,000,000). She has discovered a remarkable relationship between her speed and her elevation change. When Bessie moves from a location of height A to an adjacent location of height B, her speed is multiplied by the number 2^(A-B). The time it takes Bessie to travel from a location to an adjacent location is the reciprocal of her speed when she is at the first location. Find the both smallest amount of time it will take Bessie to join her cow friends and the number of moves required by the path (a move is a transition from one location to another adjacent location). </span></p>
<div><span style="font-size: medium">    贝茜和其他一些人去滑雪．贝茜发现她自己站在一块R x C(1≤R，C≤100)的区域中，区域中的每一块都有一个高度值Ei,j．为了参加大家的聚会，贝茜想要尽快到达右下角．</span><span style="font-size: medium"> 贝茜每一步只能向正东，正西，正南，正北前进一步．贝茜以初速度V(I≤y≤106)前</span><span style="font-size: medium">进，她发现了一个她的速度和高度的关系．当贝茜从高度n移动到高度b，她的速度就乘上了一个数2^(a-b)．贝茜移动一步的速度取决于她在前一格时的速度．</span></div>
<div><span style="font-size: medium">    请找出贝茜移动所需的最小时间．</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Three space-separated integers: V, R, and C, which respectively represent Bessie&#39;s initial velocity and the number of rows and columns in the grid. </span></p>
<p><span style="font-size: medium">* Lines 2..R+1: C integers representing the elevation E of the corresponding location on the grid. </span></p>
<div><span style="font-size: medium">    第1行：3个用空格隔开的整数V，R，C，分别表示贝茜的初速度和区域的长度和宽度．</span></div>
<div><span style="font-size: medium">    第2到R+1行：以矩阵的形式表示该区域中各块的高度．</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">A single number value, printed to two exactly decimal places: the minimum amount of time that Bessie can take to reach the bottom right corner of the grid. </span></p>
<div><span style="font-size: medium">    输出一个实数（保留2位小数），表示贝茜达到目的地最少需要的时间．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">1 3 3  //奶牛开始在左上角，速度为1,它可以移动到别的格子上，速度会发生变化<br/>
1 5 3 //这个3*3的数矩阵代表每个格子的参数，当从一个格子A到B时，速度变成V*2^(A-B)<br/>
6 3 5<br/>
2 4 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">29.00<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
Bessie&#39;s best route is:<br/>
	Start at 1,1 time  0 speed 1<br/>
	East  to 1,2 time  1 speed 1/16<br/>
	South to 2,2 time 17 speed 1/4<br/>
	South to 3,2 time 21 speed 1/8<br/>
	East  to 3,3 time 29 speed 1/4<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

