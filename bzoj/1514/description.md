
# Description

<div class="content">Task: Frogs
一群青蛙正在摧毁Byteotia所有的庄稼. 一个叫Byteasar的农夫决定使用一种放在田里的奇特的&#34;scarefrogs&#34;来吓跑他们, 所有的青蛙在跳跃过程中都尽量使自己离他们越远越好, 即是让自己离最近的scarefrog越远越好. 
Byteasar的田是块矩形的土地. 青蛙们跳跃的方向平行于坐标轴并且每次跳跃的距离为1. 一条跳跃路线的scarefrogs-距离为路径上所有点距离所有scarefrogs的最近距离. 
Byteasar已经知道青蛙们的出发位置和目的地位置, 所以他在田里放置了若干个scarefrogs. 他请求你帮忙写一个程序找一条路径使得该路径的scarefrogs-距离最大. 
</div>

# Input

<div class="content">第一行包含两个整数: wx 和 wy 分别表示田地的宽和长( 2 &lt;= wx, wy&lt;=  1 000). 第二行包含四个整数: px, py, kx 和 ky 其中 (px, py) 为青蛙的起始位置, (kx, ky) 为目的地位置( 1 &lt;= px, kx &lt;= wx, 1&lt;=  py, ky&lt;=  wy). 第三行一个整数 n – 表示scarefrogs的总数( 1&lt;=  n&lt;=  wx . wy). 接下来n 行描述所有scarefrogs的坐标. 坐标用xi 和 yi 来描述第ith个 scarefrog的位置 ( 1 &lt;= xi&lt;=  wx, 1&lt;=  yi&lt;=  wy). 没有两个scarefrogs在同一个位置出现并且不会出现在(px, py) nor (kx, ky)上. 
</div>

# Output

<div class="content">一个整数代表目标路径scarefrog距离的平方. 如果青蛙不可避免遇到某些scarefrog那么答案为0. 
</div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
1 1 5 5<br/>
2<br/>
3 3<br/>
4 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
<br/>
</span></div>

# Hint

<div class="content"><p><img border="0" src="/source/bzoj/1514/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE1MTQuanBn.jpg"/><br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

