# 

 
 # 题目描述 
<p>
　　毕业25年以后，我们的主人公开始准备同学聚会。打了无数电话后他终于搞到了所有同学的地址。他们有些人仍在本城市，但大多数人分散在其他的城市。不过，他发现一个巧合，所有地址都恰好分散在一条铁路线上。他准备出发邀请但无法决定应该在哪个地方举行宴会。最后他决定选择一个地点，使大家旅行的花费和最小。<br>　　不幸的是，我们的主人公既不擅长数学，也不擅长计算机。他请你帮忙写一个程序，根据他同学的地址，选择聚会的最佳地点。<br></p> 

 
 # 输入格式 
<p>
　　输入文件的每一行描述了一个城市的信息。<br>　　首先是城市里同学的个数，紧跟着是这个城市到Moscow（起点站）的距离（km），最后是城市的名称。最后一行描述的总是Moscow，它在铁路线的一端，距离为0。<br><br>注：城市总数不大于300。</p> 

 
 # 输出格式 
<p>
　　旅行费用（单程，每km花费一个卢布）。</p> 

 
 # 提示 
<p>
【问题分析】<br>　　中位数问题。找这样一个点(城市)——它左边的人数与右边的人数差的绝对值最小。时间复杂度为O(n)。<br></p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>7 9289 Vladivostok					
5 8523 Chabarovsk
3 5184 Irkutsk
8 2213 Yalutorovsk
10 0 Moscow
</td><td>112125</td></tr></table>
