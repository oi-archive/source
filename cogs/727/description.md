# 题目描述


<h4>
<span style="font-family:&#39;Microsoft YaHei&#39;;">【问题描述】</span> 
</h4>
<span style="font-family:&#39;Microsoft YaHei&#39;;">W 教授正在为国家航天中心计划一系列的太空飞行。每次太空飞行可进行一系列商业性实验而获取利润。现已确定了一个可供选择的实验集合</span><em><span style="font-family:&#39;Microsoft YaHei&#39;;">E</span></em><span style="font-family:&#39;Microsoft YaHei&#39;;">={</span><em><span style="font-family:&#39;Microsoft YaHei&#39;;">E</span></em><sub><span style="font-family:&#39;Microsoft YaHei&#39;;">1</span></sub><span style="font-family:&#39;Microsoft YaHei&#39;;">,</span><em><span style="font-family:&#39;Microsoft YaHei&#39;;">E</span></em><sub><span style="font-family:&#39;Microsoft YaHei&#39;;">2</span></sub><span style="font-family:&#39;Microsoft YaHei&#39;;">,…,</span><em><span style="font-family:&#39;Microsoft YaHei&#39;;">E</span></em><sub><em><span style="font-family:&#39;Microsoft YaHei&#39;;">m</span></em></sub><span style="font-family:&#39;Microsoft YaHei&#39;;">}，和进行这些实验需要使用的全部仪器的集合</span><em><span style="font-family:&#39;Microsoft YaHei&#39;;">I</span></em><span style="font-family:&#39;Microsoft YaHei&#39;;">={ </span><em><span style="font-family:&#39;Microsoft YaHei&#39;;">I</span></em><sub><span style="font-family:&#39;Microsoft YaHei&#39;;">1</span></sub><span style="font-family:&#39;Microsoft YaHei&#39;;">, </span><em><span style="font-family:&#39;Microsoft YaHei&#39;;">I</span></em><sub><span style="font-family:&#39;Microsoft YaHei&#39;;">2</span></sub><span style="font-family:&#39;Microsoft YaHei&#39;;">,…,</span><em><span style="font-family:&#39;Microsoft YaHei&#39;;">I</span></em><sub><em><span style="font-family:&#39;Microsoft YaHei&#39;;">n </span></em></sub><span style="font-family:&#39;Microsoft YaHei&#39;;">}。实验</span><em><span style="font-family:&#39;Microsoft YaHei&#39;;">E</span></em><em><span style="font-family:&#39;Microsoft YaHei&#39;;">j </span></em><span style="font-family:&#39;Microsoft YaHei&#39;;">需要用到的仪器是</span><em><span style="font-family:&#39;Microsoft YaHei&#39;;">I</span></em><span style="font-family:&#39;Microsoft YaHei&#39;;">的子集</span><em><span style="font-family:&#39;Microsoft YaHei&#39;;">R</span></em><sub><em><span style="font-family:&#39;Microsoft YaHei&#39;;">j</span></em></sub><span style="font-family:&#39;Microsoft YaHei&#39;;">∈</span><em><span style="font-family:&#39;Microsoft YaHei&#39;;">I</span></em><span style="font-family:&#39;Microsoft YaHei&#39;;">。配置仪器</span><em><span style="font-family:&#39;Microsoft YaHei&#39;;">I</span></em><sub><em><span style="font-family:&#39;Microsoft YaHei&#39;;">k </span></em></sub><span style="font-family:&#39;Microsoft YaHei&#39;;">的费用为</span><em><span style="font-family:&#39;Microsoft YaHei&#39;;">c</span></em><sub><em><span style="font-family:&#39;Microsoft YaHei&#39;;">k </span></em></sub><span style="font-family:&#39;Microsoft YaHei&#39;;">美元。实验</span><em><span style="font-family:&#39;Microsoft YaHei&#39;;">E</span></em><sub><em><span style="font-family:&#39;Microsoft YaHei&#39;;">j </span></em></sub><span style="font-family:&#39;Microsoft YaHei&#39;;">的赞助商已同意为该实验结果支付</span><em><span style="font-family:&#39;Microsoft YaHei&#39;;">p</span></em><sub><em><span style="font-family:&#39;Microsoft YaHei&#39;;">j </span></em></sub><span style="font-family:&#39;Microsoft YaHei&#39;;">美元。W教授的任务是找出一个有效算法，确定在一次太空飞行中要进行哪些实验并因此而配置哪些仪器才能使太空飞行的净收益最大。这里净收益是指进行实验所获得的全部收入与配置仪器的全部费用的差额。</span> 
<h4>
<span style="font-family:&#39;Microsoft YaHei&#39;;">【编程任务】</span> 
</h4>
<span style="font-family:&#39;Microsoft YaHei&#39;;">对于给定的实验和仪器配置情况，编程找出净收益最大的试验计划。</span> 
<h4>
<span style="font-family:&#39;Microsoft YaHei&#39;;">【数据输入】</span> 
</h4>
<span style="font-family:&#39;Microsoft YaHei&#39;;">第1行有2个正整数m和n(m,n &lt;= 100)。m是实验数，n是仪器数。接下来的m行，每行是一个实验的有关数据。第一个数赞助商同意支付该实验的费用；接着是该实验需要用到的若干仪器的编号。最后一行的n个数是配置每个仪器的费用。</span> 
<h4>
<span style="font-family:&#39;Microsoft YaHei&#39;;">【结果输出】</span> 
</h4>
<span style="font-family:&#39;Microsoft YaHei&#39;;">第1行是实验编号；第2行是仪器编号；最后一行是净收益。</span> 
<h4>
<span style="font-family:&#39;Microsoft YaHei&#39;;">【输入文件示例】shuttle.in</span> 
</h4>
<pre>2 3
10 1 2
25 2 3
5 6 7</pre>
<h4>
<span style="font-family:&#39;Microsoft YaHei&#39;;">【输出文件示例】shuttle.out</span> 
</h4>
<pre>1 2
1 2 3
17</pre>
