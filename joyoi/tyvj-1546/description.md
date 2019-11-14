# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;对于一个集合S={1,2,3,……,n}，他有2^n个子集。对于每个子集T，我们给定他的得分为F(T)。现让你寻找一个S的子集T，使得T的所有子集的得分和尽可能大。 

 
 # 输入格式 
输入数据第一行有一个正整数n。<BR>随后的2^n行，按“二进制序”从小到大给出每个子集的得分。<BR>例如n=3时，就是按照{}、{1}、{2}、{1,2}、{3}、{1,3}、{2,3}、{1,2,3}的顺序给出的。<BR> 

 
 # 输出格式 
仅一个整数，表示最大的得分和。 

 
 # 提示 
对于10%的数据，n&lt;=10。<BR>对于40%的数据，n&lt;=15。<BR>对于100%的数据，n&lt;=20。<BR>F(T)的绝对值不超过1000。<BR> 
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
-1
100
-2
-3
</td><td>99
</td></tr></table>
