# 

 
 # 题目背景 
Sandytea前段时间沉迷于QQ农场中……一天夜里，他梦见来到好友X的农场上…… 

 
 # 题目描述 
这个农场和游戏中略有不同。土地实际上是一个边长为N的正方形，由N*N块土地组成。<BR>在每块土地上，都种有一种农作物。如果他选择摘取一块土地上的农作物，就能获得一个固定的利润(当然，这个利润是正数)。不同土地上的利润多半是不同的。<BR>贪心的Sandytea本想摘取所有土地上的农作物。但是正当他准备行动时，却被告知不允许摘取了两块有公共边的土地上的作物，否则就会被主人的狗发现。<BR>Sandytea想知道，在不被狗抓住的前提下，他能获得的最大利益是多少。 

 
 # 输入格式 
第一行：一个整数N，表示土地是一个边长为N的正方形。<BR>下面N行：每行N个正整数，描述了各块土地上的农作物的单位价值。 

 
 # 输出格式 
输出一行，包含一个整数，为最大的收益。 

 
 # 提示 
数据范围：<BR>有10分的数据满足：N≤6<BR>另有20分的数据满足：N≤13<BR>另有30分的数据满足：N≤50<BR>另有40分的数据满足：N≤200<BR>所有数据满足：每块土地上作物的价值不超过100。改编自SPOJ 
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
<tr><td>2
7 7
54 54
</td><td>61
</td></tr></table>
