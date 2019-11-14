# 

 
 # 题目描述 
【问题描述】：	最近lxhgww又迷上了投资股票，通过一段时间的观察和学习，他总结出了股票行情的一些规律。<BR>	通过一段时间的观察，lxhgww预测到了未来T天内某只股票的走势，第i天的股票买入价为每股APi，第i天的股票卖出价为每股BPi（数据保证对于每个i，都有APi&gt;=BPi），但是每天不能无限制地交易，于是股票交易所规定第i天的一次买入至多只能购买ASi股，一次卖出至多只能卖出BSi股。<BR>	另外，股票交易所还制定了两个规定。为了避免大家疯狂交易，股票交易所规定在两次交易（某一天的买入或者卖出均算是一次交易）之间，至少要间隔W天，也就是说如果在第i天发生了交易，那么从第i+1天到第i+W天，均不能发生交易。同时，为了避免垄断，股票交易所还规定在任何时间，一个人的手里的股票数不能超过MaxP。<BR>在第1天之前，lxhgww手里有一大笔钱（可以认为钱的数目无限），但是没有任何股票，当然，T天以后，lxhgww想要赚到最多的钱，聪明的程序员们，你们能帮助他吗？ 

 
 # 输入格式 
【输入格式】<BR>&nbsp;&nbsp;&nbsp;	输入数据第一行包括3个整数，分别是T，MaxP，W。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来T行，第i行代表第i-1天的股票走势，每行4个整数，分别表示APi，BPi，ASi，BSi。<BR><BR><BR> 

 
 # 输出格式 
【输出格式】<BR>&nbsp;	输出数据为一行，包括1个数字，表示lxhgww能赚到的最多的钱数。<BR> 

 
 # 提示 
【数据范围】<BR>&nbsp;&nbsp;&nbsp;对于30%的数据，0&lt;=W&lt;T&lt;=50,1&lt;=MaxP&lt;=50<BR>&nbsp;&nbsp;&nbsp;对于50%的数据，0&lt;=W&lt;T&lt;=2000,1&lt;=MaxP&lt;=50<BR>&nbsp;&nbsp;&nbsp;对于100%的数据，0&lt;=W&lt;T&lt;=2000,1&lt;=MaxP&lt;=2000<BR>&nbsp;&nbsp;&nbsp;对于所有的数据，1&lt;=BPi&lt;=APi&lt;=1000,1&lt;=ASi,BSi&lt;=MaxP 
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
<tr><td>【样例输入】
	5 2 0
	2 1 1 1
	2 1 1 1
	3 2 1 1
	4 3 1 1
	5 4 1 1</td><td>【样例输出】
    3</td></tr></table>
