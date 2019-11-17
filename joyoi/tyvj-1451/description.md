# 

 
 # 题目描述 
Tyvj的Admin--zhq同学将在寒假开始实行Tyvj&nbsp;new&nbsp;web计划，把Tyvj打造成为中国一流的信息学在线评测系统。Tyvj的new&nbsp;web计划里一共有n项，编号1~n，每项的重要度为v[i],Admin—zhq同学共工作m次，第j次从编号为l[j]~r[j]的项目里选择重要度最大的一项任务完成，所获得的进展量为(l[j]+r[j])*该任务的重要度。完成该任务后该任务的重要度变为0。请问Admin在工作m次后可以有多少进展量呢？<BR><BR>注：数据保证初始情况下所有任务的重要度不同。 

 
 # 输入格式 
第一行为n，m<BR>第二行n个整数v[i]。<BR>接下来m行，每行两个整数l,r，表示Admin这一次将会从编号为l~r的项目里选择(包括l，r)重要度最大的来完成。<BR> 

 
 # 输出格式 
最终的进展量。由于结果可能会比较大，你只需要输出mod2011之后的结果即可。 

 
 # 提示 
对于50%的数据，1&lt;=n,m&lt;=1000<BR>对于100%的数据，1&lt;=n,m&lt;=200000,1&lt;=L&lt;=r&lt;=n,1&lt;=v[i]&lt;=100000<BR>来源：lydliyudong&nbsp;&nbsp;&nbsp;&nbsp;Tyvj&nbsp;February二月月赛第二场&nbsp;&nbsp;第3道 
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
<tr><td>5 3
1 2 3 4 5
1 3
2 3
1 5
</td><td>52</td></tr></table>
