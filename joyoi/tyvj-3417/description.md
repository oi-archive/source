# 

 
 # 题目描述 
<p>
交汇的火力（firepoint.pas\c\cpp）<br><br>【题目描述】<br>　　小D正在玩CS,喜欢思考的他看到无数子弹从他眼前飞过时想到了一个奇怪的问题:这么多子弹在空中飞来飞去,难道它们不会相撞吗?当然这是可能的.小D把两颗子弹轨迹相交的地方叫做”火力汇点”,显然如果让敌人站在火力汇点上那么他将受到更严重的伤害.小D想知道平面上的所有火力汇点以便对敌人造成更重的打击,但是小D数学很差,所以他找到了你,请你帮他计算出平面上所有火力汇点的坐标.小D用直线来描述子弹的轨迹,这种子弹很特别,它发射后会迸裂成两颗并沿相反方向飞行(汗!!那不是打自己),小D数学很差(已知),只会用直线的一般式表示每条直线y=kx+b.<br><br></p> 

 
 # 输入格式 
<p>
　　输入文件firepoint.in:<br>　　n<br>　　k1 b1<br>　　k2 b2<br>　　.<br>　　kn bn<br>　　第一行一个数n,表示直线数量<br>　　接下来n行,每行描述一条直线<br></p> 

 
 # 输出格式 
<p>
　　输出文件firepoint.out一个数,火力汇点的个数<br>　　若交点不存在请输出No Fire Point. (结尾有小点哦)<br></p> 

 
 # 提示 
<p>
【数据规模】<br>　　对所有数据k,b<=maxint      n<=100<br></p> 
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
1 0
-1 2
</td><td>1</td></tr></table>
