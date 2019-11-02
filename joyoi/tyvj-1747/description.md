# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;公司有n个同样的仓库需要有人把守，你的任务是决定应当录用哪些人。现<BR>有m个人应聘，其中第i个人的能力为Pi，而这个数值也是他的工资，因此公司所<BR>支付的工资在数值上等于所有被录用的工人的能力之和。<BR>&nbsp;&nbsp;&nbsp;&nbsp;一个仓库最多被一个人把守，但一个人可以同时把守多个仓库。第j个仓库的安<BR>全值为Uj=Pi/Ki，其中i为看守者编号，Ki表示此人看守的仓库数。如果某仓库<BR>无人看守，则它的安全值为0。整个系统的安全值为所有Uj的最小值。<BR>&nbsp;&nbsp;&nbsp;&nbsp;计算整个系统安全值的最大值和此最大值条件下所有看守工资总和的最小值。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入文件storage.in的第一行包含两个数n,&nbsp;m(1&lt;=n,m&lt;=100)，即仓库数目和<BR>应聘人数，第二包含m个数，即P1，P2，…Pm(均不超过1000)。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出文件storage.out仅包含一行，即系统安全值的最大值Umax和此时的工<BR>资最小值Smin。 

 
 # 提示 
SCOI2004&nbsp;day1&nbsp;T2 
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
<tr><td>2 5
10 8 6 4 1
</td><td>8 18
</td></tr></table>
