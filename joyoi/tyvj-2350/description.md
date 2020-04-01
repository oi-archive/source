# 

 
 # 题目描述 
<p>
<br>    在Y城,有n条街道,每条街道由两个路口连接. Y城的交通系统十分特别,任意两个路口都有唯一的路径可以互相到达. 作为Y城的交通局长的小O,决定在这个城市启用一些电子警察来监控这个城市的所有街道和路口.电子警察的设置有2种:<br>1)	设置在某个路口,那么这个路口,所有的被它连接的街道,和所有它连接的街道的另一端的路口将被监控.<br>2)	设置在某条街道的中央,那么这条街道和连接这条街道的两个路口以及这两个路口所连接的其他街道将被监控.<br>     当然,由于经费问题,小O希望设置最少的电子警察来监控所有的街道和路口.<br></p> 

 
 # 输入格式 
<p>
第一行为一个正整数n,表示街道的数目.<br>接下来n行,每行两个数x,y(x<>y,x,y<=100000000),表示连接这条街道的两个路口的编号,不同的路口的编号一定不同.(由于某些原因,Y城的路口编号不一定是1,2…)<br></p> 

 
 # 输出格式 
<p>
只有一个正整数,表示最少需要的电子警察的数目.<br></p> 

 
 # 提示 
p-equiv="Content-Type" content="text/html; charset=gb2312"><title>2732 -- 电子警察</title><STYLE type=text/css>A {TEXT-DECORATION: none} A:hover {COLOR: red; TEXT-DECORATION: underline }</STYLE></head>
<body leftmargin=5 link=blue alink=blue vlink=blue>
<a name=top></a><table width=980 border=1 bordercolor=#FFFFFF style="border-collapse: collapse"><TR><TD align=middle colSpan=5><img border=0 src=images/logo.jpg width=980 height=97></TD></TR><TR vAlign=top align=center bgcolor=#6589D1><TH width=196>Online Judge</TH><TH  width=196>Problem Set</TH><TH width=196>Authors</TH><TH width=197>Online Contests</TH><TH width=197>User</TH></TR><TR vAlign=top align=center bgcolor=#F1F1FD><TD><A href=bbs>Web Board</A><br><A href=./>Home Page</A><br><A href=faq.htm target=_blank>F.A.Qs</A><br>Announcement</TD><TD><form method=get action=gotoproblem><A href=problemlist>Problems</A><br><A href=submitpage>Submit Problem</A><br><A href=status>Status (Online)</A><br><font color=blue>Prob.ID:<input type=text name=pid size=6><input type=Submit value=Go name=pb1></form></TD><TD><form method=GET action=searchuser><a href=registerpage>Register</a><br><a href=modifyuserpage>Update your info</a><br><a href=userlist>Authors ranklist</a><br><input type=text name=user_id size=10><input type=Submit value=Search name=B1></form></TD>
<TD><a href=showcontest?contest_id=1070><font color=red>Current Contest</a><br><a href=pastcontests>Past Contests</a><br><a href=contests>Scheduled Contests</a></td><TD><iframe scrolling=no align=middle border=0 frameborder=0 width=197 height=90 src=login></iframe></td></TR></TABLE><table border=0 width=100% background=images/table_back.jpg><tr><td>
<p align="center"><font color=blue size=5>电子警察</p>
<p align="center">Time Limit:5000MS&nbsp; Memory Limit:65536K<br>
Total Submit:0 Accepted:0
<br><font color=read>Case Time Limit:500MS
</p>
<p align="left"><b><font color="#333399" size="5">Description
</b>
<p>
<br>    在Y城,有n条街道,每条街道由两个路口连接. Y城的交通系统十分特别,任意两个路口都有唯一的路径可以互相到达. 作为Y城的交通局长的小O,决定在这个城市启用一些电子警察来监控这个城市的所有街道和路口.电子警察的设置有2种:<br>1)	设置在某个路口,那么这个路口,所有的被它连接的街道,和所有它连接的街道的另一端的路口将被监控.<br>2)	设置在某条街道的中央,那么这条街道和连接这条街道的两个路口以及这两个路口所连接的其他街道将被监控.<br>     当然,由于经费问题,小O希望设置最少的电子警察来监控所有的街道和路口.<br></p>
<p align="left"><b><font color="#333399" size="5">Input
</b>
<p>
第一行为一个正整数n,表示街道的数目.<br>接下来n行,每行两个数x,y(x<>y,x,y<=100000000),表示连接这条街道的两个路口的编号,不同的路口的编号一定不同.(由于某些原因,Y城的路口编号不一定是1,2…)<br></p>
<p align="left"><b><font color="#333399" size="5">Output
</b>
<p>
只有一个正整数,表示最少需要的电子警察的数目.<br></p>
<p align="left"><b><font color="#333399" size="5">Sample Input
</b>
<p><font face="Times New Roman" size="3"><pre>
7
1 10
10 100
100 1000
1000 10000
10000 100000
100000 1000000
1000000 10000000  
</pre></p>
<p align="left"><b><font color="#333399" size="5">Sample Output
</b>
<p><font face="Times New Roman" size="3"><pre>
3
Hint : 3个电子警察分别设置在编号为10的路口,第4条街道的中央和编号为1000000的路口.
数据范围
30%的数据,n<=1000
100%的数据,n<=200000
</pre></p> 
