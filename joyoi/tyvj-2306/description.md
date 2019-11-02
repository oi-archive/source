# 

 
 # 题目描述 
<p>
现在商品社会发展得真快，连一向不懂经济的Dragon博士最近也决定下海了。他决定去做现下最流行的金融生意，于是他开了一家投资公司。但Dragon博士毕竟不懂经济呀，最近他已经连亏损了3个月了。但是正所谓吃一堑长一智，Dragon博士发现：市场上美元和人民币之间的汇率总是上下波动，就是说：第i天时，一人民币可以兑换c[i]美元，而一美元可以兑换d[i]元人民币，但是美国人怕中国人的外汇储备太多，因此每次把美元兑换成人民币都要收取额外的Cost元人民币作为费用，当然把人民币兑换成美元是没人反对的，也就是说不须附加费用。于是Dragon博士就想呀，是否可以从中捞点油水呢？Dragon的客户每天会向他提供w[i]元人民币运转资金。每天剩余的资金（包括美元和人民币）都可以保存到第二天而无须附加费用。<br><br></p> 

 
 # 输入格式 
<p>
第一行是两个整数n，cost，分别指天数和额外费用。<br>然后是n+1行，第i+1行是三个用空格格开的数：w[i]，c[i]，d[i]。<br><br></p> 

 
 # 输出格式 
<p>
只有一行：第n天结束可以获得的人民币最大值（保留4位小数）。<br><br>数据范围：<br>对于50%的数据，n:integer; 对于100%的数据n<=10e5;<br>0<=cost<=maxlongint;(int)<br>0<=w[i]<=30;<br>0<c[i],d[i]<=10e5;(real)<br>0<c[i]*d[i]<0.95<br>所有输出均控制在Extended和int64之内。<br></p> 
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
<tr><td>3 1
10 0.1 9
10 0.01 20
10 0.1 9

</td><td>39.0000</td></tr></table>
