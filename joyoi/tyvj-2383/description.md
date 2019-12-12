# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2383/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjM4My9wcm9ibGVtc19pbWFnZXMvMjc3Ni8xNTAxXzEuanBn.jpg"></p> 

 
 # 输入格式 
<p>
文件中包含初始的盘件描述，一共有10行，第i行有i个字符。如果第i行的第j个字符是字母”A”至”L”中的一个，则表示第i行第j列的格子上已经放了零件，零件的编号为对应的字母。如果第i行的第j个字符是”.”，则表示第i行第j列的格子上没有放零件。<br>输入保证预放的零件已摆放在盘件中。<br><br></p> 

 
 # 输出格式 
<p>
如果能找到解，向输出文件打印10行，为放完全部12个零件后的布局。其中，第i行应包含i个字符，第i行的第j个字符表示第i行第j列的格子上放的是哪个零件。<br>如果无解，输出单独的一个字符串‘No solution’(不要引号，请注意大小写)。<br>所有的数据保证最多只有一组解。<br><br></p> 
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
<tr><td>.
..
...
....
.....
.....C
...CCC.
EEEHH...
E.HHH....
E.........

</td><td>B
BK
BKK
BJKK
JJJDD
GJGDDC
GGGCCCI
EEEHHIIA
ELHHHIAAF
ELLLLIFFFF</td></tr></table>
