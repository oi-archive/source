# 

 
 # 题目描述 
一类书的序言是以罗马数字标页码的。传统罗马数字用单个字母表示特定的数值，以下是标准数字表:&nbsp;<BR><BR>I&nbsp;1&nbsp;&nbsp;L&nbsp;50&nbsp;&nbsp;M&nbsp;1000<BR>V&nbsp;5&nbsp;&nbsp;C&nbsp;100<BR>X&nbsp;10&nbsp;D&nbsp;500<BR>最多3个同样的可以表示为10n的数字(I,X,C,M)可以连续放在一起，表示它们的和:&nbsp;<BR><BR>III=3<BR>CCC=300<BR>可表示为5x10n的字符(V,L,D)从不连续出现。&nbsp;<BR><BR>除了下一个规则，一般来说，字符以递减的顺序接连出现:&nbsp;<BR><BR>CCLXVIII&nbsp;=&nbsp;100+100+50+10+5+1+1+1&nbsp;=&nbsp;268<BR>有时，一个可表示为10n的数出现在一个比它大1级或2级的数前(I在V或X前面，X在L或C前面，等等)。在这种情况下，数值等于后面的那个数减去前面的那个数:&nbsp;<BR><BR>IV&nbsp;=&nbsp;4<BR>IX&nbsp;=&nbsp;9<BR>XL&nbsp;=&nbsp;40<BR>This&nbsp;compound&nbsp;mark&nbsp;forms&nbsp;a&nbsp;unit&nbsp;and&nbsp;may&nbsp;not&nbsp;be&nbsp;combined&nbsp;to&nbsp;make&nbsp;another&nbsp;compound&nbsp;mark&nbsp;(e.g.,&nbsp;IXL&nbsp;is&nbsp;wrong&nbsp;for&nbsp;39;&nbsp;XXXIX&nbsp;is&nbsp;correct).&nbsp;<BR><BR>像XD,&nbsp;IC,&nbsp;和XM这样的表达是非法的，因为前面的数比后面的数小太多。对于XD(490的错误表达)，可以写成&nbsp;CDXC;&nbsp;对于IC(99的错误表达)，可以写成XCIX;&nbsp;对于XM(990的错误表达)，可以写成CMXC。&nbsp;90&nbsp;is&nbsp;expressed&nbsp;XC&nbsp;and&nbsp;not&nbsp;LXL,&nbsp;since&nbsp;L&nbsp;followed&nbsp;by&nbsp;X&nbsp;connotes&nbsp;that&nbsp;successive&nbsp;marks&nbsp;are&nbsp;X&nbsp;or&nbsp;smaller&nbsp;(probably,&nbsp;anyway).&nbsp;<BR><BR><BR>给定N(1&nbsp;&lt;=&nbsp;N&nbsp;&lt;&nbsp;3,500)，&nbsp;序言的页码数，请统计在第1页到第N页中，有几个I出现，几个V出现，等等&nbsp;(从小到大的顺序)。不要输出并没有出现过的字符。&nbsp;<BR><BR>比如N&nbsp;=&nbsp;5,&nbsp;那么页码数为:&nbsp;I,&nbsp;II,&nbsp;III,&nbsp;IV,&nbsp;V.&nbsp;总共有7个I出现，2个V出现。&nbsp;<BR><BR> 

 
 # 输入格式 
一个整数N。&nbsp; 

 
 # 输出格式 
每行一个字符和一个数字k，表示这个字符出现了k次。字符必须按数字表中的递增顺序输出。&nbsp;<BR><BR> 

 
 # 提示 
USACO&nbsp;2.2.1 
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
<tr><td>5
</td><td>I 7
V 2
</td></tr></table>
