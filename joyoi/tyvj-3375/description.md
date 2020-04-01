# 

 
 # 题目描述 
<p>
交错匹配（cross.pas\c\cpp）<br><br>【题目描述】<br>　　有两行自然数，UP[1..N]，DOWN[1..M]，如果UP[I]=DOWN[J]=K，那么上行的第I个位置的数就可以跟下行的第J个位置的数连一条线，称为一条K匹配，但是同一个位置的数最多只能连一条线。另外，每个K匹配都必须且至多跟一个L匹配相交且K≠L！现在要求一个最大的匹配数。<br>例如：以下两行数的最大匹配数为8<br><br><center><img src="/source/joyoi/tyvj-3375/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzM3NS9wcm9ibGVtc19pbWFnZXMvMjE2My8xLmpwZw==.jpg"></img></center></p> 

 
 # 输入格式 
<p>
　　输入文件cross.in第一行有两个正整数N和M。第二行N个UP的自然数，第三行M个DOWN的自然数。其中0<N、M<=200，UP、DOWN的数都不超过32767。</p> 

 
 # 输出格式 
<p>
　　输出文件CROSS.OUT输出最大匹配数。</p> 
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
<tr><td>【输入样例1】
12 11
1 2 3 3 2 4 1 5 1 3 5 10
3 1 2 3 2 4 12 1 5 5 3

【输入样例2】
4 4
1 1 3 3
1 1 3 3
</td><td>【输出样例1】
８
【输出样例2】
０
</td></tr></table>
