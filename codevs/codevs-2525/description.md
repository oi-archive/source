<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在野外生存中 以最快、最省力的方式收集必要的生存资源是必须的。在这次生存训练的尾声<span style="">给队员们的最后考核就是收集资源竞赛，要求队员们在限定时间内收集到最多的资源。</span></p>
<p><span style="">小龙抽到的地图是震后城市生存资源收集模拟 教官为小龙发了一张地图 地图上的南北和东西方向各有N条间距相等的街道</span></p>
<p><span style="">如果街道的交叉点即路口上标注着红点和数字这代表该路口有一定量的资源可以收集 否则表示该路口没有资源。</span></p>
<p><span style="">小龙决定利用赛前准备时间好好研究一下行走路线</span></p>
<p><span style="">根据地图上的比例尺提示 他知道从模拟城市的一个路口走到临近的下一个路口 大概需要1分钟 而需要收集的资源就放在路口中心拿起来就可以继续行进 因此行走需要时间而收集资源的时间是可以忽略不计的。请为小龙设计一个行走方案使得他在限定时间内能收集到最多的资源。 </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>共M+1行第一行为三个整数NMT1≤N,M,T≤200中间用空格分开分别为地图大小N有资源的路口的数量M和收集资源的时间T分钟。接下来M行每行三个整数Xi、Yi、Vi(中间用空格分开且均为整数)Xi、Yi为第i个有资源的地点的坐标0≤Xi,Yi≤N-1Vi为第i个地点拥有资源的数量1≤Vi≤200</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个正整数在时间T分钟内可收集到的最多资源总数</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8 8 10</p>
<p>1 1 3</p>
<p>2 2 4</p>
<p>3 3 5</p>
<p>3 4 3</p>
<p>4 3 2</p>
<p>4 4 6</p>
<p>5 5 7</p>
<p>6 6 8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>28</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>50%的数据 1≤N,M,T≤100</p>
<p>100%的数据 1≤N,M,T≤20</p>
</div>
</div>