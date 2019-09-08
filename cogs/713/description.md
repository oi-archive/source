# 题目描述


<p>
	<span style="font-family:宋体;"><strong>问题描述：</strong></span> 
</p>
<p style="text-indent:35.45pt;">
	<span style="font-family:宋体;font-size:10.5pt;">yz</span><span style="font-family:宋体;font-size:10.5pt;">住宅小区的未来规划采用了一种新方案：小区由白色的木栅栏围成，栅栏的形状将被设计为一个任意多边形，而每户<img alt="" align="right" src="/cogs/images/upload/image/20120401/20120401085545_41363.bmp"/>的住宅就位于多边形的顶点处，多边形的内部则将建成一个优雅怡人的小区公园。</span> 
</p>
<p style="text-indent:35.45pt;">
	<span style="font-family:宋体;font-size:10.5pt;"><span></span></span> 
</p>
<p style="text-indent:35.45pt;">
	<span style="font-family:宋体;font-size:10.5pt;">这个方案却给负责小区送报任务的投递员带来了一些麻烦，因为他希望坚持自己的送报习惯：他喜欢骑在自己的自行车上沿着一个标准的圆形路线投送报纸，每当看到自己的右手方向有一户住宅时，他就会将报纸投过去，而且最令他骄傲的是，无论距离远近，他投出的报纸总是准确地落在住户的门前。他的这种极具艺术感的服务方式也正是住户们最感欣赏的地方。</span> 
</p>
<p style="text-indent:35.45pt;">
	<span style="font-family:宋体;font-size:10.5pt;"></span> 
</p>
<p style="text-indent:35.45pt;">
	<span style="font-family:宋体;font-size:10.5pt;">但遗憾的是，他分辨不出每户住宅之间的区别，也记不住每家订了哪些报纸，邮局按照住宅在多边形上的次序把每户的报纸交给他，他就按照这种次序把每户的报纸投送出去。所以图一中的方案是不成立的，因为住户<span>3</span>拿到的总是住户<span>2</span>的报纸，而住户<span>2</span>拿到的报纸却是住户<span>3</span>的。图二中画出了两种可行的方案。<span></span></span> 
</p>
<p style="text-indent:35.45pt;">
	<span style="font-family:宋体;font-size:10.5pt;">你的任务就是找出所有满足上述要求的投递路线的圆心（这些圆心的坐标应当是整数）。<span></span></span> 
</p>
<p>
	<span style="font-family:宋体;font-size:10.5pt;"></span> 
</p>
<p style="text-indent:-21.5pt;margin-left:21.5pt;">
	<b><span style="font-family:宋体;">输入格式<span>(</span></span></b><span style="font-family:宋体;">polygon.in)</span><b><span style="font-family:宋体;">：<span></span></span></b> 
</p>
<p style="margin-left:21.5pt;">
	<span style="font-family:宋体;font-size:10.5pt;">输入文件名为<span>polygon.in</span>。文件第<span>1</span>行是<span>4</span>个整数<span>x<sub>min</sub></span>、<span>x<sub>max</sub></span>、<span>y<sub>min</sub></span>、<span>y<sub>max</sub></span>，表示圆心坐标的范围，第<span>2</span>行是一个正整数<span>n(n</span></span><span style="font-family:Symbol;font-size:10.5pt;"><span>£</span></span><span style="font-family:宋体;font-size:10.5pt;">100)</span><span style="font-family:宋体;font-size:10.5pt;">，表示多边形的顶点数，从第<span>3</span>行至第<span>n+2</span>行是每个顶点的坐标<span>(x,y)</span>，所有坐标值均为整数，坐标的绝对值不大于<span>1000</span>，顶点按顺时针排序。<span></span></span> 
</p>
<p style="text-indent:-21.5pt;margin-left:21.5pt;">
	<br/>
</p>
<p>
	<span></span> 
</p>
<p>
	<span></span> 
</p>
<p>
	<span></span> 
</p>
<p>
	<span></span> 
</p>
<p>
	<span></span> 
</p>
<p>
	<span></span> 
</p>
<p>
	<span></span> 
</p>
<p>
	<span></span> 
</p>
<p>
	<span></span> 
</p>
<p>
	<span></span> 
</p>
<b><span style="font-family:宋体;">输出格式<span>(</span></span></b><span style="font-family:宋体;">polygon.out)</span><b><span style="font-family:宋体;">：<span></span></span></b> 
<p>
	<br/>
</p>
<span style="font-family:宋体;font-size:10.5pt;">输出文件名为<span>polygon.out</span>。文件中共<span>m</span>行（<span>m</span>为你求出的圆心的个数），每行两个整数<span>(x,y)</span>，表示圆心的坐标，坐标应按<span>y</span>递增的次序输出，如果<span>y</span>相等的，应按<span>x</span>递增的次</span><span style="font-family:宋体;font-size:12pt;">序。</span> 
<p>
	<br/>
</p>
<p>
	<img alt="" src="/cogs/images/upload/image/20120401/20120401085625_98288.bmp"/> 
</p>
<p>
	<br/>
</p>
<p>
	<img alt="" src="/cogs/images/upload/image/20120401/20120401085927_30853.bmp"/> 
</p>
<p>
	<br/>
</p>
