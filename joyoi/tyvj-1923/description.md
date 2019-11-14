# 

 
 # 题目描述 
要开运动会了，Freda承担起了制作全校旗帜的工作。旗帜的制作方法是这样的：Freda一共有C种颜色的布条，每种布条都有无数个，你可以认为这些布条的长、宽、厚都相等，只有颜色可能不同。每个旗帜都是由一些布条横向拼接起来的，如图所示，图上所示的是一面红、黄、蓝三种颜色布条拼接的旗帜：<BR><img src="/source/joyoi/tyvj-1923/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTkyMy9odHRwOi8vZmlsZS0wMi5ibG9nY24uY29tL3dwMDEvTTAwLzA4LzY3L3dLZ0tDMUEwWllJQUFBQUFBQUFQTTJ4dVhJbzUyNC5qcGc=.jpg" border=0 align=middle><BR>布条数目不同的旗帜显然是不同的。对于布条数目都为T的两面旗帜，如果存在从左到右第i(0&lt;i&lt;=N)个布条颜色不同，那么就认为这两面旗帜是不同的。旋转或翻转后才相同的旗帜被认为是不同的旗帜，比方说，“红黄蓝”和“蓝黄红”被认为是不同的旗帜。有的时候，一些颜色放在相邻的位置上会显得很不好看，比方说红色和绿色放在一起就很不好看。作为一个完美主义者，Freda可不想这样。<BR>全校共有N个班级，不同的班级必须使用不同的旗帜，Freda也就需要制作N面不同的旗帜了。和谐起见，Freda想让使用布条数目最多的那面旗帜使用的布条数目最少，请你帮助Freda计算一下，在避免了不好看的情况之后，使用布条数目最多的那面旗帜最少要用多少布条。 

 
 # 输入格式 
第一行两个整数N，C，表示班级的数目和Freda拥有C种颜色的布条。<BR>接下来C行，每行一个长度为C的字符串，每个字符都为’0’或’1’，第i行第j个字符表示第i种颜色和第j种颜色是否能够相邻。如果能，第i行第j个字符为’1’，否则为’0’.保证第i行第j个字符与第j行第i个字符相同。 

 
 # 输出格式 
一行一个整数，表示制作了N面不同的旗帜的情况下，使用布条数目最多的那面旗帜最少需要多少布条。 

 
 # 提示 
样例解释<BR>我们分别制作如下旗帜：<BR>(1),(2),(1,1),(1,2),(2,1),(2,2),(1,1,1),(1,1,2),(1,2,1),(1,2,2)<BR>用布条最多的旗帜所用布条为3.<BR>数据范围与约定<BR>对于50%的数据，保证0&nbsp;&lt;&nbsp;N&nbsp;&lt;=&nbsp;50000.<BR>对于80%的数据，保证0&nbsp;&lt;&nbsp;N&nbsp;&lt;=&nbsp;10^9.<BR>对于100%的数据，保证0&nbsp;&lt;&nbsp;N&nbsp;&lt;=&nbsp;10^18,&nbsp;0&nbsp;&lt;&nbsp;C&nbsp;&lt;=10且数据一定有解.<BR>Description&nbsp;From&nbsp;/&nbsp;Translated&nbsp;-&nbsp;This_poet<BR>Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<BR>This_poet's&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com 
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
<tr><td>10 2
11 
11
</td><td>3
</td></tr></table>
