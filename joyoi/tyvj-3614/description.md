# 

 
 # 题目描述 
<p>
给出N行M列的数字矩阵.<br>从第一行的数列中选一个数字,从最后一行的数列中选一个数字.<br>从其它的行中,每行取一到两个数.<br>将取出来的数字相乘,希望其可以被K整除.<br>你只需要输出结果Mod L的值.</p> 

 
 # 输入格式 
<p>
第一行给出N,M<br>第二行给出K,L<br>下面有N行M列,用于描述数字矩阵<br>其值在[1,1000000]各不相同.<br><br>N在[3,200]<br>M在[3,10000]<br>K在[2,200000]<br>L在[2,30000]<br><br></p> 

 
 # 输出格式 
<p>
取法总数Mod L</p> 

 
 # 提示 
<p>
以下为样例的12种取法.<br>5 2 1<br>2 1 2<br>3 7 4<br>Pic. 1<br><br>5 2 1<br>2 1 2<br>3 7 4<br>Pic. 2	<br><br>5 2 1<br>2 1 2<br>3 7 4<br>Pic. 3	<br><br>5 2 1<br>2 1 2<br>3 7 4<br>Pic. 4	<br><br>5 2 1<br>2 1 2<br>3 7 4<br>Pic. 5	<br><br>5 2 1<br>2 1 2<br>3 7 4<br>Pic. 6<br><br>5 2 1<br>2 1 2<br>3 7 4<br>Pic. 7	<br><br>5 2 1<br>2 1 2<br>3 7 4<br>Pic. 8	<br><br>5 2 1<br>2 1 2<br>3 7 4<br>Pic. 9	<br><br>5 2 1<br>2 1 2<br>3 7 4<br>Pic. 10	<br><br>5 2 1<br>2 1 2<br>3 7 4<br>Pic. 11	<br><br>5 2 1<br>2 1 2<br>3 7 4<br>Pic. 12<br></p> 
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
<tr><td>3 3
12 100
5 2 1
2 1 2
3 7 4
</td><td>
12</td></tr></table>
