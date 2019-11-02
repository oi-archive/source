# 

 
 # 题目背景 
机器人大奖赛第3道&nbsp;noip难度 

 
 # 题目描述 
金字塔中有一个房间名叫“无归之室”。房间地面完全由相同的矩形瓷砖覆盖。房间里布满无数的机关和陷阱，这正是其名字的由来。考古队花了几年时间研究对策，最后他们想出了一个方案。一台遥控的机器人将被送入房间，解除所有机关，然后返回。为了不触动机关，机器人必须走在瓷砖的中心区域上，绝对不能碰到瓷砖的边缘。如果走错一步，机器人会被落下的岩石砸成薄饼。<BR>当考古队正准备行动的时候，他们发现了一件可怕的事情：他们没有考虑到机器人携带的工具箱。由于机器人必须将工具箱放在地面上才能开始解除机关，工具箱不可碰到瓷砖的边缘。现在他们急需你编程判断工具箱可否放下。<BR> 

 
 # 输入格式 
输入文件有多组数据组成。每组数据仅含一行四个正整数A,B,X,Y。A,B为瓷砖的长和宽，X,Y为工具箱底面的长和宽（工具箱为长方体）。最后一组数据A=B=X=Y=0，标志文件结束，不需要处理。 

 
 # 输出格式 
若工具箱能以某种方式放在地上，则输出”Escape&nbsp;is&nbsp;possible.”，否则输出”Box&nbsp;cannot&nbsp;be&nbsp;dropped.”。 

 
 # 提示 
100%的数据满足1≤A,B,X,Y≤50000；<BR>注意，工具箱可以斜着放slzxmxh 
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
<tr><td>10 10 8 8
8 8 10 10
0 0 0 0
</td><td>Escape is possible.
Box cannot be dropped.
</td></tr></table>
