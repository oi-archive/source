# 题目描述


<div>
	【问题描述】
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	最近通货膨胀很厉害，CPI跑得比银行利息要快，要抗通胀，又要避风险，其中一种很好的方式，就是购买银行发行的理财产品。虽然理财产品的利息比银行定期要高，而且没有风险，但是，购买理财产品需要一定的资金门槛，而且还要保证吧钱存入一定时间不能取出来，因此也是有一定的限制的。
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	小郭很喜欢研究银行的理财产品，她计划在2011年拿10万元进行理财产品的投资，为了简单方便，她在2011年每次投资理财产品时，都是把这笔资金和之前购买理财产品产生的所有利息投入进去，希望在年底获取最高的利润。
</div>
<div>
	 
</div>
<div>
	【理财产品】
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	<span>       </span>一个理财产品有如下要素：
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	资金门槛：至少要投入多少资金；
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	发行时间：该理财产品的购买时间；
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	投资天数：资金存放的天数，
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	年利息：该理财产品如果存放一年365天能获取的利息。
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	由于郭小姐选择的所有理财产品的门槛都是10万以内，因此理财产品就剩下的3个要素。
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	 
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	例如，A1理财产品，发行时间是3月1日，投资天数为30天，年利息为 3.5%，那么，如果10万元购买该产品，那么在30天后，也就是3月30日收市后，她可以获得的资金为：
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	`100000*(1+0.035*30/365)=100287.67元 （四舍五入，保留2位小数）
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	然后，她就可以吧100287.67元这笔资金，购买3月31日或之后发行的任何理财产品。
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	郭小姐在这一年内不断把本金和利息一起全额地购买理财产品，希望在2012年到来之前获得最高的收益。如果购买的两个理财产品之间有时间间隔，那么这笔钱就不能产生利润（银行活期利息太低，利润可以忽略）。请问她这年内，能通过购买理财产品，最多获取多少钱呢？
</div>
<div>
	 
</div>
<div>
	【输入格式】
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	第一行是整数N(1&lt;=N&lt;=15)，代表理财产品的数目
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	下面N行为3个由空格隔开的字符串 A B C
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	A代表发行时间，格式为MMDD（两位月两位日），例如4月1日则为0401，10月2日则为1002
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	B (整数)，代表投资天数，范围是[10,300]
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	C (最多2位的小数)，代表百分之几的年利息，范围是[3,30]
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	 
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	输入数据保证 发行时间+投资天数不会超过2012年。
</div>
<div>
	<span>    </span>
</div>
<div>
	【输出格式】
</div>
<div>
	<span>       </span>输出只有一行，为年底最多可获得的连本带利的资金数目，保留2位小数
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	<span>       </span>
</div>
<div>
	【输入样例】
</div>
<div>
	 3
</div>
<div>
	 0101 100 4.5
</div>
<div>
	 0201 30 5
</div>
<div>
	 0402 50 7.8
</div>
<div>
	 
</div>
<div>
	【例子分析】
</div>
<div style="margin:0cm 0cm 0pt 42pt;">
	例子中的3个理财产品，只能购买1号产品，或者连续购买2号、3号理财产品。
</div>
<div style="margin:0cm 0cm 0pt 42pt;">
	购买1号理财产品的收益为 100000*(1+0.045*100/365)=101232.88
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	购买2/3号理财产品的收益为：
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	 购买2号产品后总资金： 100000*(1+0.05*30/365)=100410.96
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	 再购买3号产品后总资金： 100410.96*(1+0.078*50/365)=101483.84<span>    </span>
</div>
<div>
	<span>    </span>因此最高收益为 101483.84
</div>
<div>
	 
</div>
<div>
	【输出样例】
</div>
<div>
	<span>     101483.84</span>
</div>
