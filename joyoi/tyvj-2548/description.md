# 

 
 # 题目描述 
<p>


 
 # 输入格式 
<p>


 
 # 输出格式 
<p>

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
<tr><td>5 5
2 1
1 5
2 3
1 4
3 4

INPUT DETAILS:

FJ is comparing 5 cows and has already determined that cow 2 > cow
1, cow 1 > cow 5, cow 2 > cow 3, cow 1 > cow 4, and cow 3 > cow 4
(where the '>' notation means "produces milk more quickly").
</td><td>
3

OUTPUT DETAILS:

From the information in the 5 test results, Farmer John knows that
since cow 2 > cow 1 > cow 5 and cow 2 > cow 3 > cow 4, cow 2 has
the highest rank. However, he needs to know whether cow 1 > cow 3
to determine the cow with the second highest rank. Also, he will
need one more question to determine the ordering between cow 4 and
cow 5. After that, he will need to know if cow 5 > cow 3 if cow 1
has higher rank than cow 3. He will have to ask three questions in
order to be sure he has the rankings: "Is cow 1 > cow 3?  Is cow 4
> cow 5? Is cow 5 > cow 3?"