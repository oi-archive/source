
# Description

<div class="content"><div>JYY最近迷上了一款塔防游戏，在游戏里JYY除了建设建筑，还可以使用炸弹对屏幕上的敌人进行范围杀伤。</div>
<div>【问题描述】</div>
<div>游戏地图可以简单认为是一个2维平面。JYY建造了N个建筑，每个建筑都是一个圆，其中第i个建筑的圆心位于(xi,</div>
<div>yi)且半径为ri。地图上一共有M个敌人，一个敌人可以近似看成一个平面上的点，其中第i个敌人位于(pi,qi)。JY</div>
<div>Y可以使用一枚可以设置半径的炸弹，可以设置一个不超过R的范围，然后选择平面上的一个点引爆，范围内的所有</div>
<div>敌人全部消灭。当然，由于炸弹威力巨大，如果爆炸范围接触到JYY的建筑，那么JYY的建筑也会受到损伤。（注：</div>
<div>如果炸弹的爆炸范围仅接触到了JYY建筑的边界，则不会对JYY的建筑造成损伤；如果敌人出现在了爆炸范围的边界</div>
<div>，则该敌人被消灭）JYY可以自由控制炸弹的爆炸地点和爆炸半径。作为一个保守的玩家，他希望在保证自己建筑</div>
<div>毫发无损的情况下，消灭尽量多的敌人。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含三个非负整数，分别为N，M，R。</div>
<div>接下来N行，每行3个整数，其中第i的为xi,yi,ri，表示第i个建筑的位置和半径。数据保证所有建筑不相交（但是</div>
<div>有可能边界接触）。</div>
<div>接下来M行，每行2个整数，其中第i行为pi,qi，表示第i个敌人的位置。</div>
<div>0&lt;=N&lt;=10,0&lt;M&lt;=1000</div>
<div>1&lt;=R,ri&lt;=20000</div>
<div>|pi|,|qi|,|xi|,|yi|&lt;=20000</div>
<div></div></div>

# Output

<div class="content"><div>输出一行一个整数，表示JYY最多可以消灭的敌人数量。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">1 5 3<br/>
0 0 1<br/>
3 3<br/>
-3 3<br/>
3 -3<br/>
3 0<br/>
0 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
第一个样例中， 最佳攻击选择应将炸弹在(3,3)引爆并将半径设置为3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

