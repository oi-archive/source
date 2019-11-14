# 

 
 # 题目描述 
【问题描述】：	lxhgww最近收到了一个01序列，序列里面包含了n个数，这些数要么是0，要么是1，现在对于这个序列有五种变换操作和询问操作：<BR>	0&nbsp;a&nbsp;b&nbsp;把[a,&nbsp;b]区间内的所有数全变成0<BR>	1&nbsp;a&nbsp;b&nbsp;把[a,&nbsp;b]区间内的所有数全变成1<BR>	2&nbsp;a&nbsp;b&nbsp;把[a,b]区间内的所有数全部取反，也就是说把所有的0变成1，把所有的1变成0<BR>	3&nbsp;a&nbsp;b&nbsp;询问[a,&nbsp;b]区间内总共有多少个1<BR>	4&nbsp;a&nbsp;b&nbsp;询问[a,&nbsp;b]区间内最多有多少个连续的1<BR>对于每一种询问操作，lxhgww都需要给出回答，聪明的程序员们，你们能帮助他吗？ 

 
 # 输入格式 
【输入】<BR>&nbsp;&nbsp;&nbsp;输入数据第一行包括2个数，n和m，分别表示序列的长度和操作数目<BR>&nbsp;&nbsp;&nbsp;第二行包括n个数，表示序列的初始状态<BR>&nbsp;&nbsp;&nbsp;接下来m行，每行3个数，op,&nbsp;a,&nbsp;b，（0&lt;=op&lt;=4，0&lt;=a&lt;=b&lt;n）表示对于区间[a,&nbsp;b]执行标号为op的操作 

 
 # 输出格式 
【输出】<BR>&nbsp;&nbsp;&nbsp;对于每一个询问操作，输出一行，包括1个数，表示其对应的答案 

 
 # 提示 
【数据范围】<BR>&nbsp;&nbsp;&nbsp;对于30%的数据，1&lt;=n,&nbsp;m&lt;=1000<BR>&nbsp;&nbsp;&nbsp;对于100%的数据，1&lt;=n,&nbsp;m&lt;=100000 
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
<tr><td>【样例输入】
10 10
0 0 0 1 1 0 1 0 1 1
1 0 2
3 0 5
2 2 2
4 0 4
0 3 6
2 3 7
4 2 8
1 0 5
0 5 6
3 3 9</td><td>【样例输出】
5
2
6
5</td></tr></table>
