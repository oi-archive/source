# 

 
 # 题目背景 
TYVJ&nbsp;2月月赛第三道 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;有一座大桥，大桥很长。如图。大桥是单向的，只能从一边走向一边。大桥中每一段子桥都有一个限制ki,表示这个子桥在某一个单位时间能通过的汽车数量。有一天，在这个大桥上举行汽车比赛。选手汽车从A点开往B点，为了不让汽车出现堵塞的情况，那么最多可以让多少量汽车参与比赛呢？<BR>&nbsp;<img src="/source/joyoi/tyvj-1277/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTI3Ny8mbmJzcDsvcHJvYmxlbWltZy8xMjc3LTEuanBn.jpg" border=0 align=middle> 

 
 # 输入格式 
第一行：一个数字n，表示大桥长度<BR>第二行：n-1个数字，表示上面横着向右的桥的ki<BR>第三行：n-1个数字，表示下面横着向右的桥的ki<BR>第四行：n-1个数字，表示斜着桥的ki<BR>第五行：n个数字，表示依次竖着桥的ki<BR> 

 
 # 输出格式 
一行一个数字，表示最多可以参与比赛的汽车数量 

 
 # 提示 
&nbsp;<img src="/source/joyoi/tyvj-1277/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTI3Ny8mbmJzcDsvcHJvYmxlbWltZy8xMjc3LTIuanBn.jpg" border=0 align=middle><BR><BR>数据范围约定<BR>20%&nbsp;N&lt;=&nbsp;10<BR>40%&nbsp;N&lt;=1000<BR>60%&nbsp;N&nbsp;&lt;=&nbsp;20000<BR>80%&nbsp;N&nbsp;&lt;=&nbsp;200000<BR>100%&nbsp;N&lt;=1500000<BR>100%数据满足&nbsp;0&lt;ki&lt;=2^29/N<BR>form&nbsp;TSY\XYF&nbsp;&nbsp;TYVJ月赛出题组 
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
<tr><td>3
1 1
2 2
4 4
3 3 3
</td><td>3</td></tr></table>
