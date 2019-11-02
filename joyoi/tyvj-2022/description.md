# 

 
 # 题目描述 
Freda有一个队列，最初它是空的。<br>现在Freda接到了一系列指令，每个指令包含一个整数x。<br>如果x&gt;0，表示在队列开头加入一个数x。<br>如果x=0，表示把队列复制一份，并接在现有队列的末尾。<br>如果x=-1，表示弹出队列头部的数，并输出这个数值。<br>但是指令实在是太多了，Freda实在是计算不过来每次要输出什么数值，请你帮帮她吧。<br> 

 
 # 输入格式 
第一行包含一个整数N，表示指令的个数。<br>接下来N行每行一个整数x，描述每条指令。<br> 

 
 # 输出格式 
对于每条x=-1的指令，若此时队列不为空，则输出一个整数，表示从队头弹出的数。否则不进行任何操作。<br> 

 
 # 提示 
对于50%的数据，1&lt;=N&lt;=1000.<br>对于100%的数据，1&lt;=N&lt;=10^6，-1&lt;=x&lt;=10^9。<br> 
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
<tr><td>8
3
4
0
-1
-1
-1
-1
1
</td><td>4
3
4
3
</td></tr></table>
