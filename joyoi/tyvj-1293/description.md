# 

 
 # 题目背景 
"红豆拆两半，一半以相思，一半以定情。"小v听了这个古老的传说后决定去红豆园里采最美的红豆，当做定情信物。<BR> 

 
 # 题目描述 
红豆园里有n棵红豆，其中若干对红豆间有一些无向的道路连接。小v现在站在编号为p的红豆边，而他的心上人站在编号为q的红豆边，小v向尽快赶过去和她会合。但红豆园里有一个诅咒，那些采红豆时走最短路径的懒惰者将永远得不到爱神丘比特的眷顾，你能帮小v想个办法吗？(数据保证有解)<BR> 

 
 # 输入格式 
第一行四个整数n，m，q，p，分别代表有n个红豆（编号分别为1到n），m条路径，q和p如题所示。<BR>接下来有m行数据，每行三个数x，y，z，表示编号为x和编号为y的红豆间有道路相连，长度为z<BR><BR> 

 
 # 输出格式 
一个整数s，表示小v赶到心上人旁边的而又不受诅咒的最短距离<BR>如果小v只能冒着诅咒赶过去，就输出"He&nbsp;will&nbsp;be&nbsp;cursed"<BR>如果小v赶不到她旁边，就输出"He&nbsp;lose&nbsp;his&nbsp;love"<BR>（引号不输出）<BR><BR> 

 
 # 提示 
数据范围：<BR>对于40%的数据，0&lt;n&lt;=50,0&lt;m&lt;=200<BR>对于100%的数据，0&lt;n&lt;=1000,0&lt;m&lt;=2000<BR><BR> 
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
<tr><td>5 7 1 4
1 2 2
1 3 2
2 5 2
2 3 3
3 5 4
3 4 3
4 5 2

</td><td>6
</td></tr></table>
