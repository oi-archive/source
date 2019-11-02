<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在幻想乡中，蓬莱山辉夜是月球公主，居住在永远亭上，二次设定说她成天宅在家里玩电脑，亦称NEET姬<br> 一天，她要她帮忙升级月球的网络服务器，应为注册用户过多（月兔和地球上的巫女都注册了……），所以作为代理管理员（俗称网管）的她，非常蛋疼。<br> 注册用户格式：<br> TouhouMaiden 2004 200<br> 其中前面的Touhoumaiden是预设，不做更改，第一个数是标识，第二个数是每次接受信息访问的间隔用时。<br> 你要做的事，就是给定一群用户及n，求出这n次信息访问中，访问到了谁？</p>
<p>presented by Izayoi sakuya</p>

<img src="/source/codevs/codevs-2830/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yODMwL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8yODMwLmpwZw==.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>以题目预设格式输入，另起一行以‘#’结束，在其一行输入n</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>n行，每行输出第行次后，信息访问到了谁？若在一个时间有若干少女被访问到，输出字典序最小的那位少女的标识</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>TouhouMaiden 2004 200</pre>
<pre>TouhouMaiden 2005 300</pre>
<pre>#</pre>
<pre>5</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>2004
2005
2004
2004
2005</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>标识和每次信息访问间隔均在integer内，n&lt;=10000</p>
<p>原本是要用到堆，但深搜+时间即可搞定</p>
<p>数据有点少但也都够变态了</p>
</div>
</div>