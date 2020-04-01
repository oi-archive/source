# 

 
 # 题目背景 
TYVJ2月月赛第四道 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;Admin在冬令营比赛的最后一小时没事做，于是便有了本游戏。这个游戏有一个N*M的墙面，我们的目标就是将整个墙面铺满。涂墙的方法有两种，一种是可以每次涂长度为1单位的墙面;第二种是每次可以涂3单位的墙面，第二种还有a1种不同的涂料可以选择。<BR>&nbsp;&nbsp;&nbsp;对于第二种涂得方法，我们有一些限制，通常情况下我们可以竖着连续涂三个单位长度（注意，必须涂满竖着的连续三个）。特殊的，我们可以在第i列和第i+1列（I∈奇数）底部或第i列和第i+1列（I∈偶数）顶部涂一条为"L"形状的。具体参见如下图<BR>&nbsp;<img src="/source/joyoi/tyvj-1278/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTI3OC8mbmJzcDtodHRwOi8vd3d3LnR5dmouY246ODA4MC9wcm9ibGVtaW1nLzEyNzgtMS5qcGc=.jpg" border=0 align=middle><BR>在第i列和第i+1列（I∈奇数）中绿色的样子<BR>在第i列和第i+1列（I∈偶数）中蓝色的样子<BR>求总共涂色的方案数（涂料不同、位置不同、方法不同都将认为是不同的方案）<BR>注意：所有涂色过程中颜色不能掩盖！<BR> 

 
 # 输入格式 
共一行&nbsp;三个正整数n,m,a1，分别表示行数、列数，a1含义上文已经描述。 

 
 # 输出格式 
共一行，输出方案数mod&nbsp;19931012的值 

 
 # 提示 
样例解释<BR>&nbsp;<img src="/source/joyoi/tyvj-1278/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTI3OC8mbmJzcDtodHRwOi8vd3d3LnR5dmouY246ODA4MC9wcm9ibGVtaW1nLzEyNzgtMi5qcGc=.jpg" border=0 align=middle><BR>X表示第一种涂墙的方法，绿色线段表示第二种涂墙的方案<BR><BR><BR>数据范围<BR>第一个测试点数据满足&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;n=1&nbsp;m&lt;=1000&nbsp;a1=1<BR>第二个测试点数据满足&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;n&lt;=1000&nbsp;m=1&nbsp;a1=1<BR>第三个测试点数据满足&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;n&lt;=2&nbsp;m&lt;=1000&nbsp;a1=100<BR>60%的数据满足&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;n&lt;=1000&nbsp;m&lt;=1000&nbsp;a1&lt;=1000<BR>100%的数据满足&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;n&lt;=40000&nbsp;m&lt;=40000&nbsp;a1&lt;=10000<BR>from&nbsp;admin&nbsp;TYVJ月赛出题组 
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
<tr><td>3 2 1</td><td>6
</td></tr></table>
