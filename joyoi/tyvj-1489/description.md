# 

 
 # 题目描述 
第一次到济南坐公交车，dxhisboy崩溃了……从济南火车站到jesful所在的SDUQLSCACMLAB……囧啊，要换乘各种公交车进城到那里。他途中可以换乘n个车站，每个车站会在某些固定的时间来一辆车，并且可以把dxhisboy带到另一个车站。问dxhisboy最早可以什么时候时间到达SDUQLSCACMLAB，dxhisboy凭借庞大的身躯挤公交的水平保证他上下车的时间可以忽略。火车站在车站1,SDUQLSCACMLAB在车站n。 

 
 # 输入格式 
第一行：四个整数n如题目所述，m为公交车辆数，t表示dxhisboy到达火车站的时间（2011年2月28日t秒）。<BR>剩下m行，每行4个整数：a，b，c，d表示这天中的第c秒会从a车站发出一辆公交在第d秒把dxhisboy送达b。 

 
 # 输出格式 
一个数，代表dxhisboy到达SDUQLSCACMLAB的最早可能时间。 

 
 # 提示 
30%的数据，n&lt;=10,m&lt;=100<BR>	100%的数据，n&lt;=100,m&lt;=10000<BR>	所有数据保证dxhisboy可以当天到达SDUQLSCACMLAB，所有车次到达时间大于等于出发时间<BR>	不保证两站之间最多有一趟车。 
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
<tr><td>3 3 20000
1 2 20001 20005
2 3 20004 20006
2 3 20005 20007</td><td>20007</td></tr></table>
