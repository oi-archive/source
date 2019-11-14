# 

 
 # 题目描述 
小Q的妈妈是一个出纳，经常需要做一些统计报表的工作。今天是妈妈的生日，小Q希望可以帮妈妈分担一些工作，作为她的生日礼物之一。<BR>	经过仔细观察，小Q发现统计一张报表实际上是维护一个非负整数数列，并且进行一些查询操作。<BR>在最开始的时候，有一个长度为N的整数序列，并且有以下三种操作：<BR>		<BR>INSERT&nbsp;i&nbsp;k	在原数列的第i个元素后面添加一个新元素k；如果原数列的第i个元素已经添加了若干元素，则添加在这些元素的最后（见下面的例子）<BR>MIN_GAP	查询相邻两个元素的之间差值（绝对值）的最小值<BR>MIN_SORT_GAP	查询所有元素中最接近的两个元素的差值（绝对值）<BR>	<BR>	例如一开始的序列为<BR>5	3	1<BR><BR>执行操作INSERT&nbsp;2&nbsp;&nbsp;9将得到：<BR>5	3	9	1<BR>此时MIN_GAP为2，MIN_SORT_GAP为2。<BR><BR>再执行操作INSERT&nbsp;2&nbsp;&nbsp;6将得到：<BR>5	3	9	6	1<BR><BR>注意这个时候原序列的第2个元素后面已经添加了一个9，此时添加的6应加在9的后面。这个时候MIN_GAP为2，MIN_SORT_GAP为1。<BR>	于是小Q写了一个程序，使得程序可以自动完成这些操作，但是他发现对于一些大的报表他的程序运行得很慢，你能帮助他改进程序么？<BR> 

 
 # 输入格式 
第一行包含两个整数N，M，分别表示原数列的长度以及操作的次数。<BR>	第二行为N个整数，为初始序列。<BR>	接下来的M行每行一个操作，即“INSERT&nbsp;i&nbsp;k”，“MIN_GAP”，“MIN_SORT_GAP”中的一种（无多余空格或者空行）。<BR> 

 
 # 输出格式 
对于每一个“MIN_GAP”和“MIN_SORT_GAP”命令，输出一行答案即可。 

 
 # 提示 
对于30%的数据，N&nbsp;≤&nbsp;1000&nbsp;,&nbsp;M&nbsp;≤&nbsp;5000<BR>对于100%的数据，N&nbsp;,&nbsp;M&nbsp;≤500000<BR>对于所有的数据，序列内的整数不超过5*10^8。<BR> 
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
<tr><td>3 5
5 3 1
INSERT 2 9
MIN_SORT_GAP
INSERT 2 6
MIN_GAP
MIN_SORT_GAP
</td><td>2
2
1
</td></tr></table>
