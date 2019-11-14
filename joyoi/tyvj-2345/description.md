# 

 
 # 题目描述 
<p>
<br><br>After he partitioned his farm into R (1 <= R <= 200) rows and C (1<br><= C <= 200) squares conveniently labeled 1,1 through R,C, Farmer<br>John spent days cutting the hay and stacking a huge amount of it<br>in square 1,1. He then undertook the task of mapping out the N (1<br><= N <= 80,000) haypaths through the farm so that he could deduce<br>the maximum rate he could move hay from square 1,1 to square R,C.<br><br>Each haypath uniquely connects the middle of two rectilinearly<br>adjacent partitioned squares and has some capacity limit L_i (1 <=<br>L_i <= 20,000,000) that is the maximum amount of hay that can be<br>transported in either direction across the haypath.  He's just<br>positive that he can move hay at a reasonable rate to the other<br>side of the farm but he doesn't know what the fastest rate is. Help<br>him learn it.<br></p> 

 
 # 输入格式 
<p>
* Line 1: Three separated integers: R, C, and N<br>* Lines 2..N+1: Line i+1 describes path i with five space-separated<br>        integers: r1, c1, r2, c2, and L_i which denote a haypath<br>        connecting (r1,c1) to (r2,c2) with capacity L_i.<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: One number, on a line by itself, the maximum amount of<br>        material which can be transported from (1,1) to (R,C)<br>        simultaneously.<br></p> 

 
 # 提示 
<p>
<br>Consider the two edges coming out of (2,2), at most 6+1=7 units of hay can<br>be transported. This is indeed feasible.<br></p> 
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
<tr><td>
3 3 8
1 1 1 2 5
1 1 2 1 3
1 2 2 2 5
2 1 2 2 2
2 2 2 3 1
2 2 3 2 6
2 3 3 3 4
3 2 3 3 7

INPUT DETAILS:

The grid is as follows:
*--5--* . . *
|     |     
3     5     :
|     |    
*--2--*--1--*
      |     |
:     6     4
      |     |
* . . *--7--*
    

</td><td>7
</td></tr></table>
