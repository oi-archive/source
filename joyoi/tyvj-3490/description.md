# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-3490/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzQ5MC9wcm9ibGVtc19pbWFnZXMvMjg0MS8xNTY4LmpwZw==.jpg"></p> 

 
 # 输入格式 
<p>
第一行 ：一个整数N ，表示方案和询问的总数。<br>接下来N行，每行开头一个单词“Query”或“Project”。<br>若单词为Query，则后接一个整数T，表示Blue Mary询问第T天的最大收益。<br>若单词为Project，则后接两个实数S，P，表示该种设计方案第一天的收益S，以及以后每天比上一天多出的收益P。<br><br></p> 

 
 # 输出格式 
<p>
对于每一个Query，输出一个整数，表示询问的答案，并精确到整百元（以百元为单位，例如：该天最大收益为210或290时，均应该输出2）。<br><br><br></p> 

 
 # 提示 
<p>
约定：<br>1 <= N <= 100000<br>1 <= T <=50000 <br>0 < P < 100，| S | <= 10^6<br><br>提示：本题读写数据量可能相当巨大，请选手注意选择高效的文件读写方式。<br><br></p> 
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
Query 2
Project 0 100
Query 2
Project 280 10
Query 2
Project 290 10
Query 2


</td><td>
0
1
2
3

</td></tr></table>
