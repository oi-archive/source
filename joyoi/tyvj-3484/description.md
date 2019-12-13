# 

 
 # 题目描述 
<p>
直线上N颗行星，X=i处有行星i,行星J受到行星I的作用力，当且仅当i<=AJ.此时J受到作用力的大小为<br>Fi->j=Mi*Mj/(j-i)<br>其中A为很小的常量，故直观上说每颗行星都只受到距离遥远的行星的作用。请计算每颗行星的受力，只要<br>结果的相对误差不超过5%即可.<br></p> 

 
 # 输入格式 
<p>
第一行两个整数N和A.<br>1<=N<=10^5.1<A<=3.5.<br>接下来N行输入N个行星的质量Mi,0<=Mi<=10^7<br></p> 

 
 # 输出格式 
<p>
N行，依次输出各行星的受力情况<br></p> 

 
 # 提示 
<p>
精确结果应该为0 0 0 2 3,但样例输出的结果误差不超过5%,也算对<br></p> 
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
<tr><td>5 0.3
3
5
6
2
4
</td><td>
0.000000
0.000000
0.000000
1.968750
2.976000
</td></tr></table>
