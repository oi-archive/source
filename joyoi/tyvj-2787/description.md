# 

 
 # 题目描述 
<p>
给定的变量X[i]为非负整数（对于任意1<=i<=n）,使目标函数<br>f(x[1], x[2],..., x[N])=x[1]+x[2]+...+x[N] ……①满足<br>c[1]*x[1]+c[2]*x[2]+...+c[N]*x[N]=V  ……②<br>   满足方程②的有序数列（X[1],X[2]，……，X[N]）称一组为可行解。你的任务是找出一组可行解并使函数①的值最小。<br>   举个例子说,若N=2,C[1]=2,C[2]=4,V=6,那么有两对满足的可行解（1，1）<br>和（3，0），因为f(1,1) < f(3,0),所以 （1，1） 是最优解，对应的函数值 f(1,1) = 2。<br><br><center><img src="/source/joyoi/tyvj-2787/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjc4Ny9wcm9ibGVtc19pbWFnZXMvMzMwOC9wZy5qcGc=.jpg"></img></center></p> 

 
 # 输入格式 
<p>
第一行包含一个正整数N（0<N<=3）<br>第二行N个数分别为C[1]，C[2]……C[N]（0<C[i]<=10^6）<br>第三行包含一个正整数V（0<V<=10^6）<br></p> 

 
 # 输出格式 
<p>
一行表示可行解对应的函数f的最小值。若无解请输出－1。</p> 
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
<tr><td>输入样例1：
2
2 4
6
输出样例1：
2

输入样例2：
2
7 4
9
输出样例2：
-1

</td><td>（见上）</td></tr></table>
