# 

 
 # 题目背景 
Bob家的机子很烂……真的很烂……<BR>以至于看视频或者跑邪恶的暴力程序的时候，由于CPU使用率持续过高而宕机。<BR> 

 
 # 题目描述 
Bob需要一个程序来监视CPU使用率。这是一个很繁琐的过程，为了让问题更加简单，Bob会慢慢列出今天会在用计算机时做什么事。<BR>Bob会干很多事，除了跑暴力程序看视频之外，还会做出去玩玩和用鼠标乱点之类的事，甚至会一脚踢掉电源……这些事有的会让做这件事的这段时间内CPU使用率增加或减少一个值；有的事还会直接让CPU使用率变为一个值。<BR>当然Bob会询问：在之前给出的事件影响下，CPU在某段时间内，使用率最高是多少。有时候Bob还会好奇地询问，在某段时间内CPU曾经的最高使用率是多少。<BR>为了使计算精确，使用率不用百分比而用一个整数表示。<BR>不保证Bob的事件列表出了莫名的问题，使得使用率为负………………<BR> 

 
 # 输入格式 
第一行一个正整数T，表示Bob需要监视CPU的总时间。<BR>然后第二行给出T个数表示在你的监视程序执行之前，Bob干的事让CPU在这段时间内每个时刻的使用率达已经达到了多少。<BR>第三行给出一个数E，表示Bob需要做的事和询问的总数。<BR>接下来E行每行表示给出一个询问或者列出一条事件：<BR>Q&nbsp;X&nbsp;Y:询问从X到Y这段时间内CPU最高使用率<BR>A&nbsp;X&nbsp;Y:询问从X到Y这段时间内之前列出的事件使CPU达到过的最高使用率<BR>P&nbsp;X&nbsp;Y&nbsp;Z:列出一个事件这个事件使得从X到Y这段时间内CPU使用率增加Z<BR>C&nbsp;X&nbsp;Y&nbsp;Z:列出一个事件这个事件使得从X到Y这段时间内CPU使用率变为Z<BR>时间的单位为秒，使用率没有单位。<BR>X和Y均为正整数（X&lt;=Y），Z为一个整数。<BR>从X到Y这段时间包含第X秒和第Y秒。<BR>保证必要运算在有符号32位整数以内。<BR> 

 
 # 输出格式 
对于每个询问，输出一行一个整数回答。<BR> 

 
 # 提示 
数据分布如下：<BR>第1、2个数据保证T和E均小于等于1000<BR>第3、4个数据保证只有Q类询问<BR>第5、6个数据保证只有C类事件<BR>第7、8个数据保证只有P类事件<BR>全部数据保证T和E均小于等于100000<BR>Bob&nbsp;HAN<BR> 
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
<tr><td>10
-62 -83 -9 -70 79 -78 -31 40 -18 -5 
20
A 2 7
A 4 4
Q 4 4
P 2 2 -74
P 7 9 -71
P 7 10 -8
A 10 10
A 5 9
C 1 8 10
Q 6 6
Q 8 10
A 1 7
P 9 9 96
A 5 5
P 8 10 -53
P 6 6 5
A 10 10
A 4 4
Q 1 5
P 4 9 -69
</td><td>79
-70
-70
-5
79
10
10
79
79
-5
10
10
</td></tr></table>