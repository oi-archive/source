# 

 
 # 题目描述 
<p>
已知有两个字串A，B及一组字串变换的规则(至多６个规则)：<br>           A1→B1<br>           A2→B2<br>           ………<br>规则的含义为：在A中的子串A1可以变换为B1、A2可以变换为B2……。<br>例如：A=‘abcd’ B=‘xyz’<br>变换规则为：<br>        ‘abc’→‘xu’ ‘ud’→‘y’   ‘y’→‘yz’<br><br>则此时，A可以经过一系列的变换变为B，其变换的过程为：<br>      ‘abcd’→‘xud’→‘xy’→‘xyz’<br><br>共进行了三次变换，使得A变换为B。<br><br></p> 

 
 # 输入格式 
<p>
<br><img src="/source/joyoi/tyvj-2757/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjc1Ny9wcm9ibGVtc19pbWFnZXMvMzI2Ni9wZy5qcGc=.jpg"></img></p> 

 
 # 输出格式 
<p>
输出文件格式如下：<br>若在10步（包含10步）以内能将A变换为B,则输出最少的变换步数；<br>否则输出“NO ANSWER”，不包括引号。<br></p> 
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
<tr><td>abcd  xyz
abc  xu 
ud  y
y  yz
</td><td>3</td></tr></table>
