# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;一个n*m矩阵由n行m列共n*m个数排列而成。两个矩阵A和B可以相乘当且仅当A的列数等于B的行数。一个N*M的矩阵乘以一个M*P的矩阵等于一个N*P的矩阵，运算量为nmp。<BR>&nbsp;&nbsp;&nbsp;矩阵乘法满足结合律，A*B*C可以表示成(A*B)*C或者是A*(B*C)，两者的运算量却不同。例如当A=2*3&nbsp;B=3*4&nbsp;C=4*5时，(A*B)*C=64而A*(B*C)=90。显然第一种顺序节省运算量。<BR>&nbsp;&nbsp;&nbsp;现在给出N个矩阵，并输入N+1个数，第i个矩阵是a[i-1]*a[i] 

 
 # 输入格式 
第一行n(n&lt;=100)<BR>第二行n+1个数 

 
 # 输出格式 
最优的运算量 
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
<tr><td>3
2 3 4 5</td><td>64</td></tr></table>
