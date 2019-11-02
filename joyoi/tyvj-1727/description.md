# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;如果有一个自然数a能被自然数b整除，则称a为b的倍数，b为a的约数。几个自然数公有的约数，叫做这几个自然数的公约数。公约数中最大的一个公约数，称为这几个自然数的最大公约数（Greatest&nbsp;common&nbsp;divisor，简写为gcd）。<BR>&nbsp;&nbsp;&nbsp;&nbsp;算两个数的最大公约数可以利用欧几里得算法求解。欧几里得算法又称辗转相除法，用于计算两个整数a，b的最大公约数。其计算原理依赖于下面的定理，<BR>&nbsp;&nbsp;&nbsp;&nbsp;定理：gcd(a,b)&nbsp;=&nbsp;gcd(b,a&nbsp;mod&nbsp;b)<BR>&nbsp;&nbsp;&nbsp;&nbsp;计算机程序实现：（例如pascal）<BR>&nbsp;&nbsp;&nbsp;&nbsp;function&nbsp;gcd(a,b&nbsp;:&nbsp;integer)&nbsp;:&nbsp;integer;<BR>&nbsp;&nbsp;&nbsp;&nbsp;begin<BR>	if&nbsp;(b&nbsp;=&nbsp;0)&nbsp;then&nbsp;gcd&nbsp;:=&nbsp;a<BR>	&nbsp;&nbsp;&nbsp;&nbsp;else&nbsp;gcd&nbsp;:=&nbsp;gcd(b,a&nbsp;mod&nbsp;b);<BR>&nbsp;&nbsp;&nbsp;&nbsp;end;<BR>&nbsp;&nbsp;&nbsp;&nbsp;这个时候我们引入一个概念，称为辗转次数。<BR>&nbsp;&nbsp;&nbsp;&nbsp;辗转次数是指，有两个整数a和b，令a’&nbsp;=&nbsp;b&nbsp;mod&nbsp;a,&nbsp;b’&nbsp;=&nbsp;a，每次将(a,b)变为(a’,b’)，直到最终a’=gcd(a,b)时总共进行的变换次数。<BR>&nbsp;&nbsp;&nbsp;&nbsp;例如a和b为77和121，gcd(77,121)=11.<BR>&nbsp;&nbsp;&nbsp;&nbsp;次数	a	b<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1		77	121<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2		44	77<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3		33	44<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4		11	33<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5		0	11<BR>&nbsp;&nbsp;&nbsp;&nbsp;可以发现，辗转到第4次的时候，a=gcd(a,b)=11，所以说77和121的辗转次数是4.<BR>&nbsp;&nbsp;&nbsp;&nbsp;假设有两个整数a和b，在满足a≤b≤N的所有数对(a,b)中，(a,b)辗转次数最大的一组是哪一组？<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入仅1行，包含一个整数N，含义如题所述。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出共2行，每行各1个整数，分别表示辗转次数最多的数对a和b。如果辗转次数一样，取b最小的（如果b也一样，取a最小的）。 

 
 # 提示 
【数据范围】<BR>对于20%的数据，N≤10^10<BR>对于30%的数据，N≤10^1000<BR>对于40%的数据，N≤10^3000<BR>对于75%的数据，N≤10^10000<BR>对于100%的数据，N≤10^12345<BR><BR>寒假模拟赛&nbsp;普及组&nbsp;第四题 
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
<tr><td>4
</td><td>2
3
</td></tr></table>
