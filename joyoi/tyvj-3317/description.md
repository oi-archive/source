# 

 
 # 题目描述 
<p>
描述 Description   <br>　　一个铁路线上有n(2 <= n <= 10000)个火车站，每个火车站到该线路的首发火车站距离都是已知的。任意两站之间的票价如下表所示：<br>站之间的距离与票价的关系表如下：<br>　　　X　　　　　　　　　　　票价<br>0 < X <= L1　　　　　　　　　C1<br>L1 < X <= L2　　　　　　　　　C2<br>L2 < X <= L3　　　　　　　　　C3<br>　　其中L1，L2，L3，C1，C2，C3都是已知的正整数，且(1 <= L1 < L2 < L3 <= 10^9, 1 <= C1 < C2 < C3 <= 10^9)。显然若两站之间的距离大于L3，那么从一站到另一站至少要买两张票。注意：每一张票在使用时只能从一站开始到另一站结束。<br>现在需要你对于给定的线路，求出从该线路上的站A到站B的最少票价。你能做到吗？<br> <br></p> 

 
 # 输入格式 
<p>
输入格式 Input Format  <br>　　输入文件的第一行为6个整数, L1, L2, L3, C1, C2, C3 (1 <= L1 < L2 < L3 <= 10^9, 1 <= C1 < C2 < C3  <= 10^9) ,这些整数由空格隔开.第二行为火车站的数量N (2 <= N <= 10000).第三行为两个不同的整数A、B,由空格隔开。接下来的 N-1 行包含从第一站到其他站之间的距离.这些距离按照增长的顺序被设置为不同的正整数。相邻两站之间的距离不超过L3. 两个给定火车站之间行程花费的最大值不超过10^9，而且任意两站之间距离不超过 10^9。<br> <br></p> 

 
 # 输出格式 
<p>
输出格式 Output Format  <br>　　输出文件中只有一个数字,表示从A到B要花费的最小值. <br></p> 
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
<tr><td>样例输入 Sample Input   
3 6 8 20 30 40
7
2 6
3
7
8
13
15
23
 
</td><td>样例输出 Sample Output   
70
 </td></tr></table>
