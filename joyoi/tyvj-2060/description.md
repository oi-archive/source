# 

 
 # 题目背景 
NOIP2012提高组模拟赛day1 

 
 # 题目描述 
期中考试和NOIP复赛都快到了，某人还没有复习英语，他背单词有一个特点，就是背单词的时间恰好等于背这个单词的字母的时间之和，可是他不知道复习完英语单词之后能不能再复习NOIP，所以他找到了你。他想让你来帮他规划一下：如果他成功复习完英语单词，还能剩下多少时间复习NOIP，如果时间不够复习所有的单词，请问他最多能背多少单词。 

 
 # 输入格式 
第一行为两个正整数T，N，表示剩余的时间是T，共有N个单词。<br>第二行为26个整数ti（空格隔开），表示背26个小写字母分别所需的时间，对应的大写字母时间一样。<br>第三行到第&nbsp;N+2&nbsp;行，每行一个单词。 

 
 # 输出格式 
第一行，输出"Yes"或"No"，表示能否复习NOIP。<br>第二行，输出剩余能够复习NOIP的时间或者最多可以背的单词个数。 

 
 # 提示 
样例解释：<br>NOIP这个单词花费的总时间是0，所以我们还剩下100个时间去复习NOIP<br><br>对于50%&nbsp;的数据，1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;1000&nbsp;，1&nbsp;&lt;=&nbsp;T&nbsp;&lt;=&nbsp;10^7&nbsp;&nbsp;，单词全部为大写<br>对于100%的数据，1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;10000，1&nbsp;&lt;=&nbsp;T&nbsp;&lt;=&nbsp;2^63-1，单词可能有小写<br>对于100%的数据，0&nbsp;&lt;=&nbsp;ti&nbsp;&lt;=1000&nbsp;，单词长度不大于50tjz 
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
<tr><td>1000 1
1 1 1 1 1 1 1 1 0 1 1 1 1 0 0 0 1 1 1 1 1 1 1 1 1 1
NOIP
</td><td>Yes
1000</td></tr></table>
