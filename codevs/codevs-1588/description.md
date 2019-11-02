<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Siruseri 政府决定将石油资源丰富的Navalur 省的土地拍卖给私人承包商以<br>建立油井。被拍卖的整块土地为一个矩形区域，被划分为M×N 个小块。<br>Siruseri 地质调查局有关于Navalur 土地石油储量的估测数据。这些数据表示<br>为M×N 个正整数，即对每一小块土地石油储量的估计值。<br>为了避免出现垄断，政府规定每一个承包商只能承包一个由K×K 块相连的<br>土地构成的正方形区域。<br>AoE 石油联合公司由三个承包商组成，他们想选择三块互不相交的K×K 的<br>区域使得总的收益最大。<br>例如，假设石油储量的估计值如下：<br>1 1 1 1 1 1 1 1 1<br>1 1 1 1 1 1 1 1 1<br>1 8 8 8 8 8 1 1 1<br>1 8 8 8 8 8 1 1 1<br>1 8 8 8 8 8 1 1 1<br>1 1 1 1 8 8 8 1 1<br>1 1 1 1 1 1 8 8 8<br>1 1 1 1 1 1 9 9 9<br>1 1 1 1 1 1 9 9 9<br>如果K = 2, AoE 公司可以承包的区域的石油储量总和为100, 如果K = 3,<br>AoE 公司可以承包的区域的石油储量总和为208。<br>AoE 公司雇佣你来写一个程序，帮助计算出他们可以承包的区域的石油储量<br>之和的最大值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行包含三个整数M, N, K，其中M 和N 是矩形区域的行数和列数，<br>K 是每一个承包商承包的正方形的大小（边长的块数）。接下来M 行，每行有N<br>个正整数表示这一行每一小块土地的石油储量的估计值。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只包含一个正整数，表示AoE 公司可以承包的区域的石油储量之和的<br />最大值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>9 9 3<br>1 1 1 1 1 1 1 1 1<br>1 1 1 1 1 1 1 1 1<br>1 8 8 8 8 8 1 1 1<br>1 8 8 8 8 8 1 1 1<br>1 8 8 8 8 8 1 1 1<br>1 1 1 1 8 8 8 1 1<br>1 1 1 1 1 1 8 8 8<br>1 1 1 1 1 1 9 9 9<br>1 1 1 1 1 1 9 9 9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>208</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据保证K≤M 且K≤N 并且至少有三个K×K 的互不相交的正方形区域。其<br>中30%的输入数据，M, N≤ 12。所有的输入数据, M, N≤ 1500。每一小块土地的<br>石油储量的估计值是非负整数且≤ 500。</p>
</div>
</div>