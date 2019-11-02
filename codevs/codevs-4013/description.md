<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<h2 style="">背景</h2><p>天好热……YJY顶着那炎炎的烈日，向Ice-cream home走去……<br>可是……停电了……<br>冰淇淋们躺在Ice-cream home的冰柜里，慢慢地……慢慢地……融化…………<br>你说，她能赶在冰淇淋融化完之前赶到Ice-cream home去吗？</p><h2 style="font-weight: normal;">描述</h2><p>给你一张坐标图，s为YJY的初始位置，m为Ice-cream home的位置，‘.’为路面，YJY在上面，每单位时间可以移动一格；‘#’为草地，YJY在上面，每两单位时间可以移动一格（建议不要模仿—毕竟YJY还小）；‘o’是障碍物，YJY不能在它上面行动。也就是说，YJY只能在路面或草地上行走，必须绕过障碍物，并到达冰淇淋店。但是……不保证到达时，冰淇淋还未融化，所以……就请聪明的你……选择最佳的方案啦……如果，YJY到的时候，冰淇淋已经融化完了，那她可是会哭的。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">依次输入冰淇淋的融化时间t(0&lt;t&lt;1000)，坐标图的长x,宽y(5&lt;=x,y&lt;=25){太长打起来好累……}，和整张坐标图。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &#39;Lucida Grande&#39;, Lucida, &#39;Lucida Sans Unicode&#39;, &#39;Lucida Sans&#39;, Tahoma, &#39;Segoe UI&#39;, Verdana, 微软雅黑, &#39;Microsoft YaHei&#39;, 宋体; font-size: 14px; line-height: 21px; background-color: rgb(255, 255, 255);">判断按照最优方案是否可以赶在冰淇淋融化之前到达冰淇淋店（注：当T=最优方案所用时间，则判断为未赶到），如赶到，输出所用时间；如未赶到，输出YJY的哭声——“55555”（不包括引号）。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>11</p><p>10</p><p>8</p><p>......s...</p><p>..........</p><p>#ooooooo.o</p><p>#.........</p><p>#.........</p><p>#.........</p><p>#.....m...</p><p>#.........</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>摘自vijos1340，有删改。</p><p>解题提示：用动态规划。</p><hr><p>YJY与LZC系列<br></p>
</div>
</div>