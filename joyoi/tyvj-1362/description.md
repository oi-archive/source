# 

 
 # 题目背景 
seer号要起飞了…… 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;起飞要用n块黄晶矿，企鹅负责开采。（好惨）<BR>矿区是一块x*y的地，有x*y&nbsp;div&nbsp;2块黄晶矿（用‘#’表示），但是有石块堵了路（用‘0’表示）。好在企鹅有m个炸药，每个可以炸开一块岩石。问企鹅可不可以在炸药用完前收集好黄晶矿。<BR>&nbsp;&nbsp;&nbsp;&nbsp;以下是3*3的图：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;#0.<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0#0<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;##0（用'.'表示出发点） 

 
 # 输入格式 
输入格式：<BR>&nbsp;&nbsp;第一行:n,x,y,m；<BR>&nbsp;&nbsp;接下来的x行，每行y个字符（#,0或.）数据确保‘.’只有一个，并一定在（1，y）。 

 
 # 输出格式 
输出格式：<BR>&nbsp;&nbsp;可收集成功输出‘yes’；否则输出‘no’； 

 
 # 提示 
数据范围：<BR>&nbsp;0&lt;x&lt;y&lt;30<BR>&nbsp;0&lt;=m&lt;1000<BR>&nbsp;0&lt;n&lt;=450第一次上传，多多包涵。企鹅 
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
<tr><td>1 2 3 10
00.
###</td><td>yes</td></tr></table>
