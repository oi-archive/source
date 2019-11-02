# 

 
 # 题目背景 
清北学堂杯Tyvj2周年邀请赛&nbsp;第一道 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;为了Tyvj2周年邀请赛，Admin有N个物品，他们分别放到了N个大小相同的盒子中，由于某种原因，Admin只想选择其中的一些作为比赛的奖品，但是由于物品数量太多，所以请你写一个程序来帮帮他吧！Admin一共需要以下功能：<BR>1.查询是否有物品被选择（初始状态下所有物品都没有被选择）<BR>2.当前选择了多少物品<BR>3.查询编号为id的物品选择情况<BR>4.将编号为id的物品选择情况取反（原先选择变为不选择，原先不选择变为选择）<BR> 

 
 # 输入格式 
第一行N，M，表示有N个物品，M个操作<BR>下面共M行，每一行描述一个操作<BR>如果这行是”any”，则表示第一个操作<BR>如果这行是”count”，则表示第二个操作<BR>如果这行是”find”+id，则表示第三个操作<BR>如果这行是”filp”+id，则表示第四个操作<BR> 

 
 # 输出格式 
每个第一、二、三操作，都需要输出一行。对于第一个询问，输出T或者F分别表示有和无，第二个操作输出一个数，第三个操作输出T或F，分别表示选择和没有选择。 

 
 # 提示 
【数据范围】<BR>30%的数据，n&lt;=100<BR>100%的数据,n&lt;=10^15,m&lt;=100,0&lt;id&lt;=n 
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
<tr><td>10 8
any
filp 1
filp 2
count
any
find 2
filp 2
find 2
</td><td>F
2
T
T
F
</td></tr></table>
