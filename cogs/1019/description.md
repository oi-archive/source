# 题目描述


<p>
	<span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">】</span></span>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">夏天，也许大家热爱在水中畅游，体验炎炎夏日中难得的清爽。可是，游泳运动中的事故也是层出不穷的。因此，游泳馆设计了一套救援方案，请你来帮忙进行评估。</span>
</p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 游泳池可以看成一个二维平面。当且仅当一个点的横纵坐标都为整数的时候，这个点为整点。平面当中每个整点上都有一名游泳的同学，他们的移动忽略不计。救生员同样处于整点位置上。由于不同的救生员能力不同，他们所能够保护的范围形状、大小也是不一样的。救生员的保护范围有三角形、正方形、圆形三种形状。现在，给出N名救生员的保护范围，如果一个同学在某一个救生员的保护范围内，那么这个同学是被保护的。请你计算能够被保护的同学人数。数据保证每个救生员的保护面积大于0.</span><br/>
<p>
	<img src="http://file-02.blogcn.com/wp02/M00/05/F7/wKgKC1ArYvoAAAAAAABxDVK7oEk466.jpg" alt=""/>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">】</span>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第一行一个整数N，表示救生员的人数。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">接下来N行描述N个救生员的保护范围：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">如果这个救生员的保护范围是三角形，那么将输入&#34;T x1 y1 x2 y2 x3 y3&#34;，其中，(x1,y1）、（x2,y2)、(x3,y3)是三角形的三个顶点坐标。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">如果这个救生员的保护范围是圆形，那么将输入&#34;C x y r&#34;，其中，(x,y)是圆心，r是圆的半径。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">如果这个救生员的保护范围是正方形，那么将输入&#34;S x y l&#34;，其中，(x,y)是正方形左下角坐标，l是正方形的边长。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">特别地，如果一个整点在图形的边界上，在这个点上的同学将被认为是被保护的。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">】</span>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">一行一个整数，表示被保护的同学的人数。</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"></span>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输入</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">】</span>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">C 10 10 3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">S 9 8 4</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">T 7 9 10 8 8 10</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输出</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">】</span>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">34</span><br/>
	</p><p>
		<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【提示】</span>
	</p>
	<p>
		<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">样例解释：如图所示，红色的点表示被保护的同学。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于100%的数据，所有数字均为正整数且不大于50.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于70%的数据，救生员保护范围只有圆形和正方形。</span>
	</p>
	<p>
		<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【时间限制】</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"></span>
	</p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">每个测试点1s</span>
<p></p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【来源</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">】</span>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">From - This_poet</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Contact me - This_poet@126.com / Freda.RD.Shi@gmail.com</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">This_poet&#39;s Blog - http://thispoet.blogcn.com</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"></span>
</p>
