# 

 
 # 题目描述 
<p>太空飞行计划问题（shut.cpp/c/pas）<br />
<br />
【问题描述】<br />
<br />
　　W&nbsp;教授正在为国家航天中心计划一系列的太空飞行。每次太空飞行可进行一系列商业性实验而获取利润。现已确定了一个可供选择的实验集合E={E1，E2，&hellip;，Em}，和进行这些实验需要使用的全部仪器的集合I={I1，I2，&hellip;In}。实验Ej需要用到的仪器是I的子集Rj&isin;I。配置仪器Ik的费用为才Ck美元。实验Ej的赞助商已同意为该实验结果支付Pj美元。W教授的任务是找出一个有效算法，确定在一次太空飞行中要进行哪些实验并因此而配置哪些仪器才能使太空飞行的净收益最大。这里净收益是指进行实验所获得的全部收入与配置仪器的全部费用的差额。<br />
【编程任务】<br />
　　对于给定的实验和仪器配置情况，编程找出净收益最大的试验计划。</p> 

 
 # 输入格式 
<p>由文件shut.in提供输入数据。<br />
　　文件第1行有2&nbsp;个正整数m和n。m是实验数，n是仪器数。接下来的m&nbsp;行，每行是一个实验的有关数据。第一个数赞助商同意支付该实验的费用；接着是该实验需要用到的若干仪器的编号。最后一行的n个数是配置每个仪器的费用。</p> 

 
 # 输出格式 
<p>程序运行结束时，将最佳实验方案输出到文件shut.out&nbsp;中。<br />
　　第1&nbsp;行是实验编号；第2行是仪器编号；最后一行是净收益。</p> 

 
 # 提示 
<p>m,n&lt;=50</p> 
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
<tr><td>2 3
10 1 2
25 2 3
5 6 7</td><td>1 2
1 2 3
17</td></tr></table>
