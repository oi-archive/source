# 

 
 # 题目描述 
<p>
时区（zones.pas\c\cpp）<br><br>【题目描述】<br>　　你是一个长年往来于世界各地做生意的忙碌的商人。每天你会收到各个时区的客户发来的消息，恰好每个时区一个。糟糕的是，这些消息的末尾只注明该消息发送时客户所在的时区的时间，而不是你这里的时间。请根据这些消息收到的先后顺序，判断哪个消息属于哪个时区。重要提示：本题输入的数据保证消息和时区的对应关系可唯一确定。假定一天有n个小事，共有恰好n个时区。</p> 

 
 # 输入格式 
<p>
　　输入文件zones.in第一行包括时区的数目n(5≤n≤60),这也是你在一天收到的邮件数目。<br>　　接下来的n行每行包括一个时间hhmm(前两个数字是小时h(0≤≤n-1),后两数字是分钟m（0≤m≤59）。这n行按时间顺序排列。<br></p> 

 
 # 输出格式 
<p>
　　输出文件zones.out一行n个数，分别为这几个邮件发信人所在的时区，顺序与输入相同。</p> 
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
<tr><td>5
0017
0250
0400
0201
0002
</td><td>3 1 0 2 4</td></tr></table>
