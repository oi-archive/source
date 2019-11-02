# 

 
 # 题目背景 
清北学堂杯NOIP模拟赛第三道<BR> 

 
 # 题目描述 
某高性能计算集群（HPC&nbsp;cluster）采用的检修机制与众不同。假定该集群不支持多台计算机同时进行检修而，故同一时刻只有单个计算机处于被检修。初始状态下，每台计算机都由称作优先级数的一个整数指定优先级，该数值越小优先级越高；若优先级数相等，则任务名ASCII&nbsp;字典顺序低者优先。此后，我们总是在检修优先级数最小的计算机；每台计算机检修完毕，再选取优先级数最小下一台计算机。不过，这里的计算机在检修完毕之后通常并不立即退出，而是将优先级数加倍（加倍计算所需的时间可以忽略）并准备检修；只有在优先级数不小于2^32&nbsp;时，才真正退出。<BR>你的任务是，根据初始优先级设置，按照上述调度原则，预测一批计算机的检修序列。<BR> 

 
 # 输入格式 
第一行为以空格分隔的两个整数n&nbsp;和m，n&nbsp;为初始时的计算机总数，m&nbsp;为预测检修序列的长度。<BR>以下n&nbsp;行分别包含一个整数和一个由不超过8个小写字母和数字组成的字符串。前者为计算机的初始优先级数，后者为计算机名称。数字和字符串之间以空格分隔。<BR> 

 
 # 输出格式 
最多m&nbsp;行，各含一个字符串。按执行次序分别给出检修序列中前m台计算机的名称，若检修序列少于m，那么输出全部检修完毕前的所有计算机即可。 

 
 # 提示 
60%&nbsp;数据&nbsp;n&lt;=500&nbsp;m&lt;=1000<BR>100%&nbsp;数据&nbsp;n&lt;=&nbsp;50000&nbsp;m&lt;=&nbsp;500000<BR>时间限制:1s 
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
<tr><td>3 3
1 hello
2 world
10 test</td><td>hello
hello
world</td></tr></table>
