# 

 
 # 题目描述 
Z城市居住着很多只跳蚤。在Z城市周六生活频道有一个娱乐节目。一只跳蚤将<BR>被请上一个高空钢丝的正中央。钢丝很长，可以看作是无限长。节目主持人会给<BR>该跳蚤发一张卡片。卡片上写有N+1个自然数。其中最后一个是M，而前N个数<BR>都不超过M，卡片上允许有相同的数字。跳蚤每次可以从卡片上任意选择一个自<BR>然数S，然后向左，或向右跳S个单位长度。而他最终的任务是跳到距离他左边<BR>一个单位长度的地方，并捡起位于那里的礼物。<BR>比如当N=2，M=18时，持有卡片(10,&nbsp;15,&nbsp;18)的跳蚤，就可以完成任务：他可以先<BR>向左跳10个单位长度，然后再连向左跳3次，每次15个单位长度，最后再向右连<BR>跳3次，每次18个单位长度。而持有卡片(12,&nbsp;15,&nbsp;18)的跳蚤，则怎么也不可能跳<BR>到距他左边一个单位长度的地方。<BR>当确定N和M后，显然一共有M^N张不同的卡片。现在的问题是，在这所有的卡<BR>片中，有多少张可以完成任务。<BR> 

 
 # 输入格式 
两个整数N和M(N&nbsp;&lt;=&nbsp;15&nbsp;,&nbsp;M&nbsp;&lt;=&nbsp;100000000)。<BR> 

 
 # 输出格式 
可以完成任务的卡片数。<BR> 

 
 # 提示 
这12张卡片分别是：<BR>(1,&nbsp;1,&nbsp;4),&nbsp;(1,&nbsp;2,&nbsp;4),&nbsp;(1,&nbsp;3,&nbsp;4),&nbsp;(1,&nbsp;4,&nbsp;4),&nbsp;(2,&nbsp;1,&nbsp;4),&nbsp;(2,&nbsp;3,&nbsp;4),<BR>(3,&nbsp;1,&nbsp;4),&nbsp;(3,&nbsp;2,&nbsp;4),&nbsp;(3,&nbsp;3,&nbsp;4),&nbsp;(3,&nbsp;4,&nbsp;4),&nbsp;(4,&nbsp;1,&nbsp;4),&nbsp;(4,&nbsp;3,&nbsp;4)<BR><BR>注意：答案保证不会超过int64(long&nbsp;long)的范围 
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
<tr><td>2 4
</td><td>12
</td></tr></table>
