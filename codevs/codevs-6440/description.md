<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>        在东方永夜抄符卡练习中的Last Word模式第217号符卡叫“收缩的世界”，使用者是十六夜咲夜。其原理是当咲夜停止时间时，所有蓝色的飞刀会沿直线延长穿过屏幕。现在你用雾雨魔理沙作为自机打这张符。假设游戏范围在平面直角坐标系中第一象限的按每一个单位分隔开的网格，如图，咲夜在里面放了一些飞刀。然后时间暂停，此时相当于很多条直线在同一个网格内。魔胖子的判定点特别大，有一整个小方格这么大，她必须躲在一个不会被飞刀打到的方格内。咲夜飞刀是直线，用一次函数解析式表示。如果飞刀穿过了某个方格（即使只是擦到角），魔理沙也是躲不开的。现在你要编程帮魔理沙算一下她有多少个方格好躲。太遗憾了，图发不上去，只能看你的悟性了。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行正整数n,m,表示网格的大小和飞刀的数目。<br></p><p>后面m行每行两个实数k,b,表示飞刀所在直线的解析式y=kx+b.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行一个正整数，表示魔理沙能躲的方格的数目。<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 2 <br></p><p>1 0<br></p><p>-0.5 4</p>

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
<p>对于100%的数据，n,m&lt;=50,-10000&lt;=k,b&lt;=10000,k不等于0,如图，打星的方格就是魔理沙可以躲的方格。</p>
</div>
</div>