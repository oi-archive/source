# 

 
 # 题目描述 
很久以前，在一个遥远的银河系……对反抗军来说，这是一个黑暗的时刻。虽然帝国军的终极武器“死亡星球”已经被摧毁，帝国的军队仍然把反抗军从隐藏的军事基地中赶出，并在整个银河系展开追逐。&nbsp;<BR><BR>考虑到邪恶的帝国完全有能力在短时间内制造出“死亡星球”的替代品，为了避免被一次全部歼灭，反抗军的指挥官决定把部队分散在很多星球上。可是，这样会带来通讯上的问题。某些星球之间可以通过“以太”隧道直接通讯，而没有隧道相连的星球之间的通讯就需要其他星球帮忙转发。因此，只有两个星球之间存在一条由“以太”隧道拼接成的路径，它们才可以正常通讯。<BR><BR>银河历2008年4月1日凌晨，反抗军最担心的事情还是发生了。反抗军司令部收到间谍的秘密通知：帝国军成功制造出第二代“死亡星球”，并将依次摧毁如下星球（星球列表略）。指挥官希望迅速计算出每次攻击之后通讯网络的连通情况，即反叛军所占据的星球被分成了多少个连通支，从而帮助决定在何时发动反击。<BR><BR> 

 
 # 输入格式 
输入文件的第一行包含两个整数N&nbsp;(2&nbsp;≤&nbsp;N&nbsp;≤&nbsp;2M)和M&nbsp;(1&nbsp;≤&nbsp;M&nbsp;≤&nbsp;200,000)，分别表示星球的数目和“以太”隧道的数目。星球用0到N&nbsp;–&nbsp;1的整数编号。<BR>接下来的M行，每行包含两个整数X和Y&nbsp;(0&nbsp;≤&nbsp;X&nbsp;≠&nbsp;Y&nbsp;&lt;&nbsp;N)，表示星球X和星球Y之间有“以太”隧道，可以直接通讯。<BR>接下来的一行包含一个整数K，表示将遭受攻击的星球的数目。<BR>接下来的K行，每行一个整数，按照顺序列出了帝国军的攻击目标。这K个数互不相同，且都在0到N&nbsp;–&nbsp;1的范围内。<BR><BR> 

 
 # 输出格式 
输出文件应该包含K&nbsp;+&nbsp;1行，每行一个整数。<BR>第一个整数表示开始时通讯网络的连通支个数。<BR>接下来的第I&nbsp;(1&nbsp;≤&nbsp;I&nbsp;≤&nbsp;K)个整数，表示在攻击列表上的第I个星球被摧毁后，通讯网络的连通支个数。<BR><BR> 

 
 # 提示 
<img src="/source/joyoi/tyvj-1824/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTgyNC9Qcm9ibGVtSW1nLzE4MjQuanBn.jpg" border=0 align=middle><BR>JSOI2008江苏省代表队组队第三轮选拔赛&nbsp;本次竞赛共分两试，本试卷为第二试。 
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
<tr><td>8 13
0 1
1 6
6 5
5 0
0 6
1 2
2 3
3 4
4 5
7 1
7 2
7 6
3 6
5
1
6
3
5
7

</td><td>1
1
1
2
3
3
</td></tr></table>
