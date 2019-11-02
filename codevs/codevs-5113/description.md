<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><strong>饥肠辘辘</strong>的<strong>wjj</strong>玩到一个崭新的galgame，这部神奇的galgame中的妹子有自己的颜值，作为字幕组的wjj不愿花费多余的力气去翻译颜值不高的妹子的线路，因此他想知道某两条剧情线之间的所有妹子的颜值和，以便享受最优的游（tui）戏（mei）过程。（剧情线将妹子们连成一棵树）</p><p>(他还要保存体力去玩女装山脉)</p><p>现在给你这部galgame上的剧情线之间的关系，并告知你每个妹子（妹子从1-n编号）的颜值，请你帮wjj找出这部galgame上某两个剧情线的妹子颜值之和.<br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行输入n，m     </p><p>n表示游戏中的剧情线上的妹子数目，m表示询问数。<br></p><p>接下来n个数，第i个数表示妹子i的颜值val[i]</p><p>接下来n-1行，每行有两个数a，b。分别表示妹子a，b间有一条剧情线</p><p>接下来m行，每行有两个数 a，b，表示询问从a妹子到b妹子之间的剧情线上妹子们的颜值和；</p><p><br></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出m行，第i行为第i个询问的答案</p><p><br/></p><p>PS：</p><p>&nbsp;&nbsp;&nbsp;&nbsp;程序错了wjj会桑心的哦！0.0<br/></p><p>&nbsp; &nbsp;<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 3</p><p>2 3 5 8 1</p><p>1 2</p><p>2 3</p><p>2 4</p><p>1 5</p><p>4 5</p><p>3 4</p><p>1 4</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style="">1 4 1 6 1 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n，m&lt;=10^6,val[i]&lt;=10^3;</p>
</div>
</div>