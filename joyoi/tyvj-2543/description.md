# 

 
 # 题目描述 
<p>
<br>农夫JOHN准备把他的 N（1 <= N <= 10,000）头牛排队以便于行动。因为脾气大<br>的牛有可能会捣乱，JOHN想把牛按脾气的大小排序。每一头牛的脾气都是一个<br>在1到100，000之间的整数并且没有两头牛的脾气值相同。在排序过程中，JOHN<br>可以交换任意两头牛的位置。因为脾气大的牛不好移动，JOHN需要X+Y秒来交<br>换脾气值为X和Y的两头牛。<br><br>请帮JOHN计算把所有牛排好序的最短时间。<br><br></p> 

 
 # 输入格式 
<p>
第1行： 一个数， N。<br>第2~N+1行： 每行一个数，第i+1行是第i头牛的脾气值。<br><br></p> 

 
 # 输出格式 
<p>
第1行： 一个数，把所有牛排好序的最短时间。<br><br></p> 
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
<tr><td>
3
2
3
1

输入解释：

队列里有三头牛，脾气分别为 2，3， 1。
</td><td>
7

输出解释：
2 3 1 : 初始序列
2 1 3 : 交换脾气为3和1的牛(时间=1+3=4). 
1 2 3 : 交换脾气为1和2的牛(时间=2+1=3). </td></tr></table>
