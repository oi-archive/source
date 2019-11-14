# 

 
 # 题目描述 
给出一个整数&nbsp;n（n&lt;10^30)&nbsp;和&nbsp;k&nbsp;个变换规则（k&lt;=15）。<BR>　　规则：<BR>　　一位数可变换成另一个一位数：<BR>　　规则的右部不能为零。<BR>　　例如：n=234。有规则（k＝2）：<BR>　　2－&gt;&nbsp;5<BR>　　3－&gt;&nbsp;6<BR>　　上面的整数&nbsp;234&nbsp;经过变换后可能产生出的整数为（包括原数）:<BR>　　234<BR>　　534<BR>　　264<BR>　　564<BR>　　共&nbsp;4&nbsp;种不同的产生数<BR>问题：<BR>　　给出一个整数&nbsp;n&nbsp;和&nbsp;k&nbsp;个规则。<BR>求出：<BR>　　经过任意次的变换（0次或多次），能产生出多少个不同整数。<BR>　　仅要求输出个数。&nbsp; 

 
 # 输入格式 
第一行n和k。<BR>下面K行每行两个整数，表示转换规则 

 
 # 输出格式 
一个整数（满足条件的个数） 

 
 # 提示 
Noip2002普及组第3题 
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
<tr><td>234 2
2 5
3 6
</td><td>4</td></tr></table>
