# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;由于地震使得连接汶川县城的电话线全部损坏，加入你是负责讲电话先接到震中汶川县城的负责人，汶川县城周围分布N（1&lt;=n&lt;=1000）根按1…n电话线杆间可以拉电话线，其余的由于地震使得无法被连接。<br>&nbsp;&nbsp;&nbsp;&nbsp;第i对电话线杆的两个端点分别为Ai，Ri，它们间的距离为Li（1&lt;=li&lt;=1000000）。数据中保证每对最多只出现一次。编号为1的电话线杆已经接入了全国的电话网络，整个县城的电话线全部连到了编号为N的电话线杆上。也就是说，你的任务仅仅是找一条将1号和N号电话线杆连起来的路径，其余的电话线杆并不一定要连入电话网络。<br>&nbsp;&nbsp;&nbsp;&nbsp;电信公司决定支援灾区免费为汶川县城连接K（0&lt;=k&lt;n）对有你指定的电话线杆。对于此外的那些电话线，需要为它们付费，总费用等于其中最长的电话线长度（每根电话线仅连接一对电话线杆）。如果需要连接的电话线杆不超过K对，那么总支出为0.<br>&nbsp;&nbsp;&nbsp;&nbsp;请你计算一下，将电话线引到震中汶川县城最少需要在电话线上花多少钱？<br> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入文件的第一行包含三个用空格隔开的整数：N&nbsp;P和K。<br>&nbsp;&nbsp;&nbsp;&nbsp;第二行到第P+1行：每行分别都为三个用空格隔开的整数：Ai&nbsp;Bi和Li。<br> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出文件仅包含一个整数，表示在这项工程上的最小支出。如果任务不可能完成，则输出-1.<br><br> 
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
<tr><td>5 7 1
1 2 5
3 1 4
2 4 8
3 2 3
5 2 9
3 4 7
4 5 6

</td><td>4
</td></tr></table>
