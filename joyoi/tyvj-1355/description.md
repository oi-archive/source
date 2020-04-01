# 

 
 # 题目背景 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;小B喜欢在蓝心网玩游戏,一天他玩到了这个游戏:&nbsp;http://boolean93.blog.163.com/blog/static/164414291201010445255950/&nbsp;，他感觉非常好玩....于是他就YY出了一个类似的简易模型....<BR>&nbsp;&nbsp;游戏规则：每次点击一个小朋友，他和他相邻的两个小朋友都会改变状态（蹲下的变成了站起来的，站起来的变成了蹲下的）&lt;这里注意&gt;：如果是1号小朋友，那么只有2号和1号小朋友改变状态。反之，如果是N号小朋友，那么只有N号小朋友和N-1号小朋友改变状态。<BR><BR> 

 
 # 题目描述 
我们将这个抽象成如下图所示的1*N的图.对于一个单元格,黑色表示小朋友是站起来的,反之,蹲下的小朋友是是白色的.Source表示初始状态,Target表示目标状态.<BR><img src="/source/joyoi/tyvj-1355/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTM1NS9odHRwOi8vd3d3LnR5dmouY246ODA4MC9Qcm9ibGVtSW1nL3AxMzU1LTEuYm1w.bmp" border=0 align=middle><BR><img src="/source/joyoi/tyvj-1355/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTM1NS9odHRwOi8vd3d3LnR5dmouY246ODA4MC9Qcm9ibGVtSW1nL3AxMzU1LTIuYm1w.bmp" border=0 align=middle><BR>&nbsp;<BR>&nbsp;&nbsp;&nbsp;现在小B有点偷懒,希望作为神牛的你帮小B算出初始状态到目标状态的最少点击数.<BR><BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第一行为N表示小朋友的个数.<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第二行是初始状态,有N个数,每个数不是0就是1.(0表示小朋友是蹲下的,1表示小朋友是站起来的)<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第三行的结构跟第二行类似,表示目标状态.<BR><BR> 

 
 # 输出格式 
一个数X,表示初始状态到目标状态的最少点击数。<BR>如果无法到达目标,则请输出"Boring"<BR><BR> 

 
 # 提示 
[数据规模]<BR>&nbsp;&nbsp;对于100%的数据，N&lt;=10<BR><BR> 
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
<tr><td>9
0 1 0 0 0 1 0 0 0 
1 0 1 0 1 0 1 0 0

</td><td>2
</td></tr></table>
