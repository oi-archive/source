# 

 
 # 题目描述 
<p>
睡觉的时间（naptime.pas\c\cpp）<br><br>【题目描述】<br>　　奶牛喜欢睡觉补充能量,他将时间分为N个时段。他将选择M个时段睡觉(M<=N)。每个时段有一个补充能量的值，奶牛希望通过睡M个时段（不一定都连续）来获得最大的能量。不幸的是，如果奶牛选择ai1,ai2,ai3....aik这连续k段作为睡觉的时段(k<=M)，那么获得的能量就是w(ai2)+w(ai3)+...+w(aik)，(ai1作为奶牛的进入睡眠时间)。更不幸的是，你要解决的问题是环形的。(见Sample)<br>　　现在请问怎样获得最大能量? <br></p> 

 
 # 输入格式 
<p>
　　输入文件naptime.in第1行: N,M (3 <= N <= 3,830)<br>　　第2行到第N+1行: N行，每行包括一个整数，为该时段能得到的能量值w(ai) (0 <= w(ai )<= 200,000)。 <br></p> 

 
 # 输出格式 
<p>
　　输出文件naptime.out只有一行，一个数字，能获得的最大能量值。</p> 
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
<tr><td>5 3
2
0
3
1
4
</td><td>6</td></tr></table>
