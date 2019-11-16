# 

 
 # 题目背景 
话说小小鱼看了P1171（自然数拆分）之后感觉异常不爽，于是异常邪恶地将题目加强。 

 
 # 题目描述 
输入自然数n，然后将其拆分成由若干数相加的形式，参与加法运算的数可以重复。 

 
 # 输入格式 
输入只有一个整数n，表示待拆分的自然数n。&nbsp;0&lt;n&lt;=4000<BR>PS:0也算自然数，所以这里应该写正整数比较好<BR>但是为了尊重原作者的版权（这有版权吗-&nbsp;-），没有改掉。<BR>本来n是要到5000的，但是开到5000的话我的程序就Memory&nbsp;Limit&nbsp;Exceeded了。。 

 
 # 输出格式 
输出一个数，即所有方案数<BR>因为这个数可能非常大，所以你只要输出这个数&nbsp;mod&nbsp;2147483648&nbsp;的余数即可。 

 
 # 提示 
解释：<BR>输入7，则7拆分的结果是<BR>7=1+6<BR>7=1+1+5<BR>7=1+1+1+4<BR>7=1+1+1+1+3<BR>7=1+1+1+1+1+2<BR>7=1+1+1+1+1+1+1<BR>7=1+1+1+2+2<BR>7=1+1+2+3<BR>7=1+2+4<BR>7=1+2+2+2<BR>7=1+3+3<BR>7=2+5<BR>7=2+2+3<BR>7=3+4<BR><BR><BR>一共有14种情况，所以输出14&nbsp;mod&nbsp;2147483648，即14小小鱼加强Admin的P1171<BR>PS:虽说加强了，但是好像还是很简单。。。 
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
<tr><td>7
</td><td>14
</td></tr></table>
