<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">阿明是一名推销员，他奉命到螺丝街推销他们公司的产品。螺丝街是一条死胡同，出口与入口是同一个，街道的一侧是围墙，另一侧是住户。螺丝街一共有N家住户，第i家住户到入口的距离为Si米。由于同一栋房子里可以有多家住户，所以可能有多家住户与入口的距离相等。阿明会从入口进入，依次向螺丝街的X家住户推销产品，然后再原路走出去。阿明每走1米就会积累1点疲劳值，向第i家住户推销产品会积累Ai点疲劳值。阿明是工作狂，他想知道，对于不同的X，在不走多余的路的前提下，他最多可以积累多少点疲劳值。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="">第一行有一个正整数N，表示螺丝街住户的数量。</span><br style=""><span style="">接下来的一行有N个正整数，其中第i个整数S<sub>i</sub>表示第i家住户到入口的距离。数据保证S<sub>1</sub>≤S<sub>2</sub>≤…≤S<sub>n</sub>&lt;10^8。</span><br style=""><span style="">接下来的一行有N个正整数，其中第i个整数A<sub>i</sub>表示向第i户住户推销产品会积累的疲劳值。数据保证A<sub>i</sub>&lt;10^3。</span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 微软雅黑, &#39;Microsoft YaHei&#39;; font-size: 12px; line-height: 20px; background-color: rgb(255, 255, 255); ">输出N行，每行一个正整数，第i行整数表示当X=i时，阿明最多积累的疲劳值。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="">【样例1】</span><br style=""><span style="">5</span><br style=""><span style="">1 2 3 4 5</span><br style=""><span style="">1 2 3 4 5</span><br style=""><br style=""><span style="">【样例2】</span><br style=""><span style="">5</span><br style=""><span style="">1 2 2 4 5</span><br style=""><span style="">5 4 3 4 1</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="">【样例1】</span><br style=""><span style="">15</span><br style=""><span style="">19</span><br style=""><span style="">22</span><br style=""><span style="">24</span><br style=""><span style="">25</span><br style=""><br style=""><span style="">【样例2】</span><br style=""><span style="">12</span><br style=""><span style="">17</span><br style=""><span style="">21</span><br style=""><span style="">24</span><br style=""><span style="">27</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="">1≤N≤100000</span><br style=""><span style="">注：请用 scanf 输入。</span></span></p>
</div>
</div>