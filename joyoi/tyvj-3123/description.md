# 

 
 # 题目描述 
<p>
问题描述：一个电子表格是一个矩阵，其中的元素可以是数也可以是表达式，表达式可以通过赋值而成为数。一个简单的电子表格，其中的数是整数，表达式是由不同的整数、元素的标示符及'＋'，'－'组成。对任一个表达式，若要求用数表示，则可用赋值以后的数值代替。<br>编程任务：对简单的电子表格进行赋值。<br></p> 

 
 # 输入格式 
<p>
数据输入：<br>　　输入数据由文件名为INPUT.TXT的文本文件提供。<br>　　第一行由2个数据N、M，表示矩阵由N行、M列组成，（n <= 200 , m <= 20 ）。<br>　　列的标示从大写字母Ａ到Ｔ，行的标示从阿拉伯数字1到255，如：第一列第一行的元素用Ａ1表示，第２０列第五行的元素用Ｔ5表示。<br>　　接下来的N行每行有M个元素，每一个元素包含一个有符号的整数或一个表达式，表达式中不能有空格。<br><br><br></p> 

 
 # 输出格式 
<p>
数据输出：<br>　　对每一个输入的电子表格，你必须求出每一个表达式的值。若元素包含循环的表达式，则在输出中应在这些单元打印"ERROR"（不能使用小写）。将求值后的电子表格输出到文件OUTPUT.TXT中。</p> 
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
<tr><td><br><img src="/source/joyoi/tyvj-3123/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzEyMy9wcm9ibGVtc19pbWFnZXMvMTQwNi8xLmJtcA==.bmp"></img></td><td><br><img src="/source/joyoi/tyvj-3123/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzEyMy9wcm9ibGVtc19pbWFnZXMvMTQwNi8yLmJtcA==.bmp"></img></td></tr></table>
