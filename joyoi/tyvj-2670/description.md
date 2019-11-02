# 

 
 # 题目描述 
<p style="margin: 0px 0px 0px 2.25pt; padding: 0px; line-height: 38px; color: rgb(68, 68, 68); font-family: 'Microsoft YaHei', 微软雅黑, Tahoma, Helvetica, Arial, sans-serif; font-size: 12px; background-color: rgba(255, 255, 255, 0.65098);">春春幼儿园举办了一年一度的&ldquo;积木大赛&rdquo;。今年比赛的内容是搭建一座宽度为n的大厦，大厦可以看成由n块宽度为1的积木组成，第i块积木的最终高度需要是ℎi。<br />
&nbsp;在搭建开始之前，没有任何积木（可以看成n块高度为&nbsp;0&nbsp;的积木）。接下来每次操作，小朋友们可以选择一段连续区间[L,&nbsp;R]，然后将第L块到第R块之间（含第L块和第R块）所有积木的高度分别增加1。<br />
&nbsp;小M是个聪明的小朋友，她很快想出了建造大厦的最佳策略，使得建造所需的操作次数最少。但她不是一个勤于动手的孩子，所以想请你帮忙实现这个策略，并求出最少的操作次数。</p> 

 
 # 输入格式 
<p>输入包含两行，第一行包含一个整数n，表示大厦的宽度。&nbsp;<br />
第二行包含n个整数，第i个整数为ℎi。</p> 

 
 # 输出格式 
<p>仅一行，即建造所需的最少操作数。</p> 

 
 # 提示 
<p>【样例解释】<br />
&nbsp;其中一种可行的最佳方案，依次选择<br />
&nbsp;&nbsp;[1,5]&nbsp;&nbsp;&nbsp;&nbsp;[1,3]&nbsp;&nbsp;&nbsp;&nbsp;[2,3]&nbsp;&nbsp;&nbsp;&nbsp;[3,3]&nbsp;&nbsp;&nbsp;&nbsp;[5,5]<br />
【数据范围】<br />
&nbsp;对于&nbsp;30%的数据，有1&nbsp;&le;&nbsp;n&nbsp;&le;&nbsp;10；&nbsp;&nbsp;对于&nbsp;70%的数据，有1&nbsp;&le;&nbsp;n&nbsp;&le;&nbsp;1000；<br />
&nbsp;对于&nbsp;100%的数据，有1&nbsp;&le;&nbsp;n&nbsp;&le;&nbsp;100000，0&nbsp;&le;&nbsp;ℎi&nbsp;&le;&nbsp;10000。</p> 
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
<tr><td>5 
2 3 4 1 2 </td><td>5</td></tr></table>
