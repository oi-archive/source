# 题目描述


<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;"></span><span style="font-family:Microsoft YaHei;font-size:16px;">【题目描述】</span> 
</h3>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">DaA 有一个弹性小球，小球有一个能量值E。<br/>
DaA 走进一个M*N 房间，房间有M 行N 列。<br/>
一开始在左上角，以向右下角45°的方向弹射小<br/>
球。小球有两个性质：</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">1. 小球在运动过程中不会损失能量，只有在<br/>
碰壁或碰角的时候才会损失能量，能量&lt;=0 了小球<br/>
就停止运动了；<br/>
2. 小球弹射遵循反射定律，小球碰角会原路<br/>
返回（请参照右边图画）。<br/>
请聪明的你告诉DaA 弹性小球在这个房间中的运动轨迹。</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;"><img src="/upload/image/20121026/20121026103221_57502.jpg" alt=""/><br/>
</span> 
</p>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【输入格式】</span> 
</h3>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">第一行三个整数M、N、E，表示房间的行数和列数、小球的初始能量。<br/>
第二行八个整数，分别是小球撞到上（北）、右（东）、下（南）、左（西）、左上（西北）、<br/>
右上（东北）、右下（东南）、左下（西南）损失的能量。</span> 
</p>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【输出格式】</span> 
</h3>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">输出一张小球运动的轨迹图（详见样例）。轨迹图要求如下：<br/>
1. 整个(M+2)*(N+2)的图，外面要有边框，上下各N 个&#39;-&#39;，左右各M 个&#39;|&#39;；<br/>
2. 小球运动轨迹用&#39;/&#39;和&#39;\&#39;表示，其他部分用&#39; &#39;表示。</span> 
</p>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【样例】</span> 
</h3>
<pre>Sample Input 1:
2 2 5
2 3 4 6 1 1 3 9
Sample Input 2:
3 5 6
1 1 1 1 1 1 1 1
Sample Output 1:
 --
|\ |
| \|
 --
Sample Output 2:
 -----
|\/ /\|
|/\/ /|
|\/\/ |
 ----- 
</pre>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【数据规模】</span> 
</h3>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">30%的数据 1&lt;=M,N&lt;=10，0<e<=30。< span=""> </e<=30。<></span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">100%的数据 1&lt;=M,N&lt;=100，0<e<=109。< span=""> </e<=109。<></span> 
</p>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;"></span> 
</h3>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【来源】</span> 
</h3>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;"><span style="font-family:Microsoft YaHei;font-size:16px;">清北学堂2012寒假培训 Test2</span></span> 
</p>
