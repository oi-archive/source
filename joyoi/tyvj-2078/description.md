# 

 
 # 题目背景 
NOIp2012考后欢乐赛第二题 

 
 # 题目描述 
　　新的服务器系统已经建好了，大家期待已久的Tyvj却只开启了一部分功能，因为数据流量实在是太大了，Admin不得不将数据进行分流，可是Admin又忙着去测试新的防御系统，所以Admin把对数据进行分流这项光荣伟大的使命交给你了。<br>　　当然，对数据分流的程序不属于NOIp的范围，所以Admin已经帮你写好了，可是Admin告诉你，他测试了N种分流方式都不能将数据流均分给每个服务器，你要做的是写一份程序来判断在使得分流效率最大的情况下到底需要分配给几台服务器才能恰好均分。<br>　　这里的分流效率最大是指：在最小可能的数据量下，分成的流的个数与每条流上的数据量之和最小，且每个流上的数据量尽量小(不得小于流的个数)。 

 
 # 输入格式 
第一行为一个正整数N，表示Admin已经测试过N次分流方案。<br>第二行到第&nbsp;N+1&nbsp;行，每行两个整数，分别是分成的流的个数Si和多余的不能均分的数据个数Ri. 

 
 # 输出格式 
输出共一行。<br>如果Admin口误，输出"No"(不含引号)和先发生冲突的方案的编号，空格隔开。<br>否则输出"Yes"(不含引号)和使分流效率最大需要的服务器的个数，空格隔开。 

 
 # 提示 
样例解释：<br>第一组：最小可能的数据量为16，分成的流的个数与每条流上的数据量之和可能为8,10,17。<br>第二组：第二个方案和第一个方案冲突。<br><br>对于100%的数据，1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;10<br>对于100%的数据，0&nbsp;&lt;=&nbsp;Ri&nbsp;&lt;&nbsp;Si&nbsp;&lt;=&nbsp;1000，保证"最小可能的数据量"在有符号64位整型存储范围内<br>提示：Tyvj的评测是在Windows平台下，C语言选手对64位整型输出请使用%I64dtjz 
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
<tr><td>[Sample 1]
3
3 1
5 1
7 2

[Sample 2]
3
2 1
2 0
3 1
</td><td>[Sample 1]
Yes 4

[Sample 2]
No 2</td></tr></table>
