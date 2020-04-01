
# Description

<div class="content"><p>一个坐落在北极冰冻湖面上的渔村因全球变暖而面临危险——湖面开始破碎。村庄内有n座球形冰屋，每座冰屋在湖面上占据了一块圆形区域。<br/>
一座冰屋可以视为平面座标系中的一个圆：其圆心座标为整数，其半径为小于1的一位浮点数。给出冰面断裂的座标，这些村民希望知道每次断裂会有多少个冰屋受到影响。<br/>
形式上，给出q个询问，每个询问包括一条由两个端点确定的线段，查询每条线段贯穿的冰屋数。如果线段与圆的内部有至少一个交点，则线段贯穿了这座冰屋。</p></div>

# Input

<div class="content"><p>第一行包括一个整数n(1&lt;=n&lt;=100 000)——冰屋数。<br/>
接下来的n行每行包括三个数x，y和r——冰屋的座标和半径。x和y为整数且1&lt;=x,y&lt;=500。r是一位浮点数且0&lt;r&lt;1。冰屋之间不存在重叠或接触。<br/>
你可以认为，对于任一冰屋i和线段s 的距离的平方小于r2-10-5或大于r2+10-5。</p></div>

# Output

<div class="content"><p>输出包括q行。第k行包括一个整数——被第k条线段穿过的冰屋数</p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
4 2 0.6<br/>
7 3 0.7<br/>
8 5 0.8<br/>
1 3 0.7<br/>
3 4 0.4<br/>
2<br/>
3 1 9 6<br/>
3 4 7 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

