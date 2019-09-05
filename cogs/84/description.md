# 题目描述


<p>
	<b>【问题描述】</b> 
</p>
<div align="left">
	用 N*N(1&lt;=N&lt;=8) 的格点阵代表海，其中 * 代表岛。给你一组编码信息，让你重构一张地图。这组信息是按垂直方向、水平方向岛的分布情况摘取的。下例中，每行右边的数字按顺序表示该行中“岛组”的大小，如第一行数字为“ 1 2 ”，表示该行第一“岛组”由一个岛组成，第二“岛组”由两个岛组成，而第四列下面的“ 2 3 ”则表示本列由两个“岛组”组成，第一个“岛组”由两个岛组成，第二个“岛组”由三个岛组成。
</div>
<p align="left">
	<br/>
</p>
<p align="left">
	<img alt="" src="/mw/images/5/54/Island.gif" height="238" width="352"/> 
</p>
<p align="left">
	现要求你编程解决下列问题：
</p>
<p align="left">
	<strong>任务 </strong> 
</p>
<p align="left">
	读取一个信息块，根据信息块重构地图（若有多个解，逐个构成地图）。
</p>
<p align="left">
	<strong>【输入<b>格式】</b></strong> 
</p>
<p align="left">
	第一行：N N表示格点阵大小（N&lt;=8）
</p>
<p align="left">
	第2—N+1 行岛组信息
</p>
<p align="left">
	第N+2—2N+1 列岛组信息
</p>
<p align="left">
	<span style="font-family:Microsoft YaHei;font-size:16px;color:#E53333;">***所有的島組信息都是以0結尾。</span> 
</p>
<p align="left">
	<br/>
</p>
<p align="left">
	<strong>【输出<b>格式】</b></strong> 
</p>
<p align="left">
	第一行：岛组编号
</p>
<p align="left">
	第2—N+1行：*号表示的地图
</p>
<p align="left">
	若有多个解时，按上面格式依次输出（输出顺序按地图中最上，最左边的*号位置（i,j）由小到大排序，i是第一关键字，j是第二关键字）
</p>
<p align="left">
	若无解时,输出&#39;no&#39;.
</p>
<p align="left">
	<strong>【输入输出样例<b>】</b></strong> 
</p>
<p align="left">
	输入：
</p>
<p>
	island.in
</p>
<p align="left">
	8 <br/>
1 1 1 1 0 <br/>
1 1 1 1 0 <br/>
1 1 1 1 0 <br/>
1 1 1 1 0 <br/>
1 1 1 1 0 <br/>
1 1 1 1 0 <br/>
1 1 1 1 0 <br/>
1 1 1 1 0 <br/>
1 1 1 1 0 <br/>
1 1 1 1 0 <br/>
1 1 1 1 0 <br/>
1 1 1 1 0 <br/>
1 1 1 1 0 <br/>
1 1 1 1 0 <br/>
1 1 1 1 0 <br/>
1 1 1 1 0
</p>
<p align="left">
	输出：
</p>
<p align="left">
	island.out
</p>
<p align="left">
	1 <br/>
* * * * <br/>
 * * * * <br/>
* * * * <br/>
 * * * * <br/>
* * * * <br/>
 * * * * <br/>
* * * * <br/>
 * * * * <br/>
2 <br/>
 * * * * <br/>
* * * * <br/>
 * * * * <br/>
* * * * <br/>
 * * * * <br/>
* * * * <br/>
 * * * * <br/>
* * * *
</p>
