# 

 
 # 题目描述 
<p>
Henry拣钱（money.pas\c\cpp）<br><br>【背景描述】<br>　　最近,Henry由于失恋(被某大牛甩掉！)心情很是郁闷.所以,他去了大牛家,寻求Michael大牛的帮助,让他尽快从失恋的痛苦中解脱出来.Michael大牛知道Henry是很爱钱的,所以他是费尽脑水,绞尽脑汁想出了一个有趣的游戏,帮助Henry.....<br><br>【题目描述】<br>　　Michael感觉自己简直是个天才(我们从不这么认为),就把这个游戏取名为:Henry拣钱.为了帮助更多的人采用这种方法早日脱离失恋之苦,Michael特地选在这次DT比赛中把游戏介绍给大家...(大家鼓掌!!!)<br>　　其实,这个游戏相当垃圾,目的就是为了满足Henry这种具有强烈好钱的心理的人.游戏是这样的:Michael首先找到了一块方形的土地,面积为m*n(米^2).然后他将土地划分为一平方米大小的方形小格.Michael在每个格子下都埋有钱(用非负数s表示,表示人民币的价值为s)和炸弹(用负数s表示,表示Henry挖出该方格下的东西会花掉s的钱去看病，医炸弹炸伤的伤口)...游戏的要求就是让Henry从一侧的中间列出发,按照下图的5种方式前进（前进最大宽度为5）,不能越出方格.他每到一个格子,必定要取走其下相应的东西.直到到达土地的另一侧,游戏结束.不用说也知道,Henry肯定想得到最多的人民币.所以他偷窥了,Michael埋钱的全过程,绘成了一张距阵图.由于他自己手动找会很麻烦,于是他就找到了学习编程的你.请给帮他找出,最大人民币价值.<br><br>　　拣钱路线规则(只有5个方向，如下图)：<br><br><center><img src="/source/joyoi/tyvj-3415/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzQxNS9wcm9ibGVtc19pbWFnZXMvMjIxMS8xLmpwZw==.jpg"></img></center><br>　　H为Henry的出发点，每组数据的出发点都是最后一行的中间位置！<br>　　(前方5个格子为当前可以到达的)<br></p> 

 
 # 输入格式 
<p>
　　输入文件money.in第一行为m n.(n为奇数)，入口点在最后一行的中间<br>　　接下来为m*n的数字距阵.<br>　　共有m行,每行n个数字.数字间用空格隔开.代表该格子下是钱或炸弹.<br>　　为了方便Henry清算,数字全是整数.<br></p> 

 
 # 输出格式 
<p>
　　输出文件money.out包含一个数,为你所找出的最大人民币价值.</p> 

 
 # 提示 
<p>
【数据范围】<br>　　N and M<=200.<br>　　结果都在longint范围内<br></p> 
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
<tr><td>6 7
16 4 3 12 6 0 3
4 -5 6 7 0 0 2
6 0 -1 -2 3 6 8
5 3 4 0 0 -2 7
-1 7 4 0 7 -5 6
0 -1 3 4 12 4 2
</td><td>
51</td></tr></table>
