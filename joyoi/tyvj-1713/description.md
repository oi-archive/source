# 

 
 # 题目描述 
DaA和他的朋友组成一个团队去旅行了。他们每个人都准备了一个背包，用来装旅行用<BR>的物品。他们的背包有两个特点：<BR>1.每个人的背包能装无限多的物品，每种物品有一个价值，但只能装一件；<BR>2.每个人都很有个性，所以每个人的背包不会完全相同。<BR>DaA的团队中有M个人，那么对于整个团队，背包价值和最大是多少呢？ 

 
 # 输入格式 
第一行两个整数M、N，表示团队的人数和物品的数量。<BR>接下来一行N个整数，表示每件物品的价值wi。<BR>数据保证不会出现有空背包人的出现。 

 
 # 输出格式 
一个整数，整个团队背包价值的最大值。 

 
 # 提示 
【数据范围】<BR>30%的数据&nbsp;1&lt;=M,N&lt;=15。<BR>60%的数据&nbsp;1&lt;=M&lt;=200，1&lt;=N&lt;=100。<BR>100%的数据&nbsp;1&lt;=M&lt;=1,000,000，1&lt;=N&lt;=500，0&lt;wi&lt;=50。<BR>输出请注意使用64&nbsp;位整数（Pascal&nbsp;中的Int64，C++中的long&nbsp;long）。<BR>【样例解释】<BR>19=(2+7+1)+(2+7)<BR>58=(1+2+3+4)+(2+3+4)+(1+3+4)+(1+2+4)+(3+4)+(1+2+3)+(2+4)+(2+3) 
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
<tr><td>Sample Input 1:
2 3
2 7 1

Sample Input 2:
8 4
1 2 3 4
</td><td>Sample Output 1:
19

Sample Output 2:
58
</td></tr></table>
