# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2224/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjIyNC9wcm9ibGVtc19pbWFnZXMvMjU4Ni8xMjk0XzEuanBn.jpg"></p> 

 
 # 输入格式 
<p>
第一行两个整数N和M，为矩阵的边长。<br>第二行一个整数D，为豆子的总个数。<br>第三行包含D个整数V1到VD，分别为每颗豆子的分值。<br>接着N行有一个N×M的字符矩阵来描述游戏矩阵状态，0表示空格，#表示障碍物。而数字1到9分别表示对应编号的豆子。<br></p> 

 
 # 输出格式 
<p>
仅包含一个整数，为最高可能获得的分值。<br></p> 

 
 # 提示 
<p>
50%的数据满足1≤D≤3。<br>100%的数据满足1≤D≤9，1≤N, M≤10，-10000≤Vi≤10000。<br></p> 
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
<tr><td>3 8
3
30 -100 30
00000000
010203#0
00000000
</td><td>38</td></tr></table>
