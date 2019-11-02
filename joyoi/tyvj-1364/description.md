# 

 
 # 题目背景 
&nbsp;&nbsp;&nbsp;&nbsp;有一个程序……<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;这个程序用于处理一些简单的运算和分析，当然，这个并不是要你写这个程序，而是请你写这个程序的子程序。<BR>&nbsp;&nbsp;&nbsp;&nbsp;这个程序的空间为n，也就是说，他有n个可用单元（开始均空闲，从1开始）。<BR>&nbsp;&nbsp;&nbsp;&nbsp;我们来描述一下这个程序需要接受的指令：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;N&nbsp;[t]&nbsp;[important]&nbsp;：(New&nbsp;Work)意思是这个程序分配一个任务，这个任务需要连续的t个空间单元，这个程序的重要性为important。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;对于这个指令，你需要找到一个最小x，使得所有单元f(x&lt;=f&lt;=x+t-1)都为空闲或分配任务的重要性没有这个任务那么重要(小于)。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;找到后，你把这些单元f均分配这个任务且返回x，若找不到这样的任务，返回wrong。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;D&nbsp;[s]&nbsp;[e]&nbsp;：(DelWork)意思是强制结束所有单元f(s&lt;=f&lt;=e)工作（若单元f不是空闲），你只需把他们变为空闲状态就可以了（无需干涉[正在执行[它们正在执行的任务]的空间单元]）。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;结束后，你要返回这当中正在执行的最重要的任务的重要度，如果全部这些单元均为空闲，那么返回wrong。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A&nbsp;[t]&nbsp;：(Ask)意思是要你返回单元t正在执行的任务的重要性，若单元t为空闲，返回wrong。<BR>&nbsp;&nbsp;&nbsp;&nbsp;这里所谓的返回，其实你只要输出就行了。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行一个整数n，表示总共的单元数量。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第二行一个整数m，表示接下来有m个指令。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来m行，每行可能为：<BR>&nbsp;&nbsp;&nbsp;&nbsp;N&nbsp;t&nbsp;i&nbsp;&nbsp;&nbsp;&nbsp;(&nbsp;1&nbsp;&lt;=&nbsp;t,i&nbsp;&lt;=&nbsp;maxlongint&nbsp;)<BR>&nbsp;&nbsp;&nbsp;&nbsp;D&nbsp;s&nbsp;e&nbsp;&nbsp;&nbsp;&nbsp;(&nbsp;1&nbsp;&lt;=&nbsp;s&nbsp;&lt;=&nbsp;e&nbsp;&lt;=&nbsp;n&nbsp;)<BR>&nbsp;&nbsp;&nbsp;&nbsp;A&nbsp;t&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(&nbsp;1&nbsp;&lt;=&nbsp;t&nbsp;&lt;=&nbsp;n&nbsp;)<BR>&nbsp;&nbsp;&nbsp;&nbsp;意义由题目所示。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;对于每一个指令，输出题目描述所示的东西。<BR> 

 
 # 提示 
99%的分数：1&nbsp;&lt;=&nbsp;n&nbsp;,&nbsp;m&nbsp;&lt;=&nbsp;100<BR>1%的分数：&nbsp;1&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;10000&nbsp;,&nbsp;1&nbsp;&lt;=&nbsp;m&nbsp;&lt;=&nbsp;10000<BR> 
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
<tr><td>2
6
N 2 1
N 2 2
D 1 1
A 1
A 2
N 2 1
</td><td>1
1
2
wrong
2
wrong
</td></tr></table>
