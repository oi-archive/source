# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2680/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjY4MC9wcm9ibGVtc19pbWFnZXMvMzE1NS8xODg1LmpwZw==.jpg"> </p> 

 
 # 输入格式 
<p>
The first line of the input file contains the numbers N and P, and<br>a real number D, 2 ≤ N ≤ 100, 1 ≤ P ≤ 3000, 1 ≤ D ≤ 10,000.<br>The number N is the number of towns, the number P is the number of<br>railroads, and D is the range of the radio in kilometers (a decimal <br>number two digits precise). The towns are numbered 1 to N. Each of<br>the following N lines contains data describing one town, i.e. two<br>integers, X and Y, -5000 ≤ X, Y ≤ 5000, representing the town ’ s<br>coordinates.<br>Each of the following P lines contains data describing one railroad<br>track, i.e. two integers G1 and G2, saying there is a railroad<br>rack connecting G1 i G2.<br>The next line contains the starting positions of Mirko and Slavku,<br>the integers U and V. Mirko starts from town U, Slavko from town V.<br>U and V will represent two towns separated at most D kilometers<br>in distance.</p> 

 
 # 输出格式 
<p>
The output file should contain the numbers of all the towns Slavko<br>can reach. These numbers should be sorted in increasing order, each of<br>them written on a separate line.</p> 
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
<tr><td>5 4 1.5
0 1
0 0
4 1
4 0
2 2
1 3
1 5
3 5
2 4
2 1</td><td>1
3</td></tr></table>
