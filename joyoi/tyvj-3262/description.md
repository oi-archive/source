# 

 
 # 题目描述 
<p>
东莞中学初中部、东城区第一中学2011年信息学第一次联考（20110305）<br>试题来源：江苏、四校联考<br>======================================================================================================<br>背景（background）<br>　　弹弹堂是一种竞技游戏。玩家通过发射炮弹打中对方来获得胜利。命中率决定着胜利的归属。游戏存在着一些可以计算的公式，这些公式通过发射时的风力和距离来帮助你确定发射的角度和力度，从而命中对方。<br>　　狐仙大人的公会开始收人了。为了保证公会的综合实力，他决定考察新人的能力。<br><br>　　　　　人员选定	　　　　友情互助　　　　　　计数　　　　　　　最佳状态<br>文件名　　select.pas　  　　 　exchange.pas　　　count.pas　　　　　　worry.pas<br>输入文件　select.in　　  　　　exchange.in　　　　count.in　　　　　　worry.in<br>输出文件　select.out　　　　  exchange.out　　　　count.out　　　　　　worry.out<br>时间限制　1s　　　　　　　　1s　　　　　　　　1s　　　　　　　　　2s<br>内存限制　128M　　　　　　128M　　　　　　128M　　　　　　　　128M<br><br>=======================================================================================================<br><br>人员选定（select）<br>描述　Description<br>　　公会活动时总是会有许多人抢着去做一件事。怎样从一群人中选择有限的几个，是一个大问题。选择不当会破坏内部团结，分裂公会。狐仙大人苦思冥想，想出了一个好方法。每次以十个人为单位，依次编号为0—9。每个人随意写出一个数，这些数的乘积的约数个数的个位数字就是被选中的那个人的编号。现在就有一些数，狐仙大人希望你能找出这次被选中的人。<br></p> 

 
 # 输入格式 
<p>
一行：十个人依次给出数num（1 <= num <= 10000）。<br></p> 

 
 # 输出格式 
<p>
一个数字p，表示被选中者的编号。<br></p> 

 
 # 提示 
<p>
======================================================================================================<br>历史测试成绩记录，测试时间：2011年3月5日<br>------------------------------------------------------------------------------------------------------<br>杨宇通　　　250　　AAAAAAAAAA　　　AAWAAAAAAA　　　　??????????　　　　AAWWWWAAAAAAAWW　<br>伍舜豪　　　250　　AAAAAAAAAA　　　AAWAAAAAAA　　　　YYYYYYYYYY　　　　AAWWWWAAAAAAAWW　　　<br>袁嘉豪　　　200　　AAAAAAAAAA　　　??????????	　　　??????????　　　　AAAAAAAAAAAAAAA　　　<br>肖遥　　　　190　　　AAAAAAAAAA　　　WWWWWAWWWA	　　　AWWWWWWWWW　　　　AAWWWWAAAAAAAWW　　　<br>张嘉曦　　　140　　AAAAAAAAAA　　　??????????	　　　AAAATTTTTT　　　　YYYYYYYYYYYYYYY　　　<br>冯灏帆　　　140　　AWTWTAAAWW　　　AAWAAAAAAA	　　　AWWWWWWWWW　　　　???????????????　　　<br>王誉锋　　　120　　AAAAAAAAAA　　　AWWAWWWWWW	　　　??????????　　　　???????????????　　　<br>孔智谦　　　120　　AAAAAAAAAA　　　WWWWWAWWWA	　　　??????????　　　　???????????????　　　<br>麦辉煜　　　110　　AAAAAAAAAA　　　----------	　　　AWWWWWWWWW　　　　???????????????　　　<br>潘熙　　　　70　　　AAATBBBWWB　　　WWWWWAWWWA	　　　AAWWTTTTTT　　　　???????????????　　　<br>林雪晴　　　50　　WWWWWWWWAW　　　??????????	　　　AAAATTTTTT　　　　???????????????　　　<br>钟嘉声　　　20　　WWWBBBBWWW　　　WWWWWAWWWA	　　　??????????　　　　???????????????　　　<br>======================================================================================================<br></p> 
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
<tr><td>1 2 6 1 3 1 1 1 1 1
</td><td>9</td></tr></table>
