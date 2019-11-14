<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>zgx被xqz关进了一个迷宫。他这个迷宫有m*n个方块组成。每个字符都代表一个方块。‘s'起点，'f'终点，’#‘墙壁，’.'通路。zgx从一个点到另一个非墙壁的点需1分钟。</p><p><br></p><p style=""><span style="font-family: arial, helvetica, sans-serif;">还有'1'~'9'，代表zgx到达这里之后需要额外1~9分钟解开房间的一些密码（以及弄点东西吃）（这些都不重要，反正要1~9分钟），才能离开。</span></p><p style=""><span style="font-family: arial, helvetica, sans-serif;"><br></span></p><p style=""><span style="font-family: arial, helvetica, sans-serif;">他最少要多长时间走出迷宫呢？</span></p><p style=""><span style="font-family: arial, helvetica, sans-serif;"><br></span></p><p style=""><span style="font-family: arial, helvetica, sans-serif;">如果走不出迷宫，输出"<span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">Impossible"</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: arial, helvetica, sans-serif;">第一行，m,n。</span></p><p style=""><br style=""></p><p style=""><span style="font-family: arial, helvetica, sans-serif;">第2~n+1行，每行n个字符，描述迷宫。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>9</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="">3 3</p><p style="">#1s</p><p style="">f9.</p><p style="">1.3</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>9</p><p>/*</p><p>为了让大家看懂题，特加此注释</p><p>(1,3)-&gt;(2,3)1min</p><p>(2,3)-&gt;(3,3)1min</p><p>(3,3)stop 3min</p><p>(3,3)-&gt;(3,2)1min</p><p>(3,2)-&gt;(3,1)1min</p><p>(3,1)stop 1min</p><p>(3,1)-&gt;(2,1)1min</p><p>1+1+3+1+1+1+1==9</p><p>只要求输出9</p><p>*/</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>m,n&lt;=1000</p><p>用深搜做（你信）</p><p><br></p><p>到达房间'1’以后还需要额外一个时间单位才能走出房间</p><p>以此类推</p>
</div>
</div>