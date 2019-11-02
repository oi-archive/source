<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>宇宙旅行总是出现一些意想不到的问题，这次小可可所驾驶的宇宙飞船所停的空间站发生了故障，这个宇宙空间站非常大，它由N个子站组成，子站之间有M条单向通道，假设其中第i（1＜＝i＜＝M）条单向通道连接了xi，yi两个中转站，那么xi子站可以通过这个通道到达yi子站，如果截断这条通道，需要代价ci。现在为了将故障的代价控制到最小，小可可必须想出一个截断方案，使a站不能到达b子站，并且截断的代价之和最小。我们称之为最小截断，小可可很快解决了这个故障，但是爱思考的小可可并不局限于此，为了今后更方便的解决同类故障，他考虑对每条单向通道：<br> 1，是否存在一个最小代价路径截断方案，其中该通道被切断？<br> 2，是否对任何一个最小代价路径切断方案，都有该通道被切断？<br> 聪明的你能帮小可可解决他的疑问吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行                      有4个整数，依次为N，M，a和b；<br>第二行到第(m+1)行   每行3个正整数x，y，c表示x子站到y子站之间有单向通道相连，单向通道的起点是x终点是y，切断它的代价是c（1≤c≤10000）；两个子站之间可能有多条通道直接连接。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对每一个单向通道，按输入的顺序，依次输出一行包含两个非0即1的整数，分别表示对问题一和问题二的回答（其中1表示是，0表示否）。每行两个整数之间用一个空格分隔开。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 7 1 6 <br>1 2 3<br>1 3 2<br>2 4 4 <br>2 5 1<br>3 5 5 <br>4 6 2<br>5 6 3<br> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 0<br> 1 0<br> 0 0<br> 1 0<br> 0 0<br> 1 0<br> 1 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>100％的数据中，N≤4000，M≤60000<br>  70％的数据中，N≤1000，M≤40000<br>  40％的数据中，n≤200，M≤2000</p>
</div>
</div>