# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;外星人逐渐逼近，为了保护地球，现在决定直接在外空进行战斗。<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在我们有N个导弹。需要在最短的时间内，用这N个导弹摧毁敌方n个目标(1个导弹只能摧毁1个目标)。N个导弹和目标的位置不一定相同，但是给每个导弹确定目标是一件很麻烦的事情。请你编程帮助给每个导弹确定目标，使每个导弹到其目标的距离之和最小。<BR> 

 
 # 输入格式 
第一行输入N(N&lt;=20)<BR>接下来N行每行包含一个坐标(x,y)，表示一个导弹，-10000&lt;x,y&lt;10000，且x,y为整数。<BR>接下来N行每行包含一个坐标(x,y)，表示一个目标，-10000&lt;x,y&lt;10000，且x,y为整数。<BR> 

 
 # 输出格式 
每个导弹到其目标距离之和的最小值。结果保留3位小数。<BR> 
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
<tr><td>1
10 1
6 -1
</td><td>4.472
</td></tr></table>
