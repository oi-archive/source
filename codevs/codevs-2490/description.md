<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　Freda的城堡——</span><br><span>　　“Freda，城堡外发现了一些入侵者！”</span><br><span>　　“喵...刚刚探究完了城堡建设的方案数，我要歇一会儿嘛lala~”</span><br><span>　　“可是入侵者已经接近城堡了呀！”</span><br><span>　　“别担心，rainbow，你看呢，这是我刚设计的导弹防御系统的说~”</span><br><span>　　“喂...别卖萌啊……”</span></p>
<p><span><span>　　Freda控制着N座可以发射导弹的防御塔。每座塔都有足够数量的导弹，但是每座塔每次只能发射一枚。在发射导弹时，导弹需要T1秒才能从防御塔中射出，而在发射导弹后，发射这枚导弹的防御塔需要T2分钟来冷却。</span><br><span>　　所有导弹都有相同的匀速飞行速度V，并且会沿着距离最短的路径去打击目标。计算防御塔到目标的距离Distance时，你只需要计算水平距离，而忽略导弹飞行的高度。导弹在空中飞行的时间就是 (Distance/V) 分钟，导弹到达目标后可以立即将它击毁。</span><br><span>　　现在，给出N座导弹防御塔的坐标，M个入侵者的坐标，T1、T2和V，你需要求出至少要多少分钟才能击退所有的入侵者。</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　第一行五个正整数N,M,T1,T2,V。</span><br><span>　　接下来M行每行两个整数，代表入侵者的坐标。</span><br><span>　　接下来N行每行两个整数，代表防御塔的坐标。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　<span>输出一个实数，表示最少需要多少分钟才能击中所有的入侵者，四舍五入保留六位小数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3 30 20 1<br>0 0<br>0 50<br>50 0<br>50 50<br>0 1000<br>1000 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>91.500000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>　　对于40%的数据，N,M&lt;=20.</span><br><span>　　对于100%的数据， 1≤N≤50, 1≤M≤50，坐标绝对值不超过10000，T1,T2,V不超过2000.</span></p>
<p><span><br></span></p>
<p><span>来源：Nescafe 19</span></p>
</div>
</div>