<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　小A的楼房外有一大片施工工地，工地上有N栋待建的楼房。每天，这片工地上的房子拆了又建、建了又拆。他经常无聊地看着窗外发呆，数自己能够看到多少栋房子。<br/>
　　为了简化问题，我们考虑这些事件发生在一个二维平面上。小A在平面上(0,0)点的位置，第i栋楼房可以用一条连接(i,0)和(i,H<sub>i</sub>)的线段表示，其中H<sub>i</sub>为第i栋楼房的高度。如果这栋楼房上任何一个高度大于0的点与(0,0)的连线没有与之前的线段相交，那么这栋楼房就被认为是可见的。<br/>
　　施工队的建造总共进行了M天。初始时，所有楼房都还没有开始建造，它们的高度均为0。在第i天，建筑队将会将横坐标为X<sub>i</sub>的房屋的高度变为Y<sub>i</sub>(高度可以比原来大---修建，也可以比原来小---拆除，甚至可以保持不变---建筑队这天什么事也没做)。请你帮小A数数每天在建筑队完工之后，他能看到多少栋楼房？</div>
# 输入格式

<div class="pdcont">　　第一行两个正整数N,M<br/>
　　接下来M行，每行两个正整数X<sub>i</sub>,Y<sub>i</sub></div>
# 输出格式

<div class="pdcont">　　M行，第i行一个整数表示第i天过后小A能看到的楼房有多少栋</div>
# 样例输入

<div class="pddata">3 4<br/>
2 4<br/>
3 6<br/>
1 1000000000<br/>
1 1</div>
# 样例输出

<div class="pddata">1<br/>
1<br/>
1<br/>
2</div>
# 数据约定

<div class="pdcont">　　对于所有的数据1&lt;=X<sub>i</sub>&lt;=N，1&lt;=Y<sub>i</sub>&lt;=10<sup>9</sup><br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">测试点<br/>
</td><td valign="top" style="border:solid 1.0pt">N,M<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=100<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=5000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=50000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=100000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=30000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=50000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=70000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=80000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">9<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=90000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=100000<br/>
</td></tr></tbody></table>　　其他条件：测试点1~4：建筑队每天等概率随机选择一栋房屋将其改造成1~10<sup>9</sup>内的等概率随机高度。测试点5~10：无。</div>

</div>