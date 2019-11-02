<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>BESSIE准备用从牛棚跑到池塘的方法来锻炼. 但是因为她懒,她只准备沿着下坡的路跑到池塘,然后走回牛棚.</p><p>BESSIE也不想跑得太远,所以她想走最短的路经. 农场上一共有M (1 &lt;= M &lt;= 10,000)条路,每条路连接两个用1..N(1 &lt;= N &lt;= 1000)标号的地点. 更方便的是,如果X&gt;Y,则地点X的高度大于地点Y的高度. 地点N是BESSIE的牛棚;地点1是池塘.</p><p>很快, BESSIE厌倦了一直走同一条路.所以她想走不同的路,更明确地讲,她想找出K (1 &lt;= K &lt;= 100)条不同的路经.为了避免过度劳累,她想使这K条路经为最短的K条路经.</p><p>请帮助BESSIE找出这K条最短路经的长度.你的程序需要读入农场的地图, 一些从X_i到Y_i 的路经和它们的长度(X_i, Y_i, D_i). 所有(X_i, Y_i, D_i)满足(1 &lt;= Y_i &lt; X_i; Y_i &lt; X_i &lt;= N, 1 &lt;= D_i &lt;= 1,000,000).</p><p>题名: cowjog</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入格式:</p><ul><li><p>第1行: 3个数: N, M, 和K</p></li></ul><ul><li><p>第 2..M+1行: 第 i+1 行包含3个数 X_i, Y_i, 和 D_i, 表示一条下坡的路.</p></li></ul>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出格式:</p><ul class=" list-paddingleft-2"><li><p>第1..K行: 第i行包含第i最短路经的长度,或-1如果这样的路经不存在.如果多条路经有同样的长度,请注意将这些长度逐一列出.</p></li></ul>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>5 8 7
5 4 1
5 3 1
5 2 1
5 1 1
4 3 4
3 1 1
3 2 1
2 1 1</pre><p></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>2
2
3
6
7
-1</pre><p></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见题目描述</p>
</div>
</div>