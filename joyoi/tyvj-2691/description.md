# 

 
 # 题目描述 
<p>
IOI2002的颁奖典礼将在YONG-IN Hall隆重举行。人们在经历了充满梦幻的世界杯之后变得更加富于情趣。为了使颁奖典礼更具魅力，有人建议在YONG-IN Hall中搭建一个I字型的颁奖台，以此代表信息学Informatics。考虑到比赛的赞助商们可能要在YONG-IN Hall中摆设了许多展示台，他们可能不愿意移动展示台的位置。你作为IOI2002的金牌得主自然地成为了他们求助的对象。

 
 # 输入格式 
<p>
第一行包含两个正整数n, m(1<=n,m<=200)，分别表示YONG-IN Hall的矩形网格区域的行数和列数。以下n行每行包含m个数字，非0即1，每个数字描述一个单位网格，1表示该单位网格存在展示台，0表示该单位网格不存在展示台。

 
 # 输出格式 
<p>
仅包含一个正整数，表示最大的I型颁奖台的面积。如果不存在合法的I型颁奖台，则输出0。

 
 # 提示 
<p>
<img border="0" src="/source/joyoi/tyvj-2691/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjY5MS9wcm9ibGVtc19pbWFnZXMvMzE3Ni8xOTEwXzMuanBn.jpg"> </p> 
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
<tr><td>6 8
1 1 1 1 1 0 0 1
1 0 0 0 0 1 1 1
1 0 0 0 0 0 1 1
1 0 1 0 1 0 1 0
1 0 0 0 0 0 0 1
1 1 0 0 0 1 0 1
</td><td>15