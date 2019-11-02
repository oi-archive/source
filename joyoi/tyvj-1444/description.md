# 

 
 # 题目背景 
Fated&nbsp;Me原创 

 
 # 题目描述 
歌者：“请给予我二相铂。”<BR>曲者：“没问题么？”<BR>歌者：“归零者在。”<BR>曲者：“给。”<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;——《三体·死神永生》<BR>&nbsp;&nbsp;这样，由于一张纸片薄的二相铂，太阳系开始向二维跌落，地球当然不会幸免于难。观察者将给予编纂者这个世界的蓝图，而你作为编纂者请描绘这个世界的二维图像。 

 
 # 输入格式 
第一行你将得到某个区域的高楼的个数B。<BR>	每个高楼由N个边长为E的正方形纵向叠加而成（成为一个长方体）。<BR>	所以第2到B+1行，每行2个数Ei和Ni。 

 
 # 输出格式 
由高到低的图像。楼顶为下划线“_”，每个下划线之间有一个空格。楼的边框为“|”。如果2个下划线间有“|”，那么就不用再多加空格。<BR><BR>由于tyvj评测方式为取出行末空格空行后全文比对，请千万注意，除了上述说明的需要打印的楼的轮廓边缘以外，其它任何地方，尤其是楼中间空的地方不要加多余的空格，否则会WA。所以温馨提示：您最好建立一个空二维字符数组然后往相应位置上填充轮廓T_T。 

 
 # 提示 
由于记事本有宽度限制，所以：数据范围：输入的所有数字不会超过10.Fated&nbsp;Me 
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
<tr><td>1
5 5

</td><td>//由于数据图形比较特殊，查看数据的时候有的数据无法显示，不过数据都是正确的，只需要按照题目要求输出即可！
 _ _ _ _ _ 
|         |
|         |
|         |
|         |
|         |
|         |
|         |
|         |
|         |
|         |
|         |
|         |
|         |
|         |
|         |
|         |
|         |
|         |
|         |
|         |
|         |
|         |
|         |
|         |
|_ _ _ _ _|</td></tr></table>
