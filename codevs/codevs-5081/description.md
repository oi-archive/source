<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style=""></span>有一次，小朋友的学校新开了一家商店，小朋友于是去那里买水=-=，小卖部的老板很坑爹，越到后面买的水越贵。并且会给一部分钱给前面买水的人。（小卖部老板是土豪）如表所示：</p><table><tbody><tr><td style="" valign="top" width="50"><p>次数</p></td><td style="" valign="top" width="50">1</td><td style="" valign="top" width="50">2</td><td style="" valign="top" width="50">3</td><td style="" valign="top" width="50">4</td><td style="" valign="top" width="50">5</td><td style="" valign="top" width="50">6</td><td style="" valign="top" width="50">7</td></tr><tr><td style="" valign="top" width="50">价格</td><td style="" valign="top" width="50">1</td><td style="" valign="top" width="50">1</td><td style="" valign="top" width="50">2</td><td style="" valign="top" width="50">3</td><td style="" valign="top" width="50">5</td><td style="" valign="top" width="50">8</td><td style="" valign="top" width="50">13</td></tr><tr><td style="" valign="top" width="50">给小明的钱数<br></td><td style="" valign="top" width="50">0</td><td style="" valign="top" width="50">0</td><td style="" valign="top" width="50">0</td><td style="" valign="top" width="50">1<br></td><td style="" valign="top" width="50">1</td><td style="" valign="top" width="50">2</td><td style="" valign="top" width="50">3</td></tr></tbody></table><p>这鬼畜的数列大家都见过吧=-=，现在输入一个数字n,使第n次的价格与后面的价格不变，给小朋友的钱数往后都变成0，（包括这次）问赚的钱数（不包括小朋友用来买水的钱数）与第n次的价格。</p><p>温馨提示<span style="">本题目并不难，请那些刷错误率的朋友别来刷我题目的错误率=-=谢谢啦！</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一个数n,表示从这个数开始往后的价格与小朋友赚的钱数的价格为0（包括第n次）。<br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>两个数x,y.代表小朋友赚的钱数和第n次的价格</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>第一次:4  </p><p>第二次:7</p><p>第三次:13</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>第一次:1 3<br></p><p>第二次:7 13</p><p>第三次：143 233</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>注意！前三次不会给小朋友钱.小朋友赚的钱数要加起来。输出中间用一个空格。</p><p>3&lt;n&lt;30</p>
</div>
</div>