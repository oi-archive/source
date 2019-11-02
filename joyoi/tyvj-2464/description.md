# 

 
 # 题目描述 
<p>
勤奋的Farmer John想要建造一个四面的栅栏来关住牛们。他有一块长为n（4<=n<=2500）的木板，他想把这块本板切成4块。<br>这四块小木板可以是任何一个长度只要Farmer John能够把它们围成一个合理的四边形。他能够切出多少种不同的合理方案。<br>注意：<br><br>       *只要大木板的切割点不同就当成是不同的方案（像全排列那样），不要担心另外的特殊情况，go ahead。<br><br>       *栅栏的面积要大于0.<br><br>       *输出保证答案在longint范围内。<br><br>       *整块木板都要用完。<br><br><br></p> 

 
 # 输入格式 
<p>
*第一行：一个数n<br><br></p> 

 
 # 输出格式 
<p>
*第一行：合理的方案总数<br></p> 
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
<tr><td>6
</td><td>6


输出详解：

Farmer John能够切出所有的情况为: (1, 1, 1,3); (1, 1, 2, 2); (1, 1, 3, 1); (1, 2, 1, 2); (1, 2, 2, 1); (1, 3,1, 1);
(2, 1, 1, 2); (2, 1, 2, 1); (2, 2, 1, 1); or (3, 1, 1, 1).
下面四种 -- (1, 1, 1, 3), (1, 1, 3, 1), (1, 3, 1, 1), and (3,1, 1, 1) – 不能够组成一个四边形.</td></tr></table>
