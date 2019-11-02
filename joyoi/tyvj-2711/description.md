# 

 
 # 题目描述 
<p>
A telecom company is developing a GSM network in the city of Vrsar. Their contract with the city specifies the minimum number of households that need to be covered by the signal. Due to budget constraints they can only build one antenna with a certain range. Since the cost is proportional to the range of the antenna, they would like to place the antenna so that the range required to meet the terms of the contract is minimized.<br>There are N households in Vrsar, each represented by a pair of integer coordinates. The antenna can be placed at any point in the plane (not necessarily with integer coordinates) and the range of the antenna can be any positive real number. If the range of the antenna is R, then a household is covered by the signal if the distance between the antenna and the household is at most R.<br>Write a program that, given the locations of the households and an integer K, finds the minimum range required and one possible location for the antenna so that at last K households are covered by the signal.<br><br>题目分析<br>题目大意是给出N个点的坐标，要求能够覆盖其中至少K个点的圆的最小半径及圆心位置。<br></p> 

 
 # 输入格式 
<p>
The first line of input contains two integers N and K (2≤K≤N≤500) – the total number of households and the minimum number of households that need to be covered by the signal.<br>Each of the following N lines contains two integers X and Y (0≤X,Y≤10 000) – the coordinates of one household. No two households will be located at the same coordinates.<br><br></p> 

 
 # 输出格式 
<p>
The first line of output should contain the minimum required range R for the antenna – a real number.<br>The second line of output should contain the coordinates of the antenna - two real numbers X and Y.<br>Note: If there are multiple solutions, you should output any one of them. All three numbers should be output either in standard decimal form or scientific notation.<br><br>Grading<br>Your solution will be marked correct if and only if the following two conditions ar satisfied:<br>&#61548;	The absolute difference between R and the minimum required range as determined by the jury is less than or equal to 0.0001.<br>&#61548;	The antenna with range R+0.0002 placed at coordinates (X,Y) covers at least K households.<br><br></p> 

 
 # 提示 
<p>
存在精度误差,请不要提交</p> 
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
<tr><td>10 5 
1 8 
2 6 
4 8 
2 2 
9 7 
8 5 
5 3 
3 3 
4 6 
4 1 </td><td>2.236068 
3 4 </td></tr></table>
