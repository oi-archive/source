# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;“数字是世界上最美丽的图形。”——乌龟。<BR>&nbsp;&nbsp;&nbsp;&nbsp;知道吗？数字可以很美丽，我们有很多写出漂亮数字的方法，下面就是一种从0到9的写法：<BR><BR><img src="/source/joyoi/tyvj-1244/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTI0NC9wcm9ibGVtaW1nLzExLmJtcA==.bmp" border=0 align=middle><img src="/source/joyoi/tyvj-1244/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTI0NC9wcm9ibGVtaW1nLzEyLmJtcA==.bmp" border=0 align=middle><BR>左图&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;右图<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;数字也是可以有大有小的，右边的就比较大。<BR>&nbsp;&nbsp;&nbsp;&nbsp;左边的图，我们称其大小为3，因为其宽度为3，高度为2*3-1=5。同理，右边的图大小为4。<BR>&nbsp;&nbsp;&nbsp;&nbsp;我们的问题也很简单，给出一个图形，问它是不是数字，如果是，告诉我们它是几，如果不是输出“?”。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入共有5个数据。<BR>&nbsp;&nbsp;&nbsp;&nbsp;每组数据给出图形的大小n，接下来2n-1行，每行n个字符，由“#”和“.”组成。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出仅包括一行，共有五个输出，即每组数据有一个输出，如果是数字输出它是几，如果不是数字，请输出“?”，最后回车。 

 
 # 提示 
正整数n的大小不超过100。<BR>保证数据中N&gt;=3EZ_lzh。第一次举办比赛，出得不好或有错，请多包涵。 
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
<tr><td>2
.#
.#
.#
6
######
#....#
#....#
#....#
#....#
#....#
#....#
#....#
#....#
#....#
######
5
#####
#...#
#...#
#...#
#...#
#...#
#...#
#...#
#####
4
#..#
#..#
#..#
####
...#
...#
...#
4
####
....
....
####
...#
...#
...#
</td><td>1004?
</td></tr></table>
