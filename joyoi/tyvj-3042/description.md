# 

 
 # 题目描述 
<p>
精灵王国中的土精灵是红绿色盲，也即红色和绿色在他们看来是完全相同的。这使得土精灵很难创作出吸引其他精灵的作品。假定一幅方形画作由N×N  (1 <= N <= 100)个方格组成，每个方格是R（red）、G（green）或者B（blue）。grid of characters (1 <= N <= 100), each one either R (red), G (green), or B (blue). 精灵认为一幅画包含越多的可以区分的颜色块，这幅画就越有意思。如果一个方格在另一个方格的东、西、南、北方，就认为它们是相邻的。当两个方格相邻并且无法区分它们的颜色时，认为它们属于同一个颜色块。例如，对于画作<br>RRRBB<br>GGBBB<br>BBBRR<br>BBRRR<br>RRRRR<br>在其他精灵看来这幅画有4个颜色块（2个红的，1个蓝的，1个绿的），但在土精灵看来只有3个颜色块（2个红绿的，1个蓝的）。给定一幅画，请帮忙算出在其他精灵和土精灵眼中，各有多少颜色块。<br></p> 

 
 # 输入格式 
<p>
第1行：整数N。<br>第2…N+1行：每一行包含N个字符，描述画作的一行。<br></p> 

 
 # 输出格式 
<p>
第1行：两个空格分开的整数，描述在其他精灵和土精灵眼中各有多少颜色块。</p> 
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
<tr><td>5
RRRBB
GGBBB
BBBRR
BBRRR
RRRRR
</td><td>4 3</td></tr></table>
