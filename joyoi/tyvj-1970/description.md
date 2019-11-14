# 

 
 # 题目背景 
考古学家发现了一块布，布上做有针线活，叫做“十字绣”，即交替地在布的两面穿线。<BR> 

 
 # 题目描述 
布是一个n*m的网格，线只能在网格的顶点处才能从布的一面穿到另一面。每一段线都覆盖一个单位网格的两条对角线之一，而在绣的过程中，一针中连续的两段线必须分处布的两面。给出布两面的图案，问最少需要几针才能绣出来？一针是指针不离开布的一次绣花过程。<BR><img src="/source/joyoi/tyvj-1970/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTk3MC9Qcm9ibGVtSW1nL1AxMDE1LmdpZg==.gif" border=0 align=middle><BR> 

 
 # 输入格式 
第1行两个数N和M(1&lt;=N,M&lt;=200)。<BR>接下来N行每行M个数描述正面。&nbsp;<BR>再接下来N行每行M个数描述反面。<BR>每个格子用.（表示空）,/（表示从右上角连到左下角）,\（表示从左上角连到右下角）和X（表示连两条对角线）表示。<BR> 

 
 # 输出格式 
一个数，最少要用的针数。<BR> 

 
 # 提示 
Ural&nbsp;State&nbsp;University&nbsp;Problem&nbsp;Archive<BR> 
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
<tr><td>4 5
.....
.\...
..\..
.....
.....
....\ 
.\X..
.....
</td><td>4
</td></tr></table>
