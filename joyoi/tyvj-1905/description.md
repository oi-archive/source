# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;明明同学最近迷上了侦探漫画《柯南》并沉醉于推理游戏之中，于是他召集了一群同学玩推理游戏。游戏的内容是这样的，明明的同学们先商量好由其中的一个人充当罪犯（在明明不知情的情况下），明明的任务就是找出这个罪犯。接着，明明逐个询问每一个同学，被询问者可能会说：<BR><img src="/source/joyoi/tyvj-1905/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTkwNS8mbmJzcDtodHRwOi8veXQudHl2ai5jbjo4MDgwL1Byb2JsZW1JbWcvUDEwMzkuanBn.jpg" border=0 align=middle><BR>&nbsp;&nbsp;&nbsp;&nbsp;证词中出现的其他话，都不列入逻辑推理的内容。<BR>&nbsp;&nbsp;&nbsp;&nbsp;明明所知道的是，他的同学中有N个人始终说假话，其余的人始终说真。<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在，明明需要你帮助他从他同学的话中推断出谁是真正的凶手，请记住，凶手只有一个！<BR> 

 
 # 输入格式 
&nbsp;&nbsp;输入由若干行组成，第一行有二个整数，M（1≤M≤20）、N（1≤N≤M）和P（1≤P≤100）；<BR>M是参加游戏的明明的同学数，N是其中始终说谎的人数，P是证言的总数。接下来M行，<BR>每行是明明的一个同学的名字（英文字母组成，没有主格，全部大写）。<BR>往后有P行，每行开始是某个同学的名宇，紧跟着一个冒号和一个空格，后面是一句证词，符合前表中所列格式。证词每行不会超过250个字符。<BR>&nbsp;&nbsp;&nbsp;&nbsp;输入中不会出现连续的两个空格，而且每行开头和结尾也没有空格。<BR> 

 
 # 输出格式 
如果你的程序能确定谁是罪犯，则输出他的名字；如果程序判断出不止一个人可能是<BR>罪犯，则输出&nbsp;Cannot&nbsp;Determine；如果程序判断出没有人可能成为罪犯，则输出&nbsp;Impossible。 
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
<tr><td>3 1 5
MIKE
CHARLES
KATE
MIKE: I am guilty.
MIKE: Today is Sunday.
CHARLES: MIKE is guilty．
KATE: I am guilty.
KATE: How are you??

</td><td>MIKE
</td></tr></table>
