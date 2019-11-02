# 

 
 # 题目背景 
清北学堂杯Tyvj2周年邀请赛&nbsp;第二道 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;Tyvj两周年庆典要到了，Sam想为Tyvj做一个大蛋糕。蛋糕俯视图是一个N*M的矩形，它被划分成N*M个边长为1*1的小正方形区域。（可以把蛋糕当成N行M列的矩阵）蛋糕很快做好了，但光秃秃的蛋糕…肯定不好看！所以，Sam要在蛋糕的上表面涂抹果酱。果酱有三种，分别是红果酱、绿果酱、蓝果酱，三种果酱的编号分别为1,2,3。为了保证蛋糕的视觉效果，Admin下达了死命令：相邻的区域严禁使用同种果酱。但…Sam在接到这条命令之前，已经涂好了蛋糕第K行的果酱，且无法修改。<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在，Sam想知道，能令Admin满意的涂果酱方案有多少种(mod&nbsp;10^6)。若不存在这种方案，请输出0<BR><BR> 

 
 # 输入格式 
输入共三行。<BR>第一行：N&nbsp;M<BR>第二行：K<BR>第三行：M&nbsp;个整数，表示第K&nbsp;行的方案<BR>字母的详细含义见题目描述，其他参见样例&nbsp;<BR> 

 
 # 输出格式 
共一行：可行的方案总数. 

 
 # 提示 
样例解释：<BR>第一行的<B>&nbsp;2&nbsp;3&nbsp;</B>是固定的，合理的果酱涂抹方案共3种：<BR>--方案1--<BR>2&nbsp;3<BR>1&nbsp;2<BR>--方案2--<BR>2&nbsp;3<BR>3&nbsp;1<BR>--方案3--<BR>2&nbsp;3<BR>3&nbsp;2<BR><BR><BR>数据范围：<BR>对于30%的数据，1&lt;=N*M&lt;=20<BR>对于60%的数据，1&lt;=N&lt;=1000,1&lt;=M&lt;=3<BR>对于100%的数据，1&lt;=N&lt;=10000,1&lt;=M&lt;=5<BR><BR> 
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
<tr><td>2 2
1
2 3
</td><td>3
</td></tr></table>
