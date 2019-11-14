
# Description

<div class="content"><div><span style="font-size: medium">Byteasar 国王把他所有的财宝都藏在了他的城堡里的一个秘密地点. 无论如何, 当他外出征战时他害怕如果战死以后财宝将会永远丢失. 因此他选择了一些可以信任的守卫然后告诉了他们每个人一点关于财宝藏匿地点的信息. 然后命令他们去守卫位于城堡地下的地下室并且不断巡逻遵守告诉他们的<i>右手原则</i>. 地下室有很多房间由走廊连接而成. 走廊互相都不交叉. 没有两条走廊连接同样的两个房间. 右手原则规定每个守卫在进入一个房间以后要由他进来的那条走廊右边的那一条离开. 每个守卫都被安排了不同的开始地点和进入走廊. 有的时候多个守卫走进同一个房间是允许的.</span></div>
<div><span style="font-size: medium">国王知道直到他牺牲和归来之前他的守卫都会足够忠诚的执行他的命令. 但是, 他害怕当若干个守卫在同一个房间聚会时他们会分享各自知道的信息. 守卫都是很慷慨的他们会分享他们所知道的所有信息. 但是如果两个守卫在走廊里相遇, 他们不会对对方说任何东西.</span></div>
<div><span style="font-size: medium">国王想知道当他从战场归来时他的财宝是否还能安全可靠. 他想知道可能得到所有财宝信息的守卫.</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行一个整数<i>n</i>. 表示地下室的房间数, 2 &lt;= <i>n</i> &lt;= 100. 房间编号1 到 <i>n</i>. 接下来<i>n</i>行每行描述一个房间. 在第 (<i>i</i> + 1) 行首先一个数<i>k<sub>i</sub></i>, 表示所有和第<i>i</i>个房间连接的走廊, 1 &lt;= <i>k<sub>i</sub></i> &lt;= <i>n</i> - 1. 接下来2<i>k<sub>i</sub></i> 个整数每两个数描述一条走廊. 第一个数为走廊另一头的房间编号, 第二个数为走廊的长度: 一个1 到 100的整数. 走廊都是双向的, 即如果有一条<i>a</i>到<i>b</i>的长度为<i>l</i>的走廊那么肯定对应的有一条从<i>b</i>到<i>a</i>的长度为<i>l</i>的走廊. 所有走廊按顺时针方向给出.</span></div>
<div><span style="font-size: medium">接下来两个整数<i>k</i> 和 <i>l</i>, 1 &lt;= <i>k</i> &lt;= 100, 1 &lt;= <i>l</i> &lt;= 100, <i>k</i> 为守卫的个数, <i>l</i> 为所有需要找到财宝要知道的信息数目. 守卫从1 到 <i>k</i>编号. 财宝信息从1 到 <i>l</i>编号. 接下来<i>k</i> 行每行描述一个守卫. 每行前两个数表示守卫的初始位置和他第一次要走到哪一个房间去. 接下来一个整数<i>m<sub>i</sub></i>, 表示这个守卫知道的信息数目, 0 &lt;= <i>m<sub>i</sub></i> &lt;= <i>l</i>. 然后接着<i>m<sub>i</sub></i> 个整数描述了他所知道的所有信息编号.</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">第一行输出一个整数, 表示知道所有财宝信息的守卫的总数.接下来每行一个数表示这些守卫的编号,从小到大输出. </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
<br/>
<br/>
3 2 3 3 4 4 1<br/>
2 1 3 3 1<br/>
3 4 3 1 4 2 1<br/>
2 1 1 3 3<br/>
3 4<br/>
1 4 2 2 3<br/>
3 1 2 1 2<br/>
3 4 2 3 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
2<br/>
2<br/>
3<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

