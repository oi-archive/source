# 

 
 # 题目背景 
清北学堂TYVJ9月模拟赛试题第二题 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;“抓鱼”是一款游戏，全名叫做“Ships&nbsp;catch&nbsp;fish&nbsp;on&nbsp;a&nbsp;river”。<BR>&nbsp;&nbsp;&nbsp;&nbsp;游戏中河被抽象成一个宽度为1，长度为N的矩形，从左到右每一个格子被从1~N标号。每个格子中都有一些鱼，第i格有ai条鱼。<BR>&nbsp;&nbsp;&nbsp;&nbsp;河上有M条船，每条船都有一个固定的长度Di，且船只能停在整数格上。两艘船之间不能有重叠，比如一艘船停在1到5格，还有一艘船停在5到6格，这就是非法的，因为5这格重叠了。船为了停止，需要下锚，每条船只能在Bi格上下锚，且船身必须覆盖下锚的这格。<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在我们定义，所有被船覆盖的格子处的鱼，都将被抓住。<BR>&nbsp;&nbsp;&nbsp;&nbsp;你需要编一个程序来求出，最多可以抓住多少条鱼。 

 
 # 输入格式 
第一行一个数N。<BR>第二行N个数，第i个数是ai。<BR>第三行一个数M。<BR>接下来M行，第i+3行描述Bi和Di。<BR> 

 
 # 输出格式 
输出一个数，表示最多可以抓到的鱼的数目。 

 
 # 提示 
数据规模<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于30%&nbsp;的数据&nbsp;N≤100；<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于100%&nbsp;的数据&nbsp;1≤N≤100&nbsp;000，1≤M≤N，1≤ai≤100。Bi和Di保证，总存在合法的方案，使得所有船都可以在河上，且不冲突。 
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
<tr><td>11
1 1 6 4 4 1 1 3 10 1 1
3
2 3
6 4
10 2</td><td>31</td></tr></table>
