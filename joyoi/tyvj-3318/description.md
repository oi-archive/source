# 

 
 # 题目描述 
<p>
交汇的火力(firepoint)<br>[题目描述]<br>　　小D正在玩CS,喜欢思考的他看到无数子弹从他眼前飞过时想到了一个奇怪的问题:这么多子弹在空中飞来飞去,难道它们不会相撞吗?当然这是可能的.小D把两颗子弹轨迹相交的地方叫做”火力汇点”,显然如果让敌人站在火力汇点上那么他将受到更严重的伤害.小D想知道平面上的所有火力汇点以便对敌人造成更重的打击,但是小D数学很差,所以他找到了你,请你帮他计算出平面上所有火力汇点的坐标.小D用直线来描述子弹的轨迹,这种子弹很特别,它发射后会迸裂成两颗并沿相反方向飞行(汗!!那不是打自己),小D数学很差(已知),只会用直线的一般式表示每条直线y=kx+b.<br><br><center><img src="/source/joyoi/tyvj-3318/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzMxOC9wcm9ibGVtc19pbWFnZXMvMjA1OC8xLmJtcA==.bmp"></img></center>　<br> (平面的CS)<br><br></p> 

 
 # 输入格式 
<p>
[输入格式]<br>n<br>k1 b1<br>k2 b2<br>......<br>kn bn<br><br>　　说明：第一行一个数n,表示直线数量，接下来n行,每行描述一条直线。</p> 

 
 # 输出格式 
<p>
[输出格式]<br>　　一个数,火力汇点的个数。若交点不存在请输出No Fire Point. (结尾有小点哦)<br></p> 

 
 # 提示 
<p>
[数据规模]<br>对所有数据k,b<=maxint ， n <= 100<br><br>数学知识加油站：<br>　　两条直线求交点的公式：<br>　　y=k1x+b1；  <br>　　y=k2x+b2；<br>则交点为：(  (b2-b1) / (k1-k2)　，(k1b2-k2b1) / (k1-k2)  )<br><br>在直线方程y=kx+b，k也称为直线的斜率。</p> 
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
2
1 0
-1 2
</td><td>[样例输出]
    1</td></tr></table>
