<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在幻想乡，东风谷早苗是以高达控闻名的高中生宅巫女。某一天，早苗终于入手了最新款的钢达姆模型。作为最新的钢达姆，当然有了与以往不同的功能了，那就是它能够自动行走，厉害吧（好吧，我自重）。早苗的新模型可以按照输入的命令进行移动，命令包含’E’、’S’、’W’、’N’四种，分别对应四个不同的方向，依次为东、南、西、北。执行某个命令时，它会向着对应方向移动一个单位。作为新型机器人，自然不会只单单执行一个命令，它可以执行命令串。对于输入的命令串，每一秒它会按照命令行动一次。而执行完命令串最后一个命令后，会自动从头开始循环。在0时刻时早苗将钢达姆放置在了(0,0)的位置，并且输入了命令串。她想要知道T秒后钢达姆所在的位置坐标。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：一个字符串，表示早苗输入的命令串，保证至少有1个命令</p>
<p>第2行：一个正整数T</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第1行：两个整数，表示T秒时，钢达姆的坐标</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>NSWWNSNEEWN</p>
<p>12</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>-1 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="581">
<p>对于60%的数据：T &lt;= 500,000且命令串长度 &lt;= 5,000</p>
<p>对于100%的数据：T &lt;= 2,000,000,000且命令串长度&lt;= 5,000</p>
</td>
</tr>
<tr>
<td valign="top" width="581">
<p>向东移动，坐标改变改变为(X+1,Y);</p>
<p>向南移动，坐标改变改变为(X,Y-1);</p>
<p>向西移动，坐标改变改变为(X-1,Y);</p>
<p>向北移动，坐标改变改变为(X,Y+1);</p>
</td>
</tr>
</tbody>
</table>
</div>
</div>