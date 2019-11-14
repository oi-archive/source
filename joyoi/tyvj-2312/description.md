# 

 
 # 题目描述 
<p>
Orez很喜欢搜集一些神秘的数据，并经常把它们排成一个矩阵进行研究。最近，Orez又得到了一些数据，并已经把它们排成了一个n行m列的矩阵。通过观察，Orez发现这些数据蕴涵了一个奇特的数，就是矩阵中上下对称且左右对称的正方形子矩阵的个数。<br>Orez自然很想知道这个数是多少，可是矩阵太大，无法去数。只能请你编个程序来计算出这个数。<br><br></p> 

 
 # 输入格式 
<p>
文件的第一行为两个整数n和m。接下来n行每行包含m个正整数，表示Orez得到的矩阵。<br><br></p> 

 
 # 输出格式 
<p>
文件中仅包含一个整数answer，表示矩阵中有answer个上下左右对称的正方形子矩阵。<br><br></p> 
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
<tr><td>5 5
4 2 4 4 4 
3 1 4 4 3 
3 5 3 3 3 
3 1 5 3 3 
4 2 1 2 4 

</td><td>27

数据范围
对于30%的数据  n，m≤100
对于100%的数据  n，m≤1000 ，矩阵中的数的大小≤109</td></tr></table>
