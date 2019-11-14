# 

 
 # 题目背景 
上传图片的那个空间速度比较缓慢，看不到图的话多刷新两遍就能看到了&nbsp;&gt;_&lt;<BR>实在不行去&nbsp;http://poj.org/problem?id=3960&nbsp;看原题…… 

 
 # 题目描述 
考虑定义在&nbsp;0&nbsp;到&nbsp;9&nbsp;之间的数字上的二元运算<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMjA4MS5wb2NvLmNuL215cG9jby9teXBob3RvLzIwMTExMjAyLzIzLzY0NTgxMzkyMjAxMTEyMDIyMzUzMzEwNC5wbmc=.png" border=0 align=middle>。<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMjA4MS5wb2NvLmNuL215cG9jby9teXBob3RvLzIwMTExMjAyLzIzLzY0NTgxMzkyMjAxMTEyMDIyMzUzMzEwNC5wbmc=.png" border=0 align=middle>:&nbsp;{0,&nbsp;1,&nbsp;...,&nbsp;9}&nbsp;×&nbsp;{0,&nbsp;1,&nbsp;...,&nbsp;9}&nbsp;<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMjA4MS5wb2NvLmNuL215cG9jby9teXBob3RvLzIwMTExMjAyLzIzLzY0NTgxMzkyMjAxMTEyMDIyMzUxNDIwMi5wbmc=.png" border=0 align=middle>&nbsp;{0,&nbsp;1,&nbsp;...,&nbsp;9}，并且满足&nbsp;0&nbsp;<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMjA4MS5wb2NvLmNuL215cG9jby9teXBob3RvLzIwMTExMjAyLzIzLzY0NTgxMzkyMjAxMTEyMDIyMzUzMzEwNC5wbmc=.png" border=0 align=middle>&nbsp;0&nbsp;=&nbsp;0。<BR>二元运算<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMTY1LnBvY28uY24vbXlwb2NvL215cGhvdG8vMjAxMTEyMDIvMjMvNjQ1ODEzOTIyMDExMTIwMjIzNTM1MTAyMy5wbmc=.png" border=0 align=middle>是运算<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMjA4MS5wb2NvLmNuL215cG9jby9teXBob3RvLzIwMTExMjAyLzIzLzY0NTgxMzkyMjAxMTEyMDIyMzUzMzEwNC5wbmc=.png" border=0 align=middle>在非负整数集合上的推广，<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMTY1LnBvY28uY24vbXlwb2NvL215cGhvdG8vMjAxMTEyMDIvMjMvNjQ1ODEzOTIyMDExMTIwMjIzNTM1MTAyMy5wbmc=.png" border=0 align=middle>:&nbsp;<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMTY1LnBvY28uY24vbXlwb2NvL215cGhvdG8vMjAxMTEyMDIvMjMvNjQ1ODEzOTIyMDExMTIwMjIzNTQxNTAzOS5wbmc=.png" border=0 align=middle>0+&nbsp;×&nbsp;<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMTY1LnBvY28uY24vbXlwb2NvL215cGhvdG8vMjAxMTEyMDIvMjMvNjQ1ODEzOTIyMDExMTIwMjIzNTQxNTAzOS5wbmc=.png" border=0 align=middle>0+&nbsp;<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMjA4MS5wb2NvLmNuL215cG9jby9teXBob3RvLzIwMTExMjAyLzIzLzY0NTgxMzkyMjAxMTEyMDIyMzUxNDIwMi5wbmc=.png" border=0 align=middle>&nbsp;<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMTY1LnBvY28uY24vbXlwb2NvL215cGhvdG8vMjAxMTEyMDIvMjMvNjQ1ODEzOTIyMDExMTIwMjIzNTQxNTAzOS5wbmc=.png" border=0 align=middle>0+。a&nbsp;<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMTY1LnBvY28uY24vbXlwb2NvL215cGhvdG8vMjAxMTEyMDIvMjMvNjQ1ODEzOTIyMDExMTIwMjIzNTM1MTAyMy5wbmc=.png" border=0 align=middle>&nbsp;b&nbsp;的结果是这样定义的：如果&nbsp;a&nbsp;和&nbsp;b&nbsp;中的一个在十进制下的位数小于另一个，那么就在它前面补零直到二者位数相等。之后按位对&nbsp;a&nbsp;和&nbsp;b&nbsp;实施<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMjA4MS5wb2NvLmNuL215cG9jby9teXBob3RvLzIwMTExMjAyLzIzLzY0NTgxMzkyMjAxMTEyMDIyMzUzMzEwNC5wbmc=.png" border=0 align=middle>运算就得到了结果。<BR><img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMTY1LnBvY28uY24vbXlwb2NvL215cGhvdG8vMjAxMTEyMDMvMDAvNjQ1ODEzOTIyMDExMTIwMzAwMDcwMzA5OC5wbmc=.png" border=0 align=middle><BR>规定<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMTY1LnBvY28uY24vbXlwb2NvL215cGhvdG8vMjAxMTEyMDIvMjMvNjQ1ODEzOTIyMDExMTIwMjIzNTM1MTAyMy5wbmc=.png" border=0 align=middle>运算是左结合的，这也就是说，a&nbsp;<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMTY1LnBvY28uY24vbXlwb2NvL215cGhvdG8vMjAxMTEyMDIvMjMvNjQ1ODEzOTIyMDExMTIwMjIzNTM1MTAyMy5wbmc=.png" border=0 align=middle>&nbsp;b&nbsp;<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMTY1LnBvY28uY24vbXlwb2NvL215cGhvdG8vMjAxMTEyMDIvMjMvNjQ1ODEzOTIyMDExMTIwMjIzNTM1MTAyMy5wbmc=.png" border=0 align=middle>&nbsp;c&nbsp;将会被认为是&nbsp;(a&nbsp;<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMTY1LnBvY28uY24vbXlwb2NvL215cGhvdG8vMjAxMTEyMDIvMjMvNjQ1ODEzOTIyMDExMTIwMjIzNTM1MTAyMy5wbmc=.png" border=0 align=middle>&nbsp;b)&nbsp;<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMTY1LnBvY28uY24vbXlwb2NvL215cGhvdG8vMjAxMTEyMDIvMjMvNjQ1ODEzOTIyMDExMTIwMjIzNTM1MTAyMy5wbmc=.png" border=0 align=middle>&nbsp;c。<BR>现在对于给定的二元运算&nbsp;<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMjA4MS5wb2NvLmNuL215cG9jby9teXBob3RvLzIwMTExMjAyLzIzLzY0NTgxMzkyMjAxMTEyMDIyMzUzMzEwNC5wbmc=.png" border=0 align=middle>&nbsp;以及两个非负整数&nbsp;a&nbsp;和&nbsp;b，你的任务是计算&nbsp;a&nbsp;<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMTY1LnBvY28uY24vbXlwb2NvL215cGhvdG8vMjAxMTEyMDIvMjMvNjQ1ODEzOTIyMDExMTIwMjIzNTM1MTAyMy5wbmc=.png" border=0 align=middle>&nbsp;(a&nbsp;+&nbsp;1)&nbsp;<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMTY1LnBvY28uY24vbXlwb2NvL215cGhvdG8vMjAxMTEyMDIvMjMvNjQ1ODEzOTIyMDExMTIwMjIzNTM1MTAyMy5wbmc=.png" border=0 align=middle>&nbsp;(a&nbsp;+&nbsp;2)&nbsp;<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMTY1LnBvY28uY24vbXlwb2NvL215cGhvdG8vMjAxMTEyMDIvMjMvNjQ1ODEzOTIyMDExMTIwMjIzNTM1MTAyMy5wbmc=.png" border=0 align=middle>&nbsp;...&nbsp;<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMTY1LnBvY28uY24vbXlwb2NvL215cGhvdG8vMjAxMTEyMDIvMjMvNjQ1ODEzOTIyMDExMTIwMjIzNTM1MTAyMy5wbmc=.png" border=0 align=middle>&nbsp;(b&nbsp;-&nbsp;1)&nbsp;<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMTY1LnBvY28uY24vbXlwb2NvL215cGhvdG8vMjAxMTEyMDIvMjMvNjQ1ODEzOTIyMDExMTIwMjIzNTM1MTAyMy5wbmc=.png" border=0 align=middle>&nbsp;b&nbsp;的值。 

 
 # 输入格式 
前&nbsp;10&nbsp;行将会给出二元运算<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMjA4MS5wb2NvLmNuL215cG9jby9teXBob3RvLzIwMTExMjAyLzIzLzY0NTgxMzkyMjAxMTEyMDIyMzUzMzEwNC5wbmc=.png" border=0 align=middle>的描述。第&nbsp;i&nbsp;行包括&nbsp;10&nbsp;个空格分隔的整数，其中第&nbsp;j&nbsp;个整数的值即为&nbsp;(i&nbsp;-&nbsp;1)&nbsp;<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMjA4MS5wb2NvLmNuL215cG9jby9teXBob3RvLzIwMTExMjAyLzIzLzY0NTgxMzkyMjAxMTEyMDIyMzUzMzEwNC5wbmc=.png" border=0 align=middle>&nbsp;(j&nbsp;-&nbsp;1)&nbsp;的值。<BR>第&nbsp;1&nbsp;行的第&nbsp;1&nbsp;个数一定为&nbsp;0。<BR>第&nbsp;11&nbsp;行给出两个非负整数&nbsp;a&nbsp;和&nbsp;b，满足&nbsp;0&nbsp;≤&nbsp;a&nbsp;≤&nbsp;b&nbsp;≤&nbsp;10^18。<BR> 

 
 # 输出格式 
输出一个整数表示答案，注意答案不可以有前导&nbsp;0。<BR> 

 
 # 提示 
注意<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMjA4MS5wb2NvLmNuL215cG9jby9teXBob3RvLzIwMTExMjAyLzIzLzY0NTgxMzkyMjAxMTEyMDIyMzUzMzEwNC5wbmc=.png" border=0 align=middle>运算和<img src="/source/joyoi/tyvj-1687/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4Ny9odHRwOi8vaW1nMTY1LnBvY28uY24vbXlwb2NvL215cGhvdG8vMjAxMTEyMDIvMjMvNjQ1ODEzOTIyMDExMTIwMjIzNTM1MTAyMy5wbmc=.png" border=0 align=middle>运算不一定满足交换律和结合律。<BR>Northeastern&nbsp;Europe&nbsp;2010,&nbsp;Binary&nbsp;Operation<BR>Translated&nbsp;by&nbsp;applepi<BR> 
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
<tr><td>0 1 2 3 4 5 6 7 8 9
1 2 3 4 5 6 7 8 9 0
2 3 4 5 6 7 8 9 0 1
3 4 5 6 7 8 9 0 1 2
4 5 6 7 8 9 0 1 2 3
5 6 7 8 9 0 1 2 3 4
6 7 8 9 0 1 2 3 4 5
7 8 9 0 1 2 3 4 5 6
8 9 0 1 2 3 4 5 6 7
9 0 1 2 3 4 5 6 7 8
0 10
</td><td>15
</td></tr></table>
