# 

 
 # 题目背景 
（在你的帮助下，Freda破解了Rainbow的密码）<br>　Rainbow：其实我的城堡还有第P+1扇门lala~<br>　Freda：Orz！！！<br>　Rainbow：第P+1扇门只有我能打开~<br>　Freda：是不是里面有什么奇奇怪怪的东西嘞？<br>　Rainbow：Of&nbsp;course！lala~ 

 
 # 题目描述 
Rainbow打开了它城堡的第P+1扇门，呈现在Freda眼前的是一架小型飞机和…………一个小型飞行场地！Rainbow向Freda介绍说，这是它自制的第一架飞机，不过还处在试飞阶段，所以只能进行室内飞行。还有一个BUG是，这架飞机只能在Rainbow城堡的灯光下飞行，否则飞机就会坠毁&gt;_&lt;。<br>方便起见，我们把这个小型飞行场地看做一条直线，将Rainbow的飞机看做一个质点。Rainbow的小型飞行场地配备有N盏灯。如图所示，每盏灯有一个坐标Xi，第i盏灯有一个高度Yi。同时，每盏灯有一个光照范围，显然，每盏灯能够照亮的是一个等腰三角形，顶角的一半是给出的Zi（按照角度制给出）。Freda很好奇，如果Rainbow的飞机从L坐标飞到R坐标且飞行高度不变，那么，Rainbow的飞机能够飞行的最高高度是多少呢？<br><img src="/source/joyoi/tyvj-1976/img/aHR0cDovL2ZpbGVzLmJsb2djbi5jb20vd3AwMi9NMDAvMDYvMzMvd0tnS0MxQmxZMzBBQUFBQUFBWXFja0JadWNFNzcxLmpwZw==.jpg" border=0 align=middle> 

 
 # 输入格式 
第一行三个数N，L，R，其中N为整数，L和R都为实数。表示灯的个数以及Rainbow的飞机飞行范围。<br>接下来N行每行三个实数，第i+1行包括三个实数Xi，Yi，Zi，分别表示第i盏灯的坐标、高度、以及照亮的等腰三角形顶角角度的一半。 

 
 # 输出格式 
一行一个实数，表示飞机能够飞行的最高高度。保留三位小数。&nbsp; 

 
 # 提示 
对于50%的数据，N&lt;=10.<br>对于100%的数据，1&lt;N&lt;=50000，15&lt;=Zi&lt;=75，-1000&lt;=Xi&lt;=1000,&nbsp;0&lt;Yi&lt;=1000，&nbsp;-1000&lt;=L&lt;R&lt;=1000.From&nbsp;-&nbsp;This_poet<br>Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<br>This_poet's&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com 
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
<tr><td>2 3.2 7.3
3.2 4.7 28
7.3 4.2 75</td><td>3.301</td></tr></table>
