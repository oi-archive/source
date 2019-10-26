
# Content

![title](/source/lutece/xiao-guai-shou/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzAzLzIwMTQwNDA5MjE1NjIyOTM4OS5qcGc=.jpg)

小怪兽Hz危害天下苍生，男巫Lsj立志为民除害。Lsj苦心修习一种魔法弹，这种魔法弹威力巨大，美中不足的是消耗魔力太多，Lsj自身的魔力值只够一发所需。终于，自信能一击必杀的Lsj来到了Hz的巢穴。在坐标系中，Lsj的坐标是$(0, 0)$，Hz的坐标是$(A, 0)$。

Hz的巢穴中有许多悬浮空中的宝箱，宝箱中是Hz积攒的不义之财。Lsj决定取些财宝回去还给百姓，于是他施展魔法，改变重力加速度，使得魔法弹在击中Hz之前能够碰到尽量多的宝箱（宝箱一旦被碰到就会被传送到Lsj手边，不影响魔法弹的飞行轨迹，必须保证轨迹能击中Hz的前提下才能收集宝箱）（Lsj的魔法保证改变后重力加速度仍然是一个正数）。

![title](/source/lutece/xiao-guai-shou/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzAzLzIwMTQwNDA5MjE1NjMyNDA4MTAuanBn.jpg)

每个宝箱可以看做底面平行于$x$轴的矩形（宝箱有可能重叠）。如果炮弹碰到某个宝箱，Lsj就可以得到这个宝箱（如上图所示）。那么Lsj最多可能得到多少个宝箱？

# Standard Input

第一行中的整数$T$代表输入数据组数。($1\leq T\leq 20$)

每组数据的第一行是Hz位置的横坐标$A$（$0<A\leq 10000.0$, $A$为浮点数），宝箱数目$N$（$0\leq N\leq 10000$，$N$为整数）

此后有$N$行，每行有$4$个浮点数$x\_1$,$y\_1$,$x\_2$,$y\_2$（$0.5<x\_1<x\_2<A-0.5$, $1.0<y\_1<y\_2<1.0\times 10^8$）分别是每个宝箱的左下角和右上角位置坐标。

# Standard Output

每组数据的输出仅有一行。对于第$k$组数据，先输出`Case #k: `一个整数，表示在炮弹击中Hz前最多可以获得的宝箱数目。每组数据的输出占一行。

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>2
10.0 1
2.0 2.0 3.0 3.0
10.0 3
3.0 3.0 4.0 4.0
1.0 5.0 2.0 7.0
7.0 3.0 8.0 4.0</td><td>Case #1: 1
Case #2: 2</td></tr></table>


# Constraints



# Note

第二组样例中炮弹可以穿过第一个和第三个宝箱

# Source


