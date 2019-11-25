# 

 
 # 题目背景 
广州市2011年市选第一试 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;最近通货膨胀很厉害，CPI跑得比银行利息要快，要抗通胀，又要避风险，其中一种很好的方式，就是购买银行发行的理财产品。虽然理财产品的利息比银行定期要高，而且没有风险，但是，购买理财产品需要一定的资金门槛，而且还要保证吧钱存入一定时间不能取出来，因此也是有一定的限制的。<BR>&nbsp;&nbsp;&nbsp;&nbsp;小郭很喜欢研究银行的理财产品，她计划在2011年拿10万元进行理财产品的投资，为了简单方便，她在2011年每次投资理财产品时，都是把这笔资金和之前购买理财产品产生的所有利息投入进去，希望在年底获取最高的利润。<BR><BR>【理财产品】<BR>&nbsp;&nbsp;&nbsp;&nbsp;一个理财产品有如下要素：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;资金门槛：至少要投入多少资金；<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;发行时间：该理财产品的购买时间；<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;投资天数：资金存放的天数，<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;年利息：该理财产品如果存放一年365天能获取的利息。<BR>&nbsp;&nbsp;&nbsp;&nbsp;由于郭小姐选择的所有理财产品的门槛都是10万以内，因此理财产品就剩下的3个要素。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;例如，A1理财产品，发行时间是3月1日，投资天数为30天，年利息为&nbsp;3.5%，那么，如果10万元购买该产品，那么在30天后，也就是3月30日收市后，她可以获得的资金为：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;100000*(1+0.035*30/365)=100287.67元&nbsp;（四舍五入，保留2位小数）<BR>&nbsp;&nbsp;&nbsp;&nbsp;然后，她就可以吧100287.67元这笔资金，购买3月31日或之后发行的任何理财产品。<BR>&nbsp;&nbsp;&nbsp;&nbsp;郭小姐在这一年内不断把本金和利息一起全额地购买理财产品，希望在2012年到来之前获得最高的收益。如果购买的两个理财产品之间有时间间隔，那么这笔钱就不能产生利润（银行活期利息太低，利润可以忽略）。请问她这年内，能通过购买理财产品，最多获取多少钱呢？<BR><BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行是整数N(1&lt;=N&lt;=15)，代表理财产品的数目<BR>&nbsp;&nbsp;&nbsp;&nbsp;下面N行为3个由空格隔开的字符串&nbsp;A&nbsp;B&nbsp;C<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A代表发行时间，格式为MMDD（两位月两位日），例如4月1日则为0401，10月2日则为1002<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B&nbsp;(整数)，代表投资天数，范围是[10,300]<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;C&nbsp;(最多2位的小数)，代表百分之几的年利息，范围是[3,30]<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;输入数据保证&nbsp;发行时间+投资天数不会超过2012年。<BR>&nbsp;&nbsp;&nbsp;&nbsp;<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出只有一行，为年底最多可获得的连本带利的资金数目，保留2位小数<BR> 

 
 # 提示 
<BR>【例子分析】<BR>例子中的3个理财产品，只能购买1号产品，或者连续购买2号、3号理财产品。<BR>购买1号理财产品的收益为&nbsp;100000*(1+0.045*100/365)=101232.88<BR>购买2/3号理财产品的收益为：<BR>&nbsp;&nbsp;购买2号产品后总资金：&nbsp;100000*(1+0.05*30/365)=100410.96<BR>&nbsp;&nbsp;再购买3号产品后总资金：&nbsp;100410.96*(1+0.078*50/365)=101483.84&nbsp;&nbsp;&nbsp;&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;因此最高收益为&nbsp;101483.84<BR><BR> 
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
<tr><td>3
0101 100 4.5 
0201 30 5
0402 50 7.8
</td><td>101483.84
</td></tr></table>
