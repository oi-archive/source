# 

 
 # 题目描述 
SJZEZ和TSYZ正在进行一轮足球联谊赛，根据规则，这轮比赛有两场，一场在SJZEZ的主场进行，一场在TSYZ的主场进行。胜负判断标准如下：<br>1.在两场比赛中进球总数较多的一方赢得比赛。<br>2.如果双方进球总数相同，在对方主场进球更多的一方赢得比赛。<br>3.如果1、2都相同，胜利者将会随机产生=&nbsp;=<br>双方已经进行了一场比赛，作为SJZEZ的队长，忘川沧月童鞋想知道：<br>(1)第二场sjzez最少需要进多少球，才有可能赢得比赛。<br>(2)第二场sjzez进不超过多少个球，tsyz才有可能赢得比赛。<br>已知在一场比赛中，一方的进球数不可能多于30个。<br><br> 

 
 # 输入格式 
第一行一个整数t，表示该测试点中数据的组数。<br>接下来t行，每行一个字符串，描述该组数据中第一场比赛的情况，形式如下：<br>wccy's&nbsp;team&nbsp;played&nbsp;where&nbsp;game,&nbsp;scored&nbsp;x&nbsp;goals,&nbsp;and&nbsp;conceded&nbsp;y&nbsp;goals.<br>其中where是'home'或者'away'中的一个，home表示第一场比赛是在sjzez的主场进行，away表示第一场比赛是在tsyz的主场进行。<br>x，y是整数，分别表示忘川沧月的队伍的进球数，和对方的进球数。<br><br> 

 
 # 输出格式 
输出t行，每行包含两个用空格隔开的整数，分别是两个问题的答案。<br><br> 

 
 # 提示 
对于100%的数据，1&lt;=t&lt;=500，0&lt;=x,y&lt;=30.<br><br> 
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
<tr><td>2
wccy's team played home game, scored 28 goals, and conceded 0 goals.
wccy's team played home game, scored 1 goals, and conceded 1 goals.

</td><td>0 1
1 29

</td></tr></table>
