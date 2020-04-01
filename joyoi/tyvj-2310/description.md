# 

 
 # 题目描述 
<p>
YY是个密码学专家。近日他正在研究一种数列E={E[1],E[2],……,E[n]}，且E[1]=E[2]=p（p为一个质数）<br>E[i]=E[i-2]*E[i-1] （若2<i<=n）。例如{2,2,4,8,32,256,8192,……}就是p=2的数列。在此基础上他又<br>设计了一种加密算法，该算法可以通过一个密钥q (q<p)将一个正整数n加密成另外一个正整数d<br>计算公式为：d=E[n] mod q。现在YY想对一组数据进行加密，但他对程序设计不太感兴趣<br>请你帮助他设计一个数据加密程序。<br><br></p> 

 
 # 输入格式 
<p>
第一行读入m，p。其中m表示数据个数，p用来生成数列E。<br>以下有m行，每行有2个整数n，q。n为待加密数据，q为密钥。<br>数据范围: <br>0 < p<br>n< 2^31<br>0 < q < p<br>0 < m <= 5000。<br><br></p> 

 
 # 输出格式 
<p>
将加密后的数据按顺序输出到文件<br>第i行输出第i个加密后的数据。<br><br>输入样例1<br>2 7<br>4 5<br>4 6<br><br>输入样例2<br>4 7<br>2 4<br>7 1<br>6 5<br>9 3<br><br><br></p> 
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
<tr><td>输出样例1
3
1

输出样例2
3
0
1
1
</td><td></td></tr></table>
