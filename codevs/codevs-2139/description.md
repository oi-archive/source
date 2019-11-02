<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>某城市市区规划成网格状，市区由n+1条南北走向和n+1条东西走向的干道将其平均分为n^2个区域，（n＋1）^2个叉路口。区域及叉路口均由上至下，由左至右编号。例如，图一、图二分别表示N=4时区域及叉路口的编号情况。</p>
<p>　                                   </p>
<div>
<table border="1" cellpadding="0" cellspacing="1" style="">
<tbody>
<tr>
<td valign="top" width="24%">
<p>1</p>
</td>
<td valign="top" width="24%">
<p>2</p>
</td>
<td valign="top" width="24%">
<p>3</p>
</td>
<td valign="top" width="24%">
<p>4</p>
</td>
</tr>
<tr>
<td valign="top" width="24%">
<p>5</p>
</td>
<td valign="top" width="24%">
<p>6</p>
</td>
<td valign="top" width="24%">
<p>7</p>
</td>
<td valign="top" width="24%">
<p>8</p>
</td>
</tr>
<tr>
<td valign="top" width="24%">
<p>9</p>
</td>
<td valign="top" width="24%">
<p>10</p>
</td>
<td valign="top" width="24%">
<p>11</p>
</td>
<td valign="top" width="24%">
<p>12</p>
</td>
</tr>
<tr>
<td valign="top" width="24%">
<p>13</p>
</td>
<td valign="top" width="24%">
<p>14</p>
</td>
<td valign="top" width="24%">
<p>15</p>
</td>
<td valign="top" width="24%">
<p>16</p>
</td>
</tr>
</tbody>
</table>
</div>
<p> <span style="">图一 区域编号图</span></p>
<table border="3">
<tbody>
<tr>
<td style="">1</td>
<td>2</td>
<td>3</td>
<td>4</td>
<td>5</td>
</tr>
<tr>
<td>6</td>
<td>7</td>
<td>8</td>
<td>9</td>
<td>10</td>
</tr>
<tr>
<td>11</td>
<td>12</td>
<td>13</td>
<td>14</td>
<td>15</td>
</tr>
<tr>
<td>16</td>
<td>17</td>
<td>18</td>
<td>19</td>
<td>20</td>
</tr>
<tr>
<td>21</td>
<td>22</td>
<td>23</td>
<td>24</td>
<td>25</td>
</tr>
</tbody>
</table>
<p><span style=""><br></span></p>
<p>图二 叉路口编号图</p>
<p>现在要在城市中划分出若干区域作为游览胜地，每一个游览胜地将会有且仅有一路公共汽车围绕它的四周运行，这路公共汽</p>
<p>车将仅在该区域四周的四个叉路口设立四个公共汽车车站。相邻的两个区域（两个区域相邻当且仅当它们有一段公共的公路）将会共用两个公共汽车车站。</p>
<p>政府为每一个公共汽车车站设立一个站牌，站牌号用自然数1，2，3，…表示且互不相同，可没想到站牌号的设置令政府大伤脑筋。原来，该城市有三个公交公司，他们有各自的规定，即：</p>
<p>1．甲公司的一路公共汽车绕某一个区域运行的四个站，应该满足下面条件：从某一个站出发，顺时针方向经过的三个站应是站牌号逐渐减少的，再回到原来的那个站。</p>
<p>2．乙公司的一路公共汽车绕某一个区域运行的四个站，应该满足下面条件：从某一个站出发，逆时针方向经过的三个站应是站牌号逐渐减少的，再回到原来的那个站。</p>
<p>3．丙公司的一一路公共汽车绕某个区域运行的四个站，应该满足下面条件：从某一个站出发，顺时针方向经过的三个站应是站牌号依次先减少，再增加，再减少，最后再 增加回到原来的那个站。</p>
<p>为公平起见，政府希望找出一个安排站牌的方法，对这<span>n</span>个区域所涉及的所有的<span>K</span>个站分配站牌。使三个公司能在游览胜地中开辟尽量一样多的公共汽车路线。请你编程解决上述问题。</p>
<p>设三个公司可开辟的公共汽车路线数分别为<span>X</span>、<span>Y</span>、<span>Z</span>，你应使：<span>S</span>＝（<span>X</span>一<span>Y</span>）<span>^2 </span>＋<span>(Y</span>一<span>Z)^2</span>十（<span>Z</span>一<span>X</span>）<span>^2</span>最小。如果你找不到<span>S</span>的最小值，你应该使你找到的<span>S</span>值尽量的小。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行为n（0＜n＜8，第二行为m，表示有m个区域为游览胜地，第三行的m个数分别为这m个区域的编号，相邻的两数之间用一个空格符隔开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件的第一行为你所找到的<span lang="EN-US">S</span>值，第二行为<span lang="EN-US">K</span>，以下的<span lang="EN-US">K</span>行每行各有两个数，第一个数为叉路口号，第二个数为你安排该叉路口的公共汽车站牌号（站牌号应为由<span lang="EN-US">1</span>到<span lang="EN-US">K</span>的自然数，且各不相同），这<span lang="EN-US">K</span>行应按叉路口号从小到大输出。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">2</span></p>
<p><span>3</span></p>
<p><span>2 3 4</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">0</span></p>
<p><span>8</span></p>
<p><span>2 7</span></p>
<p><span>3 6</span></p>
<p><span>4 8</span></p>
<p><span>5 1</span></p>
<p><span>6 5</span></p>
<p><span>7 4 8 3</span></p>
<p><span>9 2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n最大为7</p>
</div>
</div>