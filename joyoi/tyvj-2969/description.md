# 

 
 # 题目描述 
<p>
最近科学家们在研究一个很庞大的原子核家族——“X家族”。他们发现这个家族中的所有原子核都非常相似，只能通过质量来区分它们。质量相差越小，它们之间相互转化的可能性就越大。<br>为了深入研究这个X家族，科学家们设计了一系列的实验。其中，作为一项重要的基础设施，他们设计了一台特别的设备，可以支持以下三种操作指令：<br>1.generate M——如果当前不存在质量为M的核，则生成一个，否则，该操作被忽略。<br>2.remove M——如果当前存在质量为M的核，则把它移除，否则，该操作被忽略。<br>3.query——输出当前存在的所有核中，最小的质量差。例如，如果当前有三种核，分别重1、7、10，那么最小的质量差就是10-7=3。特别地，如果当前不存在两种或以上的核，则输出-1。<br>现在你的任务就是编程模拟这个设备，假定开始时没有任何核。<br></p> 

 
 # 输入格式 
<p>
输入第一行是一个整数N（1 <= N <= 100000），表示总共有多少条操作指令。<br>接下来N行，每行表示一条指令，格式如上所述。其中，M是不大于100000的正整数。<br></p> 

 
 # 输出格式 
<p>
对于每一条query指令，输出一行，包含一个整数，即当前最小的质量差或者-1。</p> 

 
 # 提示 
<p>
对于30%的数据，N <= 100。</p> 
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
<tr><td>12
generate 1
remove 2
generate 1
query
generate 7
query
generate 10
query
generate 5
query
remove 7
query
</td><td>-1
6
3
2
4</td></tr></table>
