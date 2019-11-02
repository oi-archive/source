# 
题目描述
有1个长度为n的序列bi，初始全为0，pluto 认为这个序列是优雅的当且仅当bi = ai。

现在有m 组操作，对于第i 组操作有三个参数li; ri; di，表示将bli - bri 都加上di

问是否存在1个k，经过k 组操作后，序列b 是优雅的，如果存在则输出满足条件的最小的k，否则输出’-1’。

输入输出格式
输入格式：

一行两个数n;m

第二行n 个数a1::an

接下来m 行每行三个数li; ri; di

输出格式：

一行一个数最小的满足条件的k 或者是“-1”。

输入输出样例

输入样例： 

5 6

1 3 2 5 6

1 5 1

2 5 2

3 4 -1

4 5 3

1 5 2

1 5 -2

输出样例：

4
说明

step0(bi)：0 0 0 0 0

step1(bi)：1 1 1 1 1

step2(bi)：1 3 3 3 3

step3(bi)：1 3 2 2 3

step4(bi)：1 3 2 5 6

step5(bi)：3 5 4 7 8

step6(bi)：1 3 2 5 6

对于50% 的数据，1<=n;m<=1000。 

对于80% 的数据，1<=n;m<=10^5。

对于100% 的数据，1<=n;m<=10^6，|ai|<=10^18，1<= li<=ri<=n，|di| <=10^9。# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>5 6
1 3 2 5 6
1 5 1
2 5 2
3 4 -1
4 5 3
1 5 2
1 5 -2</td><td>4</td></tr></table>
