# 

 
 # 题目描述 
<p>
 给定一个长度为n的序列C1, C2…Cn，我们称C的单调序列就是把它改成一个严格单调递增的序列D1,D2..Dn(D1<D2<..<Dn)或者是严格递减的序列D1,D2..Dn(D1>D2>..>Dn)，同时我们定义它的代价就是|D1-C1|+|D2-C2|…|Dn-Cn|．<br>这个问题你是不是看得非常眼熟呢? <br>下面请考虑这个问题的加强版把．<br>请你把这个长度为n的序列分成m段，其中要求将每段改成一个单调序列，同时要求代价和最小．比如说1,2,3,2,1就是一个满足要求2段单调序列(1,2,3),(2,1)，而将1,1,1,1改成2段单调序列的最优的方案就是(1,2),(2,1)，它的代价就是2．<br></p> 

 
 # 输入格式 
<p>
第1行2个数n, m．<br>接下来n行，每行一个数，按顺序给出C1, C2…Cn．<br></p> 

 
 # 输出格式 
<p>
一个数，即最小的代价和．<br></p> 

 
 # 提示 
<p>
30%的数据,  n<=100．<br>20%的数据,  m=1．<br>100%的数据，n<=2000, m<=min{n,10}，Ci<=10000．<br></p> 
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
<tr><td>6 1
1
2
3
3
2
1
</td><td>9</td></tr></table>
