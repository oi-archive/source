# 

 
 # 题目描述 
姚先生经营一家商店，在他的精心经营下，商店办的越来越红火。有一天，一位神秘的客户找到了姚先生，给了姚先生N份订单。当姚先生读这N份神秘订单时，他意识到他缺少M台机器去完成这些订单。不是所有的订单都需要所有的机器，但是每一份订单都至少需要M台机器中的一台。<BR>	为了完成一份订单，姚先生需要买下或者租下这个订单要求的每一台机器。由于不同的订单在每台机器上的工作时间不同，所以机器的租金依赖于订单。当然购买一台机器所需要的金钱数是恒定的。一旦买下一台机器，姚先生可以任意的使用它，不用考虑时间上限。<BR>	如果完成某个订单的花费太高，姚先生可以拒绝这份订单，这不会给他带来任何花费。<BR>	聪明的程序员，请你帮助姚先生决定是否决定接受订单的策略以及购买（或租赁）机器的策略，从而最大化他的利益。<BR><BR>例子<BR>	<BR>N=2,M=3<BR>┌───┬────────────┐	<BR>│订单│如果完成的收益│<BR>├───┼────────────┤<BR>│1号│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;100&nbsp;&nbsp;&nbsp;&nbsp;│<BR>├───┼────────────┤<BR>│2号│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;100&nbsp;&nbsp;&nbsp;&nbsp;│<BR>└───┴────────────┘<BR><BR>┌───┬─────────┐	<BR>│机器│完成的收益│<BR>├───┼─────────┤<BR>│M1&nbsp;│&nbsp;50&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<BR>├───┼─────────┤<BR>│M2&nbsp;│&nbsp;&nbsp;80&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<BR>├───┼─────────┤<BR>│M3&nbsp;│&nbsp;&nbsp;110&nbsp;&nbsp;&nbsp;&nbsp;│<BR>└───┴─────────┘<BR><BR>┌────┬────────┬───────┐<BR>│订单│需要的机器│租赁价格│<BR>├────┼────────┼───────┤<BR>│&nbsp;&nbsp;&nbsp;&nbsp;│M1	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│30&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<BR>│1&nbsp;&nbsp;&nbsp;│M2	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│20&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<BR>├────┼────────┼───────┤<BR>│2&nbsp;&nbsp;&nbsp;│M3	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│80&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<BR>│&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;M1	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│40&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<BR>└────┴────────┴───────┘<BR>最大收益为50，有两种方法实现。<BR><BR>1、拒绝2，完成1，租用M1和M2<BR>2、完成1和2，购买M1,租用M2和M3<BR><BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入数据第一行有两个整数，&nbsp;N(1≤N≤1200)，M(1≤M≤1200)&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来有N个模块，每一个模块描述一个订单：第i个模块的第一行包含两个整数，&nbsp;Oi的收入金额Vi和它需要用到的机器数量mi(1≤mi≤M)。接下来的mi行每行有两个数字：这个订单用到的机器j和租用它完成这个订单的租用费rij(1≤rij≤20000)。<BR>接下来的M行每行包含一个正整数：购买每个机器需要的金钱si(1≤si≤20000)<BR> 

 
 # 输出格式 
输出包含一个数：姚先生的最大收益。 
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
<tr><td>2 3
100 2
1 30
2 20
100 2
1 40
3 80
50
80
110
</td><td>50
</td></tr></table>
