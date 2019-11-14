<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

某陈和某Y 最近对一个游戏着迷.那是Electronic Arts 今年发布的优秀的模拟经营类游戏,Spore.
在Spore 中,玩家将经历从单细胞生物到星系的统治者的进化过程,创造并守护你自己的文明.
而某陈在经历了几天*几十分钟/天的游戏后,也终于已经近乎通关了.
目前,某陈统治着银河系中标号1 到N 的星系,而他的帝国中心,在星系1 的某颗美丽的行星之上.如同所有银河系中的文
明一样,贸易,发展,结盟,扩张,抵抗Grox[银河系中心的庞大的强悍的恐怖的邪恶帝国]的侵略.
某陈有足够的力量,他的疆域蔓延几百个光年.可是Grox 异常强大,他们的飞船出现在某陈了解的任何地方,并时常攻击任
何位置的某陈和盟友的单位[飞船,建筑,星球,甚至星系].战争在所难免.
某陈将从帝国中心去标号为N 的星系,他疆域的边缘,去寻找一个可能存在的通向银河系中心的黑洞.他要计划一条合适的
路线.
从星系g1 到达g2,某陈需要花费c1 的代价[主要是燃料,另外还有与沿途Grox 的势力作战的花费],c1 小于0 则是因为
这样的星系旅行,会给某陈带来收益[来源于物流差价,以及一些殖民地的税收..].相应地,c2 则是代表从星系g2 到达g1
的代价.据某陈了解,共有M 条这样的星系间路径.
为了战备,他需要选择一条总代价最小的路线.

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
输入文件包括多组数据.
对于每一组数据,第一行有2 个整数n,m,如题目描述中的含义,1&lt;=n&lt;=1000,0&lt;=m&lt;=10000.
接下来的m 行,每行会有四个整数g1,g2,c1,c2,如题目描述中的含义.0&lt;=g1,g2&lt;=n.输入数据保证所有整数都在[-
10000..10000]的范围内.
n=0,m=0 标识着输入数据的结束.每个输入文件包含不超过10 组数据.

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

对于每组输入数据,输出一行,为从星系1 到星系N 的最小代价的路线的代价.
如果这样的路线不存在,输出'No such path'.

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
3 2
1 2 2 -1
2 3 0 1
0 0

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
2

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
jiantimu
</div>
</div>