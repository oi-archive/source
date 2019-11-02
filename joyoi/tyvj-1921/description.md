# 

 
 # 题目描述 
Freda的旅行社开通了一条暑期旅行路线，路线可以被看成是一条直线。这条路线一共经过N个地区，N个地区的管辖范围完全覆盖了整条旅行路线且管辖范围之间两两没有重合。<BR>我们知道，地区与地区之间的气温可能是不同的，第i个地区的气温设为ti.报名旅行的M名游客都要乘车从第1个地区前往第N个地区,每辆车的容量没有限制。当然，谁也不想让自己乘坐的车里温度太高。假设经过第i个地区的时候，一辆车上面有k名乘客，那么这辆车上的温度就是ti+k。如果某辆车上的温度超过了这个地区的“最热限制”Ti(ti+k&gt;Ti)，这辆车上的每个乘客都会向旅行社索赔xi元钱，用法律武器维护自己合法权益。<BR>还有很特殊的一点，游客所乘坐的车不是从1~N直达的，而是在各个地区分别租用的。在第i个地区租用的车只能在第i个地区的管辖范围内行驶。即进入第i个地区时，租用第i个地区的车，离开第i个地区时，就要继续租用第i+1个地区的车。在第i个地区，你可以租用任意数量的车，租用一辆车的费用是ci。<BR>下面，Freda请你帮忙设计一个花费最小的方案，即设计在每个地区的租车数目以及此时安排到每辆车上的乘客数目。这个方案的花费是租车费用+给乘客的赔偿金（如果有的话）,输出这个最小花费。 

 
 # 输入格式 
第一行两个整数N，M，表示地区数目和乘客数目。<BR>接下来N行每行4个整数，第i行的4个整数表示ti,Ti,xi,ci.含义如上所示。 

 
 # 输出格式 
一行一个整数表示最小花费。 

 
 # 提示 
样例解释<BR>在第1个地区，租用1辆车，车内温度为30+10=40&gt;35，需要给乘客每人1元补偿费。<BR>在第2个地区，租用1辆车，车内温度为20+10=30&lt;35，不需要给乘客补偿费。<BR>总费用为100（第一个地区的租车费用）+10（第二个地区的租车费用）+10（第一个地区的补偿费用）=120.<BR>数据范围与约定<BR>对于50%的数据，N&lt;=100,&nbsp;M&lt;=100.<BR>对于100%的数据，0&lt;N&lt;=10^5,&nbsp;0&lt;M&lt;=10^6,&nbsp;0&lt;xi,ci,ti,Ti&lt;=10^6.Description&nbsp;From&nbsp;/&nbsp;Translated&nbsp;by&nbsp;-&nbsp;This_poet<BR>Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<BR>This_poet's&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com 
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
<tr><td>2 10
30 35 1 100
20 35 10 10</td><td>120</td></tr></table>
