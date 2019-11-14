# 

 
 # 题目描述 
<p>
[题目描述]<br>　　小A在WOW中是个小术士.作为一名术士,不会单刷副本是相当丢脸的.所谓单刷副本就是单挑BOSS了,这么有荣誉感的事小A怎么会不做呢?于是小A来到了厄运之槌开始了单刷.小A看了看,厄运之槌的地图是一个N*M的矩形（N，M<=100）,上面遍布了小怪和传送门。例如（1表示有小怪，0表示无小怪,大写字母表示传送门,传送门:例如,走到 B 传送门点将传送到另一个 B 传送点（次数无限，但每次进入传送点只传送过去，不会在传送回来）数据保证每个传送门有且仅有相对应的另一个传送门）:<br><br><center><img src="/source/joyoi/tyvj-3321/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzMyMS9wcm9ibGVtc19pbWFnZXMvMjA2MS8xLmJtcA==.bmp"></img></center>　<br>　　而入口在左上方（1，1）,BOSS却躲在右下方（N，M）.小A非常急切的想要完成单刷然后去向其他那些战士啊盗贼啊不会单刷的职业炫耀炫耀,所以呢,小A绝不会在小怪身上浪费时间(当然是绕开他们),并且想通过传送门尽快到达BOSS身边.看啊看,想啊想,还是没找出最快的路。终于,灵机一动,想什么啊,编程呗!<br></p> 

 
 # 输入格式 
<p>
[输入格式]<br>　　第一行2个数据：n m；<br>　　下面n行，每行m个数（入口点和BOSS点无怪和传送门），表示厄运之槌的地图。地图数据之间无空格。每步只能走一格，方向上下左右。左上角为入口点,右下角为出口点.<br></p> 

 
 # 输出格式 
<p>
[输出格式]<br>　　一个整数，表示小A最少需要走多少步。如果小A不能走到目标，则输出“No Solution.”。(结尾有小点哦) <br></p> 

 
 # 提示 
<p>
[数据规模]<br>对60%的数据,n,m <= 20<br>对100%的数据,n,m <= 100<br></p> 
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
<tr><td>[样例输入]
3 4
0000
00A0
A000
</td><td>[样例输出]
4


[样例说明]
路线如图：
 
<br><center><img src="/source/joyoi/tyvj-3321/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzMyMS9wcm9ibGVtc19pbWFnZXMvMjA2MS8yLmJtcA==.bmp"></img></center>　</td></tr></table>
