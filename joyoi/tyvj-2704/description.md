# 

 
 # 题目描述 
<p>
有一个长度为 N 的序列P 和两种操作，共 Q个： <br>1.  给定 L, R, A, B，将第 L 到第 R 个之间的每个元素 Px 变成（（X-L+1）×A）mod B  。  <br>2.  给定 L, R，询问第 L 到第 R 个元素的和。 <br>数据规模：N≤10^9  ，Q≤50000  ，  A, B≤106<br> </p> 

 
 # 输入格式 
<p>
The first line contains two integers N i Q (1 ≤ N ≤ 1 000 000 000) (1 ≤ Q ≤ 50 <br>000), number of boxes and number of queries.<br>The next Q lines contain information about the simulation.<br>If the line starts with 1, than it follows the format "1 L R A B" (1 ≤ L ≤ R ≤ N) (1 <br>≤ A, B ≤ 1 000 000), meaning that Aladin keyed in numbers L, R, A and B in the <br>device and allowed the device to do its job.<br>If the line starts with 2, than it follows the format "2 L R" (1 ≤ L ≤ R ≤ N). <br>Meaning that Aladin wonders how many stones in total are ther stones are in <br>boxes labeled L to R (inclusive).</p> 

 
 # 输出格式 
<p>
For each query beginning with 2 output the answer to that particular query. <br>Queries should be processed in the order they are given in the input.</p> 

 
 # 提示 
<p>
The boxes start containing {0, 0, 0, 0, 0, 0}, 0 stones in total. <br>After that the device sets the stones to {1 mod 2, 2 mod 2, 3 mod 2, 4 mod 2, <br>5 mod 2, 0} = {1,0,1,0,1,0}, or 3 stones in total.</p> 
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
<tr><td>6 3
2 1 6
1 1 5 1 2
2 1 6
</td><td>0
3</td></tr></table>
