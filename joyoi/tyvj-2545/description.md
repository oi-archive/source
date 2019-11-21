# 

 
 # 题目描述 
<p>
每天,农夫 John 的N(1 <= N <= 50,000)头牛总是按同一序列排队. 有一天, John<br>决定让一些牛们玩一场飞盘比赛. 他准备找一群在对列中为置连续的牛来进行比赛.<br>但是为了避免水平悬殊,牛的身高不应该相差太大.<br><br>John 准备了Q (1 <= Q <= 180,000) 个可能的牛的选择和所有牛的身高 (1 <=<br>身高 <= 1,000,000). 他想知道每一组里面最高和最低的牛的身高差别.<br><br>注意: 在最大数据上, 输入和输出将占用大部分运行时间.<br><br></p> 

 
 # 输入格式 
<p>
* 第一行: N 和 Q.<br><br>* 第2..N+1行: 第i+1行是第i头牛的身高.<br><br>* 第N+2..N+Q+1行: 两个整数, A 和 B  (1 <= A <= B <= N), 表示从A到B的<br>所有牛.<br><br><br></p> 

 
 # 输出格式 
<p>
*第1..Q行: 所有询问的回答 (最高和最低的牛的身高差), 每行一个.<br></p> 
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
1
7
3
4
2
5
1 5
4 6
2 2

</td><td>6
3
0</td></tr></table>
