# 

 
 # 题目描述 
<p>
加油站有N种汽油,每种汽油用三个整数(Ai,Bi,Ci)表示,即购买1单位汽油,共容量为Ai升,要Bi的资金且价值为Ci(价值越高代表油越好).现在你要用恰好B的资金,买A升的汽油,当然你希望混合后的汽油价值最高. <br>设第i种汽油购买Xi个单位(Xi为非负实数),则X1*C1+.......+Xn*Cn表示的就是混合后汽油的价值 <br></p> 

 
 # 输入格式 
<p>
第一行三个整数N,A,B <br>以下N行每行3个整数Ai,Bi,Ci <br></p> 

 
 # 输出格式 
<p>
输出仅一个数,即最大价值保留三位小数,无法达成就输出0.000 <br></p> 

 
 # 提示 
<p>
A,B均大于0,小于等于100000<br>Ai,Bi,Ci均大于0小于等于1000<br>50%数据N小于等于100<br>100%数据N小于等于100000<br></p> 
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
<tr><td>2 3 3
1 2 1
2 1 1
</td><td>
2.000
</td></tr></table>
