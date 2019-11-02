# 

 
 # 题目背景 
zst神犇翻开奥数，发现一道博弈论，于是他让蒟蒻lzf把它做成一道OI题......<br> 

 
 # 题目描述 
甲乙两人玩一个游戏:一张卡片上有个数字,甲乙两人轮流操作,若当前卡片上的数字为x,每次操作可以把它变为x+1或2x,且不能超过n(例如n=8,x=6,只能变为7而不能变为12),每次甲首先在卡片上写1,规定写n的人获胜。给定n,问甲是否有必胜策略?<br> 

 
 # 输入格式 
共t+1行,第一行是一个正整数t，表示数据组数,下面t行,每行一个正整数n,含义如题所述<br> 

 
 # 输出格式 
共t行,每行为'YES'或'NO',若甲有必胜策略则输出'YES',否则输出'NO'<br> 

 
 # 提示 
数据范围<br>t&lt;=10000<br>n&lt;2^63<br>奥数<br> 
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
<tr><td>2
7
8
</td><td>YES
NO
</td></tr></table>
