# 

 
 # 题目描述 
<p>
	有N个村庄坐落在一条直线上，第i(i>1)个村庄距离第1个村庄的距离为Di。需要在这些村庄中建立不超过K个通讯基站，在第i个村庄建立基站的费用为Ci。如果在距离第i个村庄不超过Si的范围内建立了一个通讯基站，那么就成它被覆盖了。如果第i个村庄没有被覆盖，则需要向他们补偿，费用为Wi。现在的问题是，选择基站的位置，使得总费用最小。<br>输入数据 (base.in)<br>	输入文件的第一行包含两个整数N,K，含义如上所述。<br>	第二行包含N-1个整数，分别表示D2,D3,…,DN ，这N-1个数是递增的。<br>	第三行包含N个整数，表示C1,C2,…CN。<br>	第四行包含N个整数，表示S1,S2,…,SN。<br>	第五行包含N个整数，表示W1,W2,…,WN。<br></p> 

 
 # 输入格式 
<p>
	输出文件中仅包含一个整数，表示最小的总费用。<br></p> 

 
 # 输出格式 
<p>
3 2<br>1 2<br>2 3 2<br>1 1 0<br>10 20 30<br></p> 
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
<tr><td>	4
</td><td>	40%的数据中，N<=500；
	100%的数据中，K<=N，K<=100，N<=20,000，Di<=1000000000，Ci<=10000，Si<=1000000000，Wi<=10000。</td></tr></table>
