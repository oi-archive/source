# 

 
 # 题目描述 
<p>
Irena和Sirup正准备下个周末的Party。为这个Party,他们刚刚买了一个非常大的圆桌。他们想邀请每个人，但他们现在不知道如何分配座次。Irena说当有超过K个女孩座位相邻（即这些女孩的座位是连续的，中间没有男孩）的话，她们就会说一整晚的话而不和其他人聊天。<br>Sirup没有其他选择，只有同意她。然而，作为一名数学家，他很快地痴迷于所有可能方案。<br>题目说明：<br>N个人围绕着圆桌坐着，其中一些是男孩，另一些是女孩。你的任务是找出所有合法的方案数，使得不超过K个女孩座位是连续的。<br>循环同构会被认为是同一种方案。<br></p> 

 
 # 输入格式 
<p>
第一行有一个数T，表示以下有T组数据，每组数据有两个整数N，K。<br>每组数据之间有一个空行隔开。<br></p> 

 
 # 输出格式 
<p>
输出T行，每行顺次对应一组测试数据。<br>每组数据你需要输出最后的方案数除以100000007的余数。<br><br></p> 
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
<tr><td>3

3 1

3 3

4 1


</td><td>2
4
3

解释：
第一组数据的方案是：MMM，MMW (M是男孩, W是女孩)。
第二组数据的方案是：MMM，MMW，MWW，WWW。
第三组数据的方案是：MMMM, MMMW,MWMW。

约束和限制：
对于20%的数据T < = 20;
对于100%的数据T < = 50;
对于20%的数据N,K < = 20;
对于100%的数据N,K < = 2000;</td></tr></table>
