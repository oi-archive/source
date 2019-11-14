# 

 
 # 题目描述 
<p>
<br>对于一个给定的序列a1, …, an，我们对它进行一个操作reduce(i)，该操作将数列中的元素ai和ai+1用一个元素max(ai，ai+1)替代，这样得到一个比原来序列短的新序列。这一操作的代价是max(ai，ai+1)。进行n-1次该操作后，可以得到一个长度为1的序列。我们的任务是计算代价最小的reduce操作步骤，将给定的序列变成长度为1的序列。<br><br></p> 

 
 # 输入格式 
<p>
第一行为一个整数n( 1 <= n <= 1,000,000 )，表示给定序列的长度。接下来的n行，每行一个整数ai（0 <=ai<= 1, 000, 000, 000），为序列中的元素。<br></p> 

 
 # 输出格式 
<p>
只有一行，为一个整数，即将序列变成一个元素的最小代价。<br><br></p> 

 
 # 提示 
<p>
30%的测试数据 n<=500；<br>50%的测试数据 n <= 20,000。<br></p> 
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
1
2
3	</td><td>5
</td></tr></table>
