# 

 
 # 题目描述 
<p>
Farmer John is running out of supplies and needs to purchase H (1<br><= H <= 50,000) pounds of hay for his cows.<br><br>He knows N (1 <= N <= 100) hay suppliers conveniently numbered 1..N.<br>Supplier i sells packages that contain P_i (1 <= P_i <= 5,000)<br>pounds of hay at a cost of C_i (1 <= C_i <= 5,000) dollars. Each<br>supplier has an unlimited number of packages available, and the<br>packages must be bought whole.<br><br>Help FJ by finding the minimum cost necessary to purchase at least<br>H pounds of hay.<br><br><br>N种HAY,要H个,每种HAY有个价格,还有对应的数量,要买H个HAY,至少要多少钱.<br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: N and H<br><br>* Lines 2..N+1: Line i+1 contains two space-separated integers: P_i<br>        and C_i<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: A single integer representing the minimum cost FJ needs to<br>        pay to obtain at least H pounds of hay.<br></p> 
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
<tr><td>2 15
3 2
5 3

</td><td>9


FJ can buy three packages from the second supplier for a total cost of 9.</td></tr></table>
