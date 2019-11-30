# 

 
 # 题目描述 
<p>&nbsp;&nbsp;&nbsp;旧版的石子合并游戏已经为大家所广知了。最近JSOI小组的成员dwyak与好友BenBen聊天时谈起了一种新的石子合并游戏。<br />
<br />
BenBen最近被这种石子合并游戏所困惑：<br />
有一排石子，共N堆，每堆分别有s1、s2、s3&hellip;&hellip;sN个。每次可以合并相邻的两堆石子si和sj，合并的代价是si&nbsp;+&nbsp;sj，合并以后得到一堆含si&nbsp;+&nbsp;sj个石子的石堆，放在第i堆石子的位置上。此外与传统石子合并游戏不同的是，每次合并石子之前，可以交换任意两堆石子的位置。<br />
<br />
现在，要求你用一定的方法，将N堆石子合并为一堆，使合并总代价最小。<br />
&nbsp;&nbsp;&nbsp;<br />
BenBen将这个游戏讲给了dwyak听，dwyak觉得这个游戏挺有趣，于是拿出来与大家分享。</p> 

 
 # 输入格式 
<p>第一行一个整数N（N&nbsp;&lt;=&nbsp;1&nbsp;000&nbsp;000），表示石堆的数量。<br />
第二行N个整数s1、s2、s3&hellip;&hellip;sN，分别表示每个石堆中石子的个数（si&nbsp;&lt;=&nbsp;1&nbsp;000&nbsp;000）。</p> 

 
 # 输出格式 
<p>&nbsp;一个整数，表示最小合并总代价。</p> 

 
 # 提示 
<p>第一步：交换2和3，并将1和2合并，代价为3。剩下两堆石子3&nbsp;&nbsp;3。<br />
第二步：交换3和3，并将3和3合并，代价为6。剩下一堆石子6。<br />
合并总代价：3&nbsp;+&nbsp;6&nbsp;=&nbsp;9</p> 
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
<tr><td>3
1 3 2</td><td>9</td></tr></table>
