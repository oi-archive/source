<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">设有<span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">n</span></span></span>种物品，记作<span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">A1</span></span></span>、<span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">A2</span></span></span>、<span style="font-family: Arial,sans-serif;">…</span>、<span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">An</span></span></span>，对应于每个<span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">Ai</span></span></span>（<span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">1&lt;=i&lt;=n</span></span></span>）都有一个重量<span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">Awi</span></span></span>和价值<span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">Avi</span></span></span>（重量和价值都为正整数）。另外，对应于每个<span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">Ai</span></span></span>，都有一件可代替它的<span style="font-family: Arial,sans-serif;">“</span>代用品<span style="font-family: Arial,sans-serif;">”</span><span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">Bi</span></span></span>，<span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">Bi</span></span></span>的重量和价值分别为<span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">Bwi</span></span></span>和<span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">Bvi</span></span></span>。</p>
<p style="">本题的任务是：选择这<span style="font-family: Arial,sans-serif;"><span>n</span></span>件物品或其代用品的一个子集装进背包，使总重量不超过给定重量<span style="font-family: Arial,sans-serif;"><span>TOT</span></span>，同时使总价值<span style="font-family: Arial,sans-serif;"><span>VAL</span></span>最高。装填的第<span style="font-family: Arial,sans-serif;"><span>I</span></span>步，要么装入<span style="font-family: Arial,sans-serif;"><span>Ai</span></span>，要么装入<span style="font-family: Arial,sans-serif;"><span>Bi</span></span>，要么<span style="font-family: Arial,sans-serif;"><span>Ai</span></span>和<span style="font-family: Arial,sans-serif;"><span>Bi</span></span>都不装。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">第一行：<span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">n TOT </span></span></span>，<span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">n&lt;=100, TOT&lt;=10000</span></span></span></p>
<p style="">第二行：<span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">A</span><sub><span style="font-family: Arial,sans-serif;">W1 </span></sub><span style="font-family: Arial,sans-serif;"> A</span><sub><span style="font-family: Arial,sans-serif;"> v1 </span></sub><span style="font-family: Arial,sans-serif;"> B</span><sub><span style="font-family: Arial,sans-serif;"> W1 </span></sub><span style="font-family: Arial,sans-serif;"> B</span><sub><span style="font-family: Arial,sans-serif;">v1</span></sub></span></span></p>
<p style="">第三行：<span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">A</span><sub><span style="font-family: Arial,sans-serif;">W2 </span></sub><span style="font-family: Arial,sans-serif;"> A</span><sub><span style="font-family: Arial,sans-serif;"> v2 </span></sub><span style="font-family: Arial,sans-serif;"> B</span><sub><span style="font-family: Arial,sans-serif;"> W2 </span></sub><span style="font-family: Arial,sans-serif;"> B</span><sub><span style="font-family: Arial,sans-serif;">v2</span></sub></span></span></p>
<p style=""><span style="font-family: Arial,sans-serif;"><span> ……</span></span></p>
<p style="">第<span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">n+1</span></span></span>行：<span style="font-family: Times New Roman,serif;"><span><span style="font-family: Arial,sans-serif;">A</span><sub><span style="font-family: Arial,sans-serif;">Wn </span></sub><span style="font-family: Arial,sans-serif;"> A</span><sub><span style="font-family: Arial,sans-serif;"> vn </span></sub><span style="font-family: Arial,sans-serif;"> B</span><sub><span style="font-family: Arial,sans-serif;"> Wn </span></sub><span style="font-family: Arial,sans-serif;"> B</span><sub><span style="font-family: Arial,sans-serif;">vn</span></sub></span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="cjk" style="text-indent: 0.74cm; margin-bottom: 0cm;">只有一个数为最大的价值</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: Arial,sans-serif;"><span>4 20</span></span></p>
<p style=""><span style="font-family: Arial,sans-serif;"><span>8 20 12 31</span></span></p>
<p style=""><span style="font-family: Arial,sans-serif;"><span>2 3 9 20</span></span></p>
<p style=""><span style="font-family: Arial,sans-serif;"><span>13 31 11 12</span></span></p>
<p style=""><span style="font-family: Arial,sans-serif;"><span>8 9 13 36</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: Arial,sans-serif;"><span>40</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>详见输入描述</p>
</div>
</div>