<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">Barry Allen</span><span style="">也就是</span><span style="">Flash (</span><span style="">闪电侠</span><span style="">) </span><span style="">正在</span><span style=""> Central City </span><span style="">中打击犯罪，他以极快的速度在城市间穿梭。但是现在他遇到了一个问题，他所追捕的是一名具有超能力的</span><span style="">meta-human</span><span style="">，这个人能够改变城市中道路的高度，将某一条路上升</span><span style="">(</span><span style="">下降</span><span style="">) x</span><span style="">米，这就使城市中的道路高度参差不齐，也阻碍了</span><span style="">Barry</span><span style="">前进的速度。现在</span><span style="">Barry</span><span style="">想要找出从</span><span style="">s</span><span style="">到</span><span style="">t</span><span style="">的一种行进路线，满足他跑的道路的最高的高度和最低的高度差距最小，以便他能更快地到达</span><span style="">t</span><span style="">。</span></p><p><span style="">    </span><span style="">每条道路的初始高度都相等。初始高度一定为正整数，</span><span style="">x</span><span style="">一定为整数。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行输入</span><span style="">n</span><span style="">和</span><span style="">m </span><span style="">中间用空格隔开，表示一共有</span><span style="">n</span><span style="">个路口，</span><span style="">m</span><span style="">条道路。</span></p><p style=""><span style="">第二行输入一个</span><span style="">h</span><span style="">，表示所有道路的初始高度。</span></p><p style=""><span style="">接下来</span><span style="">m</span><span style="">行，输入</span><span style="">u</span><span style="">，</span><span style="">v</span><span style="">，</span><span style="">x</span><span style="">，中间用空格隔开，表示</span><span style="">u</span><span style="">路口到</span><span style="">v</span><span style="">路口中间有一条路。若</span><span style="">x</span><span style="">为正数表示这条路被上升了</span><span style="">x</span><span style="">米，反之则表示下降了</span><span style="">x</span><span style="">米，一条路可能不被修改。</span></p><p style=""><span style="">最后输入</span><span style="">s</span><span style="">和</span><span style="">t</span><span style="">，中间用空格隔开，表示起始路口和目标路口。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size:16px;font-family:宋体">&nbsp; &nbsp; 如果</span><span style="font-size:16px">s</span><span style="font-size:16px;font-family:宋体">和</span><span style="font-size:16px">t</span><span style="font-size:16px;font-family:宋体">不连通输出“</span><span style="font-size:16px">IMPOSSIBLE</span><span style="font-size:16px;font-family:宋体">”</span><span style="font-size:16px"> (</span><span style="font-size:16px;font-family:宋体">不含引号</span><span style="font-size:16px">)</span></p><p><span style="font-size:16px">&nbsp;&nbsp;&nbsp; </span><span style="font-size:16px;font-family:宋体">否则一个整数</span><span style="font-size:16px">ans</span><span style="font-size:16px;font-family:宋体">，表示找到的满足题目中要求的这一条行进路线中，最高道路和最低道路的高度的乘积的绝对值。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">6 7</span></p><p><span style="">2</span></p><p><span style="">1 2 1</span></p><p><span style="">2 4 -1</span></p><p><span style="">1 3 -2</span></p><p><span style="">3 4 3</span></p><p><span style="">4 5 4</span></p><p>4 6 1</p><p><span style="">5 6 0</span></p><p><span style="">1 6   </span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style=""> 30% </span><span style="">的数据满足</span><span style=""> n&lt;=10  m&lt;=20</span></p><p><span style=""> 60% </span><span style="">的数据满足</span><span style=""> n&lt;=100  m&lt;=1000</span></p><p><span style=""> 100% </span><span style="">的数据满足</span><span style=""> n&lt;=500  m&lt;=5000 </span><strong><span style=""> </span></strong><span style="">h&lt;=10000<strong>  </strong></span><strong><span style="">|</span></strong><span style="">x</span><strong><span style="">| </span></strong><strong><span style="">&lt;=1e4 </span></strong><strong><span style=""> </span></strong></p><p><span style=""><br></span></p><p><span style=""> 闪电侠会在道路被修改后才开始行动。</span></p><p><span style=""> 道路被修改后可能为负。</span></p><p><br></p><p><br></p>
</div>
</div>