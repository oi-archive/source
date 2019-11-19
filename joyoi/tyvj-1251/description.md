# 

 
 # 题目描述 
若某个家族人员过于庞大，要判断两个是否是亲戚，确实还很不容易，现在给出某个亲戚关系图，求任意给出的两个人是否具有亲戚关系。<BR>规定：x和y是亲戚，y和z是亲戚，那么x和z也是亲戚。如果x,y是亲戚，那么x的亲戚都是y的亲戚，y的亲戚也都是x的亲戚。<BR> 

 
 # 输入格式 
第一行：三个整数n,m,p，（n&lt;=5000,m&lt;=5000,p&lt;=5000），分别表示有n个人，m个亲戚关系，询问p对亲戚关系。<BR>以下m行：每行两个数Mi，Mj，1&lt;=Mi，Mj&lt;=N，表示Ai和Bi具有亲戚关系。<BR>接下来p行：每行两个数Pi，Pj，询问Pi和Pj是否具有亲戚关系。<BR> 

 
 # 输出格式 
P行，每行一个’Yes’或’No’。表示第i个询问的答案为“具有”或“不具有”亲戚关系。<BR> 

 
 # 提示 
cdwind整理提交<BR> 
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
<tr><td>6 5 3
1 2
1 5
3 4
5 2
1 3
1 4
2 3
5 6
</td><td>Yes
Yes
No
</td></tr></table>
