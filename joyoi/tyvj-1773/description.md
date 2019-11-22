# 

 
 # 题目描述 
windy学会了一种游戏。<BR>对于1到N这N个数字，都有唯一且不同的1到N的数字与之对应。<BR>最开始windy把数字按顺序1，2，3，……，N写一排在纸上。<BR>然后再在这一排下面写上它们对应的数字。<BR>然后又在新的一排下面写上它们对应的数字。<BR>如此反复，直到序列再次变为1，2，3，……，N。<BR><BR>如：<BR>1&nbsp;2&nbsp;3&nbsp;4&nbsp;5&nbsp;6<BR>对应的关系为<BR>1-&gt;2&nbsp;&nbsp;2-&gt;3&nbsp;&nbsp;3-&gt;1&nbsp;&nbsp;4-&gt;5&nbsp;&nbsp;5-&gt;4&nbsp;&nbsp;6-&gt;6<BR>windy的操作如下<BR><BR>1&nbsp;2&nbsp;3&nbsp;4&nbsp;5&nbsp;6<BR>2&nbsp;3&nbsp;1&nbsp;5&nbsp;4&nbsp;6<BR>3&nbsp;1&nbsp;2&nbsp;4&nbsp;5&nbsp;6<BR>1&nbsp;2&nbsp;3&nbsp;5&nbsp;4&nbsp;6<BR>2&nbsp;3&nbsp;1&nbsp;4&nbsp;5&nbsp;6<BR>3&nbsp;1&nbsp;2&nbsp;5&nbsp;4&nbsp;6<BR>1&nbsp;2&nbsp;3&nbsp;4&nbsp;5&nbsp;6<BR><BR>这时，我们就有若干排1到N的排列，上例中有7排。<BR>现在windy想知道，对于所有可能的对应关系，有多少种可能的排数。<BR> 

 
 # 输入格式 
一个整数，N。<BR> 

 
 # 输出格式 
一个整数，可能的排数。<BR> 

 
 # 提示 
30%的数据，满足&nbsp;1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;10&nbsp;。<BR>100%的数据，满足&nbsp;1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;1000&nbsp;。四川SCOI2009一试&nbsp;Day1&nbsp;第三题 
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
<tr><td>3</td><td>3</td></tr><tr><td>10</td><td>16</td></tr></table>
