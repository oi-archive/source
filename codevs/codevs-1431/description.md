<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>这又是一道关于国际象棋棋盘上放子的题目， 虽然这种题目已经出滥了， 但是大</span><span> </span><span><br></span><span>家还是要忍住再摆一回"马"吧 :-),</span><span> </span><span>这里面马的攻击规则和传统的国际象棋一样, 即一</span><span> </span><span><br></span><span>个坐标是</span><span>(0,0)</span><span>的马可以攻击到的格子是</span><span>(1, 2),  (2, 1),  (2, -1),  (1, -2), (-1, -2), (-2, -1),  (-2, 1), (-1, 2), </span><span>假设这些格子都在棋盘上</span><span>. </span><span><br></span><span><br></span><span>   </span><span>这道题的描述非常简单</span><span>,  </span><span>就是在n*n(1</span><span>&lt;= n&lt;</span><span>= 10)的棋盘上放k个马, 问有多少种</span><span> </span><span><br></span><span>摆放的方法使得任意两个马互相不攻击.</span><span> </span><span>唯一的限制是你只能把这些马摆放到指定(将</span><span> </span><span><br></span><span>被描述在输入文件里面)的t(k</span><span>&lt;= t&lt;</span><span>= 40)个位置上. 为了简化你的输出, 你只要输出结</span><span> </span><span><br></span><span>果除以9901的余数就可以了</span><span> </span><span><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行是包含三个整数</span><span>n</span><span>、</span><span>t</span><span>、</span><span>k, </span><span>之后t行每行两个整数x和y( 1</span><span>&lt;=x&lt;=n, 1&lt;=y&lt;</span><span>=n)描述每个可以放置马的位置, 这里面任意两个位置都是不同的.</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0"><span class="15">包含唯一的一行一个整数表示总共的放置方案数除以</span><span class="15">9901</span><span class="15">的余</span><span class="15">数.</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>2 4 2</span><span><br></span><span>1 1 </span><span><br></span><span>1 2 </span><span><br></span><span>2 1 </span><span><br></span><span>2 2 </span><span><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>