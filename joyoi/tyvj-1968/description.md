# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;Adam和Eve玩一个游戏，他们先从1900.1.1到2001.11.4这个日期之间随意抽取一个日期出来。然后他们轮流对这个日期进行操作：<BR><BR>&nbsp;&nbsp;&nbsp;1&nbsp;：&nbsp;把日期的天数加1，例如1900.1.1变到1900.1.2<BR><BR>&nbsp;&nbsp;&nbsp;2&nbsp;：&nbsp;把月份加1，例如：1900.1.1变到1900.2.1<BR><BR>&nbsp;&nbsp;&nbsp;其中如果天数超过应有天数则日期变更到下个月的第1天。月份超过12则变到下一年的1月。而且进行操作二的时候，如果有这样的日期：1900.1.31，则变成了1900.2.31，这样的操作是非法的，我们不允许这样做。而且所有的操作均要考虑历法和闰年的规定。<BR><BR>&nbsp;&nbsp;&nbsp;谁先将日期变到2001.11.4谁就赢了。<BR><BR>&nbsp;&nbsp;&nbsp;每次游戏都是Adam先操作，问他有没有必胜策略？<BR> 

 
 # 输入格式 
&nbsp;&nbsp;一个测试点。多组数据。<BR>&nbsp;&nbsp;第一行为数据组数。<BR>&nbsp;&nbsp;接下来一行X&nbsp;Y&nbsp;Z表示X年Y月Z日<BR> 

 
 # 输出格式 
&nbsp;&nbsp;输出“YES”or“NO”表示亚当是否有必胜策略。&nbsp;<BR> 

 
 # 提示 
&nbsp;&nbsp;建议先把所有情况都算出来^_^<BR>From&nbsp;ZJU<BR> 
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
2001 11 3
2001 11 2
2001 10 3
</td><td>YES
NO
NO
</td></tr></table>
