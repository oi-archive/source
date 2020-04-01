<div id="pcont1" style="margin-top:20px; display:block;">

# 题目背景

<div class="pdcont">　　Bertown被包围了！入侵者封锁了所有的道路，然后他们用加农炮(Cannon)轰炸这座城市。幸运的是，Bertown的情报机关在设法阻止敌人的轰炸。</div>
# 问题描述

<div class="pdcont">　　为了方便描述，我们引进了直角坐标系，其中Cannon炮在坐标系的原点(0,0)点，城市在x轴的正半轴，y轴的正半轴则表示天空。Cannon会向城市打出n枚炮弹。所有炮弹的初速度相等且等于V(单位：m/s)，当然初速度方向都是斜指向天空（即斜抛运动），于是炮弹的路径就可以仅仅由一个角度alpha来描述，alpha表示炮弹初速度方向与x轴正半轴的夹角，由于科技条件限制，alpha不能超过45°(π/ 4)。假设炮弹发出去后只受到重力的影响。<br/>
　　根据物理定理，我们可以知道：<br/>
　　v<sub>x</sub>(t) = V · cos(alpha)<br/>
　　v<sub>y</sub>(t) = V · sin(alpha) – g · t<br/>
　　x(t) = V · cos(alpha) · t<br/>
　　y(t) = V · sin(alpha) · t – g · t<sup>2</sup> / 2<br/>
　　（本题中重力加速度g可以视为9.8m/s<sup>2</sup>）<br/>
　　Bertown一共有m堵墙。所有墙可以看成一条垂直于x轴的线段(xi,0)-(xi,yi)，线段可能退化成点，当炮弹一旦触碰到墙（线段）或者地面（x轴），它就会停止行动，如果炮弹刚好经过线段的端点(xi,yi)，那么也算作是触碰。<br/>
　　你的任务是找到每一枚炮弹最后停止的位置。</div>
# 输入格式

<div class="pdcont">　　第一行两个正整数n,V(1 ≤ <i>n</i> ≤ 10000, 1 ≤ <i>V</i> ≤ 1000))，分别表示炮弹的数量以及初速度。<br/>
　　接下来n行，每行一个实数表示大炮的发射角度alpha（单位：弧度；0&lt;<i>alpha<sub>i</sub></i>&lt;π/4）；<br/>
　　再接下来一个整数m表示墙的数量(1 ≤ <i>m </i>≤ 10<sup>5</sup>)。<br/>
　　最后m行，每行2个实数xi和yi(1 ≤ <i>x<sub>i</sub></i> ≤ 1000, 0 ≤ <i>y<sub>i</sub></i> ≤ 1000)，表示m堵墙的信息。<br/>
<br/>
　　所有输入数据最多含有4位小数。</div>
# 输出格式

<div class="pdcont">　　输出n行，每行2个实数依次表示每枚炮弹停止的位置，输出顺序与读入顺序一致。<br/>
　　你的输出与标准输出之差不超过 10<sup>-4</sup>则判为正确。</div>
# 样例输入

<div class="pddata">2 10<br/>
0.7853<br/>
0.3<br/>
3<br/>
5.0 5.0<br/>
4.0 2.4<br/>
6.0 1.9</div>
# 样例输出

<div class="pddata">5.000000000 2.549499369<br/>
4.000000000 0.378324889</div>
# 样例输入

<div class="pddata">2 10<br/>
0.7853<br/>
0.3<br/>
2<br/>
4.0 2.4<br/>
6.0 1.9</div>
# 样例输出

<div class="pddata">10.204081436 0.000000000<br/>
4.000000000 0.378324889</div>
# 部分数据规模

<div class="pdcont">　　对于50%的数据：1 ≤ n * m ≤ 1000000。</div>

</div>