# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;Masha&nbsp;和&nbsp;Stas&nbsp;正在玩一个游戏。在游戏的开始，给出一个定值&nbsp;N&nbsp;，同时有两个正整数&nbsp;A&nbsp;和&nbsp;B，初始时满足&nbsp;A^B&nbsp;&lt;=&nbsp;N&nbsp;。Masha&nbsp;先手。每一回合，玩家要将&nbsp;A&nbsp;和&nbsp;B&nbsp;的其中一个数加上&nbsp;1，但不能令到&nbsp;A^B&nbsp;&gt;&nbsp;N&nbsp;，否则该玩家输。如果出现a=1等导致游戏无法结束的情况为平局。<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在，Masha&nbsp;想知道假如两人都使用最优策略，对于一个特定的&nbsp;N&nbsp;，不同的&nbsp;A、B&nbsp;的初始值谁将获胜呢？<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入第一行为一个正整数&nbsp;N&nbsp;。<BR>&nbsp;&nbsp;&nbsp;&nbsp;输入第二行为一个正整数&nbsp;T，表示测试数据个数。<BR>&nbsp;&nbsp;&nbsp;&nbsp;下面&nbsp;T&nbsp;行，每行有两个正整数&nbsp;Ai&nbsp;、&nbsp;Bi&nbsp;，描述了一组测试数据&nbsp;&lt;&nbsp;Ai&nbsp;,&nbsp;Bi&nbsp;,&nbsp;N&nbsp;&gt;，含义如题目描述。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;对每组数据输出一行。如果先手&nbsp;Masha&nbsp;获胜，输出"Masha"；如果后手&nbsp;Stas&nbsp;获胜，输出"Stas"；如果和则输出"Missing"（不用输出引号）。<BR> 

 
 # 提示 
数据限制<BR>对&nbsp;30%&nbsp;的数据有&nbsp;1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;2000；<BR>对&nbsp;100%&nbsp;的数据有：<BR>1&nbsp;&lt;=&nbsp;&nbsp;N&nbsp;&lt;=&nbsp;&nbsp;108<BR>1&nbsp;&lt;=&nbsp;&nbsp;T&nbsp;&lt;=&nbsp;100<BR>1&nbsp;&lt;=&nbsp;Ai、Bi&nbsp;&lt;=&nbsp;N<BR><BR>清北学堂模拟赛，第一场，第二题。 
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
<tr><td>9
2
2 2
1 4
</td><td>Masha
Missing

</td></tr></table>
