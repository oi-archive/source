<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一个著名的仓库管理公司＊<span>ERKOI</span>请你的公司为其安装一套闭路监视系统。由于<span> SERKOI</span>财力有限，每个房间只能安装一台摄像机作监视用，不过它的镜头可以向任意方向旋转。</p>
<p>首要的问题是确定摄像机的位置以确保房间的每一个角落都能被它监视到。每个房间用一个封闭的多边形表示，图中的每条边表示一面墙。</p>
<p>写一个程序，对于给定的房间示意图，判断是否有可能在这个房间中的某一位置安置一台摄像机，使其能监视到这个房间的任何一个角落。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件包含一个或多个房间示意图的描述信息。每个描述信息的第一行是一一个正整数<span>n</span>（<span>4</span>＜<span>=n</span>＜<span>=100</span>），表示该房间的示意图为一个<span>n</span>边形。以下<span>n</span>行每行包括用空格符隔开的两个整数<span>x,y,</span>按顺时针方向依次为这个<span>n</span>边形的<span>n</span>个顶点在直角坐标系中的的横纵坐标，<span>x,y,</span>的范围在：<span>-1000</span>至<span>1000</span>之间。若<span>n</span>等于<span>0</span>则表示输入文件结束。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个房间，首先输出一行该房间的编号信息&ldquo;Room ＃k：&rdquo;，k按照输入次序从1开始计数。紧接着一行是判断结果，如果摄像机在房间中某处安置能满足条件，输出： &ldquo;surveillance is possible。&rdquo;，否则输出&ldquo;surveillance is impossible。&rdquo;&nbsp;每两个房间的输出结果之间用一个空行隔开。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>4</span></p>
<p><span>0 0</span></p>
<p><span>0 1</span></p>
<p><span>1 1</span></p>
<p><span>1 0</span></p>
<p><span>8</span></p>
<p><span>0 0 </span></p>
<p><span>3 0</span></p>
<p><span>4 3</span></p>
<p><span>2 2</span></p>
<p><span>3 4</span></p>
<p><span>4 4</span></p>
<p><span>4 5</span></p>
<p><span>0 5</span></p>
<p><span>0</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>Room #1:</span></p>
<p><span>Surveillance is possible.</span></p>
<p><span>Room #2:</span></p>
<p><span>Surveillance is impossible.</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>是ACM题改来的</p>
</div>
</div>