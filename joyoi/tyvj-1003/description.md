# 

 
 # 题目背景 
成成第一次模拟赛&nbsp;第二道 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;为了能在下一次跑步比赛中有好的发挥，贝茜在一条山路上开始了她的训练<BR>。贝茜希望能在每次训练中跑得尽可能远，不过她也知道农场中的一条规定：<BR>奶牛独自进山的时间不得超过M秒(1&nbsp;&lt;=&nbsp;M&nbsp;&lt;=&nbsp;10,000,000)。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;整条山路被贝茜划分成T个长度相同的小段(1&nbsp;&lt;=&nbsp;T&nbsp;&lt;=&nbsp;100,000)，并且，<BR>贝茜用S_i表示第i个小段的路况。S_i为u，f，d这3个字母之一，它们分别表示<BR>第i个小段是上坡、平地，或是下坡。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;贝茜要花U秒(1&nbsp;&lt;=&nbsp;U&nbsp;&lt;=&nbsp;100)才能跑完一段上坡路，跑完一段平地的耗时是<BR>F秒(1&nbsp;&lt;=&nbsp;F&nbsp;&lt;=&nbsp;100)，跑完一段下坡路要花D秒(1&nbsp;&lt;=&nbsp;D&nbsp;&lt;=&nbsp;100)。注意，沿山路<BR>原路返回的时候，原本是上坡路的路段变成了下坡路，原本是下坡路的路段变成<BR>了上坡路。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;贝茜想知道，在能按时返回农场的前提下，她最多能在这条山路上跑多远。 

 
 # 输入格式 
输入格式:<BR><BR>*&nbsp;第1行:&nbsp;5个用空格隔开的整数：M，T，U，F，以及D<BR><BR>*&nbsp;第2..T+1行:&nbsp;第i+1行为1个字母S_i，描述了第i段山路的路况<BR> 

 
 # 输出格式 
输出格式:<BR><BR>*&nbsp;第1行:&nbsp;输出1个整数，为贝茜在按时回到农场的前提下，最多能跑到多远 

 
 # 提示 
输入说明:<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;贝茜跑步的最大耗时为13秒（这么短...），她跑步的山路一共被划成5段。<BR>贝茜跑完一段上坡路的耗时为3秒，平地为2秒，下坡路为1秒。山路各段的走向<BR>如下图所示：<BR><BR>&nbsp;&nbsp;_/\_<BR>/<BR><BR>输出说明:<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;贝茜跑完山路的前3段，然后返回，总耗时为3&nbsp;+&nbsp;2&nbsp;+&nbsp;3&nbsp;+&nbsp;1&nbsp;+&nbsp;2&nbsp;+&nbsp;1&nbsp;=&nbsp;12秒，只比她能在外面呆的时限少1秒。如果她跑得更远，就无法按时回到农场。 
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
<tr><td>13 5 3 2 1
u
f
u
d
f</td><td>3
</td></tr></table>
