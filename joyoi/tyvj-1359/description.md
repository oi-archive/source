# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;高考结束后，同学们大都找到了一份临时工作，渴望挣得一些零用钱。从今天起，Matrix67将连续工作N天(1&lt;=N&lt;=100&nbsp;000)。每一天末他可以领取当天及前面若干天里没有领取的工资，但他总共只有M(1&lt;=M&lt;=N)次领取工资的机会。Matrix67已经知道了在接下来的这N天里每一天他可以赚多少钱。为了避免自己滥用零花钱，他希望知道如何安排领取工资的时间才能使得领到工资最多的那一次工资数额最小。注意Matrix67必须恰好领工资M次，且需要将所有的工资全部领走（即最后一天末需要领一次工资）。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行输入两个用空格隔开的正整数N和M<BR>&nbsp;&nbsp;&nbsp;&nbsp;以下N行每行一个不超过10000正整数，依次表示每一天的薪水。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;输出领取到的工资的最大值最小是多少。<BR> 

 
 # 提示 
【样例说明】<BR>&nbsp;&nbsp;&nbsp;&nbsp;采取下面的方案可以使每次领到的工资不会多于500。这个答案不能再少了。<BR>100&nbsp;400&nbsp;&nbsp;&nbsp;300&nbsp;100&nbsp;&nbsp;&nbsp;500&nbsp;&nbsp;&nbsp;101&nbsp;&nbsp;&nbsp;400&nbsp;&nbsp;&nbsp;每一天的薪水<BR>&lt;------1&nbsp;&lt;-------2&nbsp;&lt;---3&nbsp;&lt;---4&nbsp;&lt;---5&nbsp;&nbsp;领取工资的时间<BR>&nbsp;&nbsp;500&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;400&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;500&nbsp;&nbsp;&nbsp;101&nbsp;&nbsp;&nbsp;400&nbsp;&nbsp;&nbsp;领取到的工资<BR> 
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
<tr><td>7 5
100
400
300
100
500
101
400
</td><td>500
</td></tr></table>
