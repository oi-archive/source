# 

 
 # 题目背景 
LYG&nbsp;NOIP&nbsp;2011&nbsp;模拟赛&nbsp;2试&nbsp;T2 

 
 # 题目描述 
曹操钻研古书的时候，深深着迷于伏羲的二进制思想。在这个基础上，他居然早于后世两千年发明了二进制中的与（and），或（or），异或（xor）运算！但很快曹操就被自己提出的一个问题难住了。<BR>现在曹操的手下有&nbsp;N&nbsp;个士兵，每个士兵有一个战斗力&nbsp;A，第&nbsp;i个士兵的战斗力是Ai。每对士兵之间有一个和谐度。按照曹操的想法，每对士兵的和谐度，是这对士兵的战斗力的and，or，xor值的和。而曹操军队的总战斗力是每对士兵之间的和谐度之和。无奈曹操的士兵太多了，曹操无法知道他的军队战斗力的总和。你做为曹操的谋士，被迫要求计算这个无聊的数字。<BR><BR> 

 
 # 输入格式 
输入有若干行，第一行只有一个数N（1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;1000000），代表曹操的士兵数。<BR>第&nbsp;2...N+1&nbsp;行，每行有一个数Ai（0&nbsp;&lt;=&nbsp;Ai&nbsp;&lt;=&nbsp;30000）,代表该士兵的战斗力。<BR> 

 
 # 输出格式 
一个整数表示军队总战斗力。答案保证在2^63&nbsp;-&nbsp;1以内。 

 
 # 提示 
输入数据较大，C++&nbsp;选手请使用&nbsp;scanf/fscanf&nbsp;避免&nbsp;TLE。<BR><BR>对于50%的数据，1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;10000<BR>对于100%的数据，1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;1000000<BR><BR>//样例解释<BR>有3个士兵战斗力分别为1，2，3。<BR>有3对士兵，分别为（1，2），和谐度是(1&nbsp;and&nbsp;2)&nbsp;+&nbsp;(1&nbsp;or&nbsp;2)&nbsp;+&nbsp;(1&nbsp;xor&nbsp;2)&nbsp;=&nbsp;6；<BR>(1，3)，和谐度为(1&nbsp;and&nbsp;3)&nbsp;+&nbsp;(1&nbsp;or&nbsp;3)&nbsp;+&nbsp;(1&nbsp;xor&nbsp;3)&nbsp;=&nbsp;6；<BR>(2，3)，和谐度为(2&nbsp;and&nbsp;3)&nbsp;+&nbsp;(2&nbsp;or&nbsp;3)&nbsp;+&nbsp;(2&nbsp;xor&nbsp;3)&nbsp;=&nbsp;6；<BR>故军队总战斗力为&nbsp;6+6+6=18。<BR>By&nbsp;FB&nbsp;and&nbsp;TB.&nbsp; 
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
1
2
3
</td><td>18
</td></tr></table>
