# 

 
 # 题目描述 
<p>
Bessy 正在上学并且分数还不错. 她考了N (一个数据中1 <= N <= 50,000, 其<br>余数据 1 <= N <= 50,00) 次试,每次考试得分为T_i, 满分为P_i(0 <= T_i <=<br>P_i < 40,000; 0 < P_i).<br><br>在计算总分时,她的老师先将把分数(P_i/T_i)最低的D个试卷去掉,然后将其余P_i<br>的和除以其余T_i的和作为Bessy的分数. Bessy精通数学,所以很快发觉这并没<br>有想象中那么好.<br><br>Bessy想告诉她的老师所有附和以下条件的D: 如果令一组(D个)分数去掉,她的分<br>数回比老师算出来的更高.<br><br>Bessy 很惊讶地发现她没有两次考试得分百分点是一样的.<br><br></p> 

 
 # 输入格式 
<p>
*第一行: N<br><br>*第2..N+1行: 第i行里有 T_i 和 P_i.<br><br></p> 

 
 # 输出格式 
<p>
<br>* 第一行: K, 符合条件的D的个数.<br><br>*第2..K+1行: 按递增顺序,每行一个符合条件的D.<br><br></p> 
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
<tr><td>5
1 2
5 9
3 8
4 10
1 3

输入解释:

Bessy 考了5门试, 分数分别为1/2, 5/9, 3/8, 4/10, 1/3.
</td><td>2
1
2

输出解释:

当D=1时, 去掉1/3将使总分变成13/29, 而去掉3/8则得到11/24.

当D=2时, 去掉1/3和3/8得到总分10/21. 更高的7/14则能由去掉3/8和4/10
得到.</td></tr></table>
