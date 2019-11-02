# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;随着tyvj发展越来越大，管理员的任务越来越重，如何合理的分配任务，成为了一个可研究的命题。Tyvj当前一共有M个需要做的任务，和N位管理员。每一个管理员的上线时间并不是固定的，每一个人有d[i]单位的上线时间，每一位管理员一个单位的时间可以完成一个任务，且一个任务只能由一个管理员来完成（如果更多的管理员参与进来，可能会造成混乱）。每一位管理员的能力有所不同，所以能完成的任务集合可能不相同。最终让所有未完成的任务数量最少。 

 
 # 输入格式 
输入文件第一有两个正整数，分别是N和M<BR>&nbsp;&nbsp;&nbsp;下面面N行，每一行表示一位管理员的信息，第一个正整数为d[i]，第二个正整数为tot，后面有tot个数，表示第i位管理员可以完成的任务集合。<BR> 

 
 # 输出格式 
输出文件仅有一个数，所有未完成任务的最少值。 

 
 # 提示 
数据范围约定：<BR>20%的数据&nbsp;n&lt;=10&nbsp;M&lt;=10&nbsp;且D[i]=1<BR>60%的数据&nbsp;n&lt;=50&nbsp;M&lt;=300&nbsp;且D[i]&lt;=30<BR>100%的数据&nbsp;n&lt;=3000&nbsp;M&lt;=10000&nbsp;且d[i]&lt;=100<BR>admin&nbsp;TYVJ首届月赛第三道 
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
<tr><td>3 3
2 2 1 2
0 3 1 2 3
1 1 2
</td><td>1
</td></tr></table>
