# 题目描述


<p>
	<span style="font-weight:bold;font-size:14px;font-family:&#39;Microsoft YaHei&#39;;">【问题描述】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">毕业</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">25</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">年以后，我们的主人公开始准备同学聚会。打了无数电话后他终于搞到了所有同学的地址。他们有些人仍在本城市，但大多数人分散在其他的城市。不过，他发现一个巧合，所有地址都恰好分散在一条铁路线上。他准备出发邀请但无法决定应该在哪个地方举行宴会。最后他决定选择一个地点，使大家旅行的花费和最小。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:14px;font-family:&#39;Microsoft YaHei&#39;;">不幸的是，我们的主人公既不擅长数学，也不擅长计算机。他请你帮忙写一个程序，根据他同学的地址，选择聚会的最佳地点。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-weight:bold;font-size:14px;font-family:&#39;Microsoft YaHei&#39;;">【输入】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:14px;font-family:&#39;Microsoft YaHei&#39;;">输入文件的每一行描述了一个城市的信息。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">首先是城市里同学的个数，紧跟着是这个城市到</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">Moscow</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">（起点站）的距离（</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">km</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">），最后是城市的名称。最后一行描述的总是</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">Moscow</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">，它在铁路线的一端，距离为</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">0</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">。城市数不超过50000个。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-weight:bold;font-size:14px;font-family:&#39;Microsoft YaHei&#39;;">【输出】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">聚会地点城市名称和旅行费用（单程），两者之间用一空格隔开。每</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">km</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">花费一个卢布。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-weight:bold;font-size:14px;font-family:&#39;Microsoft YaHei&#39;;">【样例】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:14px;font-family:&#39;Microsoft YaHei&#39;;">reunion.in</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:14px;font-family:&#39;Microsoft YaHei&#39;;">7 9289 Vladivostok</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:14px;font-family:&#39;Microsoft YaHei&#39;;">5 8523 Chabarovsk</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:14px;font-family:&#39;Microsoft YaHei&#39;;">3 5184 Irkutsk</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:14px;font-family:&#39;Microsoft YaHei&#39;;">8 2213 Yalutorovsk</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:14px;font-family:&#39;Microsoft YaHei&#39;;">10 0 Moscow</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><br/>
</span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:14px;font-family:&#39;Microsoft YaHei&#39;;">reunion.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:14px;font-family:&#39;Microsoft YaHei&#39;;">Yalutorovsk 112125</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<br/>
</p>
