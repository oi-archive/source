# 

 
 # 题目描述 
<p>
对于一个1-N的排列(ai)，每次你可以交换两个数ax与ay(x<>y)，代价为W(ax)+W(ay)<br>若干次交换的代价为每次交换的代价之和。请问将(ai)变为(bi)所需的最小代价是多少。<br><br></p> 

 
 # 输入格式 
<p>
第一行N。<br>第二行N个数表示wi。<br>第三行N个数表示ai。<br>第四行N个数表示bi。<br><br>2<=n<=1000000<br>100<=wi<=6500<br>1<=ai,bi<=n<br>ai各不相等，bi各不相等<br>(ai)<>(bi)<br>样例中依次交换数字(2,5)(3,4)(1,5)<br></p> 

 
 # 输出格式 
<p>
一个数，最小代价。<br></p> 

 
 # 提示 
<p>
感谢MT大牛贡献译文.</p> 
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
<tr><td>6
2400 2000 1200 2400 1600 4000
1 4 5 3 6 2
5 3 2 4 6 1
</td><td>11200
</td></tr></table>
