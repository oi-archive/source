<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>飞镖是在欧洲颇为流行的一项运动。它的镖盘上分为<span style="font-family: 'Times New Roman';">20</span><span style="">个扇形区域，分别标有</span><span style="font-family: 'Times New Roman';">1</span><span style="">到</span><span style="font-family: 'Times New Roman';">20</span><span style="">的分值，每个区域中有单倍、双倍和三倍的区域，打中对应的区域会得到分值乘以倍数所对应的分数。例如打中</span><span style="font-family: 'Times New Roman';">18</span><span style="">分里面的三倍区域，就会得到</span><span style="font-family: 'Times New Roman';">54</span><span style="">分。另外，在镖盘的中央，还有</span><span style="font-family: 'Times New Roman';">“</span><span style="">小红心</span><span style="font-family: 'Times New Roman';">”</span><span style="">和</span><span style="font-family: 'Times New Roman';">“</span><span style="">大红心</span><span style="font-family: 'Times New Roman';">”</span><span style="">，分别是</span><span style="font-family: 'Times New Roman';">25</span><span style="">分和</span><span style="font-family: 'Times New Roman';">50</span><span style="">分。</span></span></p>
<p><span>通常的飞镖规则还有一条，那就是在最后一镖的时候，必须以双倍结束战斗，才算获胜。也就是说，当还剩<span style="font-family: 'Times New Roman';">12</span><span style="">分的时候，必须打中双倍的</span><span style="font-family: 'Times New Roman';">6</span><span style="">才算赢，而打中单倍的</span><span style="font-family: 'Times New Roman';">12</span><span style="">或者三倍的</span><span style="font-family: 'Times New Roman';">4</span><span style="">则不算。特别的，</span><span style="font-family: 'Times New Roman';">“</span><span style="">大红心</span><span style="font-family: 'Times New Roman';">”</span><span style="">也算双倍</span><span style="font-family: 'Times New Roman';">(</span><span style="">双倍的</span><span style="font-family: 'Times New Roman';">25)</span><span style="">。在这样的规则下，</span><span style="font-family: 'Times New Roman';">3</span><span style="">镖能解决的最多分数是</span><span style="font-family: 'Times New Roman';">170</span><span style="">分</span><span style="font-family: 'Times New Roman';">(</span><span style="">两个三倍的</span><span style="font-family: 'Times New Roman';">20</span><span style="">，最后用大红心结束</span><span style="font-family: 'Times New Roman';">)</span><span style="">。</span></span></p>
<p><span>现在，<span style="font-family: 'Times New Roman';">lxhgww</span><span style="">把原来的</span><span style="font-family: 'Times New Roman';">1</span><span style="">到</span><span style="font-family: 'Times New Roman';">20</span><span style="">分的分值变为了</span><span style="font-family: 'Times New Roman';">1</span><span style="">到</span><span style="font-family: 'Times New Roman';">K</span><span style="">分，同时把小红心的分数变为了</span><span style="font-family: 'Times New Roman';">M</span><span style="">分</span><span style="font-family: 'Times New Roman';">(</span><span style="">大红心是其双倍</span><span style="font-family: 'Times New Roman';">)</span><span style="">，现在</span><span style="font-family: 'Times New Roman';">lxhgww</span><span style="">想知道能否在</span><span style="font-family: 'Times New Roman';">3</span><span style="">镖内（可以不一定用满</span><span style="font-family: 'Times New Roman';">3</span><span style="">镖）解决</span><span style="font-family: 'Times New Roman';">X</span><span style="">分。同样的，最后一镖必须是双倍（包括大红心）。</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行是一个整数T</p>
<p>第二行是5个整数，A1，B1，C1，D1，K1，表示第一组数据的镖盘是从1到K1分的，随后数据的镖盘由公式Ki=(A1*Ki-1<sup>2</sup>+B1*Ki-1+C1) mod D1 + 20决定，其中第i(1 &lt; i &lt;= T)组数据的镖盘是从1到Ki分的</p>
<p>第三行是5个整数，A2，B2，C2，D2，M1，表示第一组数据的小红心是M1分的，随后数据的镖盘由公式Mi=(A2*Mi-1<sup>2</sup>+B2*Mi-1+C2) mod D2 + 20决定，其中第i(1 &lt; i &lt;= T)组数据的的小红心是Mi分的</p>
<p>第四行是5个整数，A3，B3，C3，D3，X1，表示第一组数据需要解决的分数是X1分，随后数据的镖盘由公式Xi=(A3*Xi-1<sup>2</sup>+B3*Xi-1+C3) mod D3 + 20决定，其中第i(1 &lt; i &lt;= T)组数据需要解决的分数是Xi分</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>一行，包括一个数字，表示这</span><span style="font-family: 'Times New Roman';">T</span><span style="font-family: 宋体;">组数据中，能够被解决的数据数目。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>5</span><br><span> 1 2 2 10 20</span><br><span> 1 3 2 15 25</span><br><span> 2 2 5 200 170</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>4</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>1&lt;=T&lt;=1000000,20&lt;=K1,M1,X1,D1,D2,D3&lt;=10^9</span></p>
<p><span style="">0&lt;=A1,B1,C1,A2,B2,C2,A3,B3,c3&lt;=10^9</span></p>
<div>
<div><span><br></span></div>
</div>
</div>
</div>