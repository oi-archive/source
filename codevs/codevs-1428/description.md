<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>国际象棋是世界上最古老的博弈游戏之一，和中国的围棋、象棋以及日本的将棋同享盛名。据说国际象棋起源于易经的思想，棋盘是一个<span style="font-family: 'Times New Roman';">8*8</span><span style="">大小的黑白相间的方阵，对应八八六十四卦，黑白对应阴阳。</span></p><p>而我们的主人公小<span style="font-family: 'Times New Roman';">Q</span><span style="">，正是国际象棋的狂热爱好者。作为一个顶尖高手，他已不满足于普通的棋盘与规则，于是他跟他的好朋友小</span><span style="font-family: 'Times New Roman';">W</span><span style="">决定将棋盘扩大以适应他们的新规则。</span></p><p>小<span style="font-family: 'Times New Roman';">Q</span><span style="">找到了一张由</span><span style="font-family: 'Times New Roman';">N*M</span><span style="">个正方形的格子组成的矩形纸片，每个格子被涂有黑白两种颜色之一。小</span><span style="font-family: 'Times New Roman';">Q</span><span style="">想在这种纸中裁减一部分作为新棋盘，当然，他希望这个棋盘尽可能的大。</span></p><p>不过小<span style="font-family: 'Times New Roman';">Q</span><span style="">还没有决定是找一个正方形的棋盘还是一个矩形的棋盘（当然，不管哪种，棋盘必须都黑白相间，即相邻的格子不同色），所以他希望可以找到最大的正方形棋盘面积和最大的矩形棋盘面积，从而决定哪个更好一些。</span></p><p>于是小<span style="font-family: 'Times New Roman';">Q</span><span style="">找到了即将参加全国信息学竞赛的你，你能帮助他么？</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个整数N和M，分别表示矩形纸片的长和宽。接下来的N行包含一个N * M的<span style="font-family: 'Times New Roman';">01</span><span style="">矩阵，表示这张矩形纸片的颜色（</span><span style="font-family: 'Times New Roman';">0</span><span style="">表示白色，</span><span style="font-family: 'Times New Roman';">1</span><span style="">表示黑色）。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出<span style="font-size: 10px;">包含两行，每行包含一个整数。第一行为可以找到的最大正方形棋盘的面积，第二行为可以找到的最大矩形棋盘的面积（注意正方形和矩形是可以相交或者包含的）。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p><p>1 0 1</p><p>0 1 0</p><p>1 0 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p><p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于<span style="font-family: 'Times New Roman';">20%</span><span style="">的数据，</span>N, M &amp;le; 80</p><p>对于<span style="font-family: 'Times New Roman';">40%</span><span style="">的数据，</span>N, M &amp;le; 400 </p><p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据，</span>N, M &amp;le; 2000</p>
</div>
</div>