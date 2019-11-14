<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    这天，小X<span style="">幸运</span>地获得了一次进行挖金币游戏的机会，规则如下：</p>
<p>    在一个<span style="font-family: 'Times New Roman';">N*N</span><span style="">的矩形里，有</span><span style="font-family: 'Times New Roman';">N*N</span><span style="">个边长为</span><span style="font-family: 'Times New Roman';">1</span><span style="">的正方形格子</span>。在游戏中取左下角的格子坐标为（<span style="font-family: 'Times New Roman';">1</span><span style="">，</span><span style="font-family: 'Times New Roman';">1</span><span style="">），右上角为（</span><span style="font-family: 'Times New Roman';">N,N</span><span style="">）。在游戏开始前，每一个格子中都会放入一枚金币，而当游戏开始时，每一个格子中的那一枚金币都会进行一次移动，移动后的横、纵坐标值将分别变为原横、纵坐标值每一位上的乘积。当有金币被移动出格子矩形时，将被游戏方收走。小</span>X将被允许选取<span style="font-family: 'Times New Roman';">M</span><span style="">个格子，他将获得他所选取的格子中所有的金币，</span>而他对游戏中获得的金币数有一个期望值H<span style="">。他想知道他最多能获得的金币数能否达到他的期望值。不过金币移动的让人眼花缭乱，小</span><span style="font-family: 'Times New Roman';">X</span><span style="">算不过来了，他找到了你，希望你能用编程解决这个问题。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一行，三个正整数数<span style="font-family: 'Times New Roman';">N</span>、M、H，以空格隔开，意义如题目中所说</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一个或两个正整数数，以空格隔开</p>
<p class="p0">若小X<span style="font-family: 宋体;">最多能获得的金币数能达到期望值（即大于等于）</span>，则输出小X最多能获得的金币数以及金币总数能达到期望值的格子数的最小值</p>
<p class="p0">若小X<span style="font-family: 宋体;">最多能获得的金币数不能达到期望值（即小于），则输出金币数最多的那个格子中的金币数</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>17 3 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>12 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于<span style="font-family: 'Times New Roman';">20%</span><span style="">的数据，保证</span><span style="font-family: 'Times New Roman';">0</span><span style="">＜</span><span style="font-family: 'Times New Roman';">M</span><span style="">≤</span><span style="font-family: 'Times New Roman';">N</span>≤100</p>
<p>对于<span style="font-family: 'Times New Roman';">50%</span><span style="">的数据，保证</span><span style="font-family: 'Times New Roman';">0</span><span style="">＜</span><span style="font-family: 'Times New Roman';">M</span><span style="">≤</span><span style="font-family: 'Times New Roman';">N</span>≤2000</p>
<p>对于<span style="font-family: 'Times New Roman';">70%</span><span style="">的数据，保证</span><span style="font-family: 'Times New Roman';">0</span><span style="">＜</span><span style="font-family: 'Times New Roman';">M</span><span style="">≤</span><span style="font-family: 'Times New Roman';">N</span>≤5000</p>
<p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据，保证</span><span style="font-family: 'Times New Roman';">0</span><span style="">＜</span><span style="font-family: 'Times New Roman';">M</span><span style="">≤</span><span style="font-family: 'Times New Roman';">N</span>≤10000</p>
<p>举例，（<span style="font-family: 'Times New Roman';">123,456</span><span style="">）处的金币将会被移动至（</span><span style="font-family: 'Times New Roman';">1*2*3</span><span style="">，</span><span style="font-family: 'Times New Roman';">4*5*6</span><span style="">）即（</span><span style="font-family: 'Times New Roman';">6,120</span><span style="">）。</span></p>
</div>
</div>