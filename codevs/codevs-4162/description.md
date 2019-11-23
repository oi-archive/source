<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>无双大王hzwer扫清六合，席卷八荒，万姓倾心，四方仰德。</p><p>hzwer拥有一片领土，其中有n个城市和m条双向道路。他规定每个人在领土上行走都要交过路费，同时进城也要交进城费。不同道路的过路费可能不同，不同城市的进城费可能不同。但是hzwer规定，如果缴纳x的进城费，那么所有小于x的进城费就不用缴纳了。（即只缴纳一条路径上的所有过路费和最大的进城费）那么从s城市出发到t城市，要缴纳多少费用？（s城市和t城市进城费也要算）</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个数n,m,q。表示n个城市m条路q个询问。</p><p>接下来n个数，表示n个城市的进城费。</p><p>接下来m行，每行3个数，表示一条路径的两端和过路费。</p><p>接下来q行，每行两个数s,t，表示询问从s到t的最小花费。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size:16px;font-family:宋体">对于每个询问，输出一行表示最小花费。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 7 2<br> 2 5 3 3 4<br> 1 2 3<br> 1 3 2<br> 2 5 3<br> 5 3 1<br> 5 4 1<br> 2 4 3<br> 3 4 4<br> 1 4<br> 2 3</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8<br></p><p>9</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%数据，1&lt;=n&lt;=10.<br></p><p>对于60%数据，1&lt;=n&lt;=100.</p><p>对于100%数据，1&lt;=n&lt;=250,1&lt;=m,q&lt;=10000</p><p><br></p><p>比赛已结束 详细解析见题解</p>
</div>
</div>