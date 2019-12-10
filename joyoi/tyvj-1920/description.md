# 

 
 # 题目描述 
【问题描述】<BR>&nbsp;&nbsp;&nbsp;&nbsp;设T=(V,&nbsp;E,&nbsp;W)&nbsp;是一个无圈且连通的无向图（也称为无根树），每条边带有正整数的权，我们称T为树网（treenetwork），其中V,&nbsp;E分别表示结点与边的集合，W表示各边长度的集合，并设T有n个结点。<BR>&nbsp;&nbsp;&nbsp;&nbsp;路径：树网中任何两结点a,b都存在唯一的一条简单路径，用d(a,b)表示以a,b为端点的路径的长度，它是该路径上各边长度之和。我们称d(a,b)为a,b两结点间的距离。<BR>&nbsp;&nbsp;&nbsp;&nbsp;一点v到一条路径P的距离为该点与P上的最近的结点的距离：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d(v，P)=min{d(v，u)，u为路径P上的结点}。<BR>&nbsp;&nbsp;&nbsp;&nbsp;树网的直径：树网中最长的路径称为树网的直径。对于给定的树网T，直径不一定是唯一的，但可以证明：各直径的中点（不一定恰好是某个结点，可能在某条边的内部）是唯一的，我们称该点为树网的中心。<BR>&nbsp;&nbsp;&nbsp;&nbsp;偏心距ECC(F)：树网T中距路径F最远的结点到路径F的距离，&nbsp;即<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ECC(F)=max{d(v,F),v∈V}.<BR>&nbsp;&nbsp;&nbsp;&nbsp;任务：对于给定的树网T=(V,&nbsp;E,W)和非负整数s，求一个路径F，它是某直径上的一段路径（该路径两端均为树网中的结点），其长度不超过s（可以等于s），使偏心距ECC(F)最小。我们称这个路径为树网T=(V,E,W)的核（Core）。必要时，F可以退化为某个结点。一般来说，在上述定义下，核不一定只有一个，但最小偏心距是唯一的。<BR>&nbsp;&nbsp;&nbsp;&nbsp;下面的图给出了树网的一个实例。图中，A-B与A-C是两条直径，长度均为20。点W是树网的中心，EF边的长度为5。如果指定s=11，则树网的核为路径DEFG（也可以取为路径DEF），偏心距为8。如果指定s=0（或s=1、s=2），则树网的核为结点F，偏心距为12。<BR><img src="/source/joyoi/tyvj-1920/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTkyMC8mbmJzcDtodHRwOi8veXQudHl2ai5jbjo4MDgwL1Byb2JsZW1JbWcvUDEwNzMuanBn.jpg" border=0 align=middle><BR><BR><BR> 

 
 # 输入格式 
&nbsp;&nbsp;输入文件包含n行：<BR>&nbsp;&nbsp;&nbsp;&nbsp;第1行，两个正整数n和s，中间用一个空格隔开。其中n为树网结点的个数，s为树网的核的长度的上界。设结点编号依次为1,&nbsp;2,&nbsp;...,&nbsp;n。<BR>&nbsp;&nbsp;&nbsp;&nbsp;从第2行到第n行，每行给出3个用空格隔开的正整数，依次表示每一条边的两个端点编号和长度。例如，“2&nbsp;4&nbsp;7”表示连接结点2与4的边的长度为7。<BR>&nbsp;&nbsp;&nbsp;&nbsp;所给的数据都是正确的，不必检验。 

 
 # 输出格式 
输出文件只有一个非负整数，为指定意义下的最小偏心距。 

 
 # 提示 
【限制】<BR>&nbsp;&nbsp;&nbsp;&nbsp;40%的数据满足：5&lt;=n&lt;=15<BR>&nbsp;&nbsp;&nbsp;&nbsp;70%的数据满足：5&lt;=n&lt;=80<BR>&nbsp;&nbsp;&nbsp;&nbsp;100%的数据满足：5&lt;=n&lt;=300,&nbsp;0&lt;=s&lt;=1000。边长度为不超过1000的正整数<BR><BR> 
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
<tr><td>5 2
1 2 5
2 3 2
2 4 4
2 5 3
</td><td>5
</td></tr></table>
