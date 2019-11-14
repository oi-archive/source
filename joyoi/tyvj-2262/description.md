# 

 
 # 题目描述 
<p>
Leopold十分幸运，买彩票中了大奖，得到了一座庄园。庄园中除了Leopold打算居住的主宅之外，还有一些其他的建筑。然后，这座庄园缺少围墙保护，这一点让Loepold很担心。于是，Loepold打算在房子周围建围墙，为了省钱他决定只要围墙能将主宅包围起来就足够了，还有一点就是围墙不能离庄园中的任何一个建筑太近。也就是说，每个建筑都被一个禁止矩形包围，在这个矩形内部不允许有任何围墙。矩形的边平行于x轴和y轴。围墙的每一部分也必须平行于x轴或者y轴。<br>请你帮助Leopold计算包围主宅的围墙的最小长度。<br> <br><img border="0" src="/source/joyoi/tyvj-2262/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjI2Mi9wcm9ibGVtc19pbWFnZXMvMjYzMS8xMzQzLmpwZw==.jpg"><br><br>图1：有主宅（黑色）和其他三个建筑，每个建筑外面灰色的矩行是禁止矩形，粗的黑线表示这种情况下最小的围墙长度。<br><br></p> 

 
 # 输入格式 
<p>
第一行是一个正整数m（1<=m<= 100），表示庄园中建筑的总数。接下来的m行，每行描述了一个建筑对应的禁止矩形，包括4个空格隔开的整数tx，ty，bx和by，(tx，ty)是矩形左上角的坐标，(bx，by)是矩形右下角的坐标。所有的坐标值满足0 <= tx <= bx <= 10000和 0 <= ty <= by <= 10000。第一个禁止矩形是包围主宅的。<br></p> 

 
 # 输出格式 
<p>
一个正整数，即包围主宅的围墙的最小长度。<br><br></p> 

 
 # 提示 
<p>
30%的测试数据中，m <= 10。<br></p> 
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
<tr><td>4
8 4 13 8
2 1 6 7
4 7 9 11
14 7 19 11	</td><td>32</td></tr></table>
