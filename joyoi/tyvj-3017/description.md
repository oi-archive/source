# 

 
 # 题目描述 
<p>N头牛要去参加一场在编号为x(1&lt;=x&lt;=n)的牛的农场举行的派对（1&lt;=N&lt;=1000）,有M(1&lt;=m&lt;=100000)条有向道路，每条路长ti(1&lt;=ti&lt;=100);每头牛都必须参加完派对后回到家，每头牛都会选择最短路径，求这n个牛的最短路径（一个来回）中最长的一条的长度。<br />
特别提醒：可能有权值不同的重边。</p> 

 
 # 输入格式 
<p>第1行：&nbsp;N,M,X；</p>

<p><span style="line-height: 1.6em;">第2~m+1行:&nbsp;Ai,Bi,Ti,表示有一条从Ai到Bi的路，长度为Ti.</span></p> 

 
 # 输出格式 
<p>最长最短路的长度。</p> 

 
 # 提示 
<p>&nbsp;</p>

<center><img src="/source/joyoi/tyvj-3017/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzAxNy9wcm9ibGVtc19pbWFnZXMvMzYzMC8xLnBuZw==.png" /></center>

<p>&nbsp;</p> 
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
<tr><td>party.in
4 8 2
1 2 4
1 3 2
1 4 7
2 1 1
2 3 5
3 1 2
3 4 4
4 2 3</td><td>party.out
10</td></tr></table>
