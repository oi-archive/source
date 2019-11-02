<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　小A的楼房外有一大片施工工地，工地上有N栋待建的楼房。每天，这片工地上的房子拆了又建、建了又拆。他经常无聊地看着窗外发呆，数自己能够看到多少栋房子。</span><br><span>　　为了简化问题，我们考虑这些事件发生在一个二维平面上。小A在平面上(0,0)点的位置，第i栋楼房可以用一条连接(i,0)和(i,H</span><sub>i</sub><span>)的线段表示，其中H</span><sub>i</sub><span>为第i栋楼房的高度。如果这栋楼房上任何一个高度大于0的点与(0,0)的连线没有与之前的线段相交，那么这栋楼房就被认为是可见的。</span><br><span>　　施工队的建造总共进行了M天。初始时，所有楼房都还没有开始建造，它们的高度均为0。在第i天，建筑队将会将横坐标为X</span><sub>i</sub><span>的房屋的高度变为Y</span><sub>i</sub><span>(高度可以比原来大---修建，也可以比原来小---拆除，甚至可以保持不变---建筑队这天什么事也没做)。请你帮小A数数每天在建筑队完工之后，他能看到多少栋楼房？</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　第一行两个正整数N,M</span><br><span>　　接下来M行，每行两个正整数X</span><sub>i</sub><span>,Y</span><sub>i</sub></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　M行，第i行一个整数表示第i天过后小A能看到的楼房有多少栋</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>3 4</span><br><span>2 4</span><br><span>3 6</span><br><span>1 1000000000</span><br><span>1 1</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>1</span><br><span>1</span><br><span>1</span><br><span>2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<div>对于所有的数据1&lt;=X<sub>i</sub>&lt;=N，1&lt;=Y<sub>i</sub>&lt;=10<sup>9</sup><br>
<table cellpadding="2px" cellspacing="0">
<tbody>
<tr>
<td valign="top">测试点</td>
<td valign="top">N,M</td>
</tr>
<tr>
<td valign="top">1</td>
<td valign="top">&lt;=100</td>
</tr>
<tr>
<td valign="top">2</td>
<td valign="top">&lt;=5000</td>
</tr>
<tr>
<td valign="top">3</td>
<td valign="top">&lt;=50000</td>
</tr>
<tr>
<td valign="top">4</td>
<td valign="top">&lt;=100000</td>
</tr>
<tr>
<td valign="top">5</td>
<td valign="top">&lt;=30000</td>
</tr>
<tr>
<td valign="top">6</td>
<td valign="top">&lt;=50000</td>
</tr>
<tr>
<td valign="top">7</td>
<td valign="top">&lt;=70000</td>
</tr>
<tr>
<td valign="top">8</td>
<td valign="top">&lt;=80000</td>
</tr>
<tr>
<td valign="top">9</td>
<td valign="top">&lt;=90000</td>
</tr>
<tr>
<td valign="top">10</td>
<td valign="top">&lt;=100000</td>
</tr>
</tbody>
</table>
</div>
<div>　　其他条件：测试点1~4：建筑队每天等概率随机选择一栋房屋将其改造成1~10<sup>9</sup>内的等概率随机高度。测试点5~10：无。</div>
</div>
<div> </div>
<div>来源：<span>中国国家队清华集训 2012-2013 第一天</span></div>
</div>
</div>