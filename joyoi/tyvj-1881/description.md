# 

 
 # 题目描述 
每样商品的价格越低，其销量就会相应增大。现已知某种商品的成本及其在若干价位上的销量（产品不会低于成本销售），并假设相邻价位间销量的变化是线性的且在价格高于给定的最高价位后，销量以某固定数值递减。（我们假设价格及销售量都是整数）<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;对于某些特殊商品，不可能完全由市场去调节其价格。这时候就需要政府以税收或补贴的方式来控制。（所谓税收或补贴就是对于每个产品收取或给予生产厂家固定金额的货币）<BR><BR>&nbsp;&nbsp;&nbsp;问题求解&nbsp;&nbsp;&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;你是某家咨询公司的项目经理，现在你已经知道政府对某种商品的预期价格，以及在各种价位上的销售情况。要求你确定政府对此商品是应收税还是补贴的最少金额（也为整数），才能使商家在这样一种政府预期的价格上，获取相对其他价位上的最大总利润。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;总利润&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;=&nbsp;单位商品利润&nbsp;*&nbsp;销量&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;单位商品利润&nbsp;=&nbsp;单位商品价格&nbsp;–&nbsp;单位商品成本&nbsp;（–&nbsp;税金&nbsp;&nbsp;or&nbsp;&nbsp;+&nbsp;补贴） 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;输&nbsp;&nbsp;&nbsp;入&nbsp;&nbsp;&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;输入的第一行为政府对某种商品的预期价，第二行有两个整数，第一个整数为商品成本，第二个整数为以成本价销售时的销量售，以下若干行每行都有两个整数，第一个为某价位时的单价，第二个为此时的销量，以一行-1，-1表示所有已知价位及对应的销量输入完毕，输入的最后一行为一个单独的整数表示在已知的最高单价外每升高一块钱将减少的销量。<BR> 

 
 # 输出格式 
输&nbsp;&nbsp;&nbsp;出&nbsp;&nbsp;&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;输出有两种情况：若在政府预期价上能得到最大总利润，则输出一个单独的整数，数的正负表示是补贴还是收税，数的大小表示补贴或收税的金额最小值。若有多解，取绝对值最小的输出。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;如在政府预期价上不能得到最大总利润，则输出“NO&nbsp;SOLUTION”.<BR> 

 
 # 提示 
价格和数量&lt;=10000<BR>单位补贴（收税）&lt;=100 
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
<tr><td>31
28 130
30 120
31 110
-1 –1
15</td><td>4
</td></tr></table>
