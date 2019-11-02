# 

 
 # 题目描述 
<p>
个点构成一棵树，开始时任两点之间的边全是灰色的。现决定将已有的边重新涂色，并且是彩虹的颜色。每天将选择两个点点A，B和一种色调C，并A，B之间色调不是C的道路涂成C。现在将具体方案事先告诉你，求输出每种色调被使用了多少次.<br></p> 

 
 # 输入格式 
<p>
第一行,一个整数N,点的编号是1~N。 <br>下面若干行，每行两个数A,B,表示A,B之间有道路直接连接。 <br>下面一行,一个整数Q,表示计划的持续天数。 <br>下面Q行,每行三个正整数,S,T,C(1<=S,T<=N,1<=C<=7),表示将S,T之间颜色不是C的道路的颜色都涂成C。 <br><br><br></p> 

 
 # 输出格式 
<p>
共包含7行,第i行包含一个整数，表示颜色i的使用次数。 <br></p> 
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
<tr><td>4
1 2
2 3
3 4
3
1 4 1
2 4 2
1 3 1
</td><td>
4
2
0
0
0
0
0
</td></tr></table>
