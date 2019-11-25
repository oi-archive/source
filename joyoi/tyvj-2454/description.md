# 

 
 # 题目描述 
<p>
   Farmer John的农场里有P个牧场，有C条无向道路连接着他们，第i条道路连接着两个牧场Ai和Bi，注意可能有很多条道路连接着相同的Ai和Bi，并且Ai有可能和Bi相等。Farmer John在1号牧场里。<br>由于地震，某些牧场被损坏，但由于信春哥，C条道路没有一条损坏。有N头奶牛，他们在不同的牧场里，于是N <= P。他们一一向Farmer John报告。第i头奶牛报告给Farmer John一个整数Report_i，代表第Report_i个牧场没有损毁，但不能够从第Report_i个牧场经过一些没有损坏的牧场到达1号牧场。<br>现在Farmer John想知道，最少有多少损坏的牧场。<br></p> 

 
 # 输入格式 
<p>
第一行三个整数 P，C，N<br>第2..C+1行：每行两个整数Ai,Bi<br>第C+2..C+N+1行：第C+1+i行包含一个整数，Report_i<br></p> 

 
 # 输出格式 
<p>
一个整数，代表最少有多少损坏的牧场<br></p> 
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
<tr><td>5 5 2
1 2
2 3
3 5
2 4
4 5
4
5
</td><td>1
【数据规模】
1 <= P <=3000
1 <= C <=20000</td></tr></table>
