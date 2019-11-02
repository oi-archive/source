# 

 
 # 题目描述 
<p>
Rain has pummeled the cows' field, a rectangular grid of R rows and<br>C columns (1 <= R <= 50, 1 <= C <= 50). While good for the grass,<br>the rain makes some patches of bare earth quite muddy. The<br>cows, being meticulous grazers, don't want to get their hooves dirty<br>while they eat.<br><br>To prevent those muddy hooves, Farmer John will place a number of<br>wooden boards over the muddy parts of the cows' field.  Each of the<br>boards is 1 unit wide, and can be any length long.  Each board must<br>be aligned parallel to one of the sides of the field.<br><br>Farmer John wishes to minimize the number of boards needed to cover<br>the muddy spots, some of which might require more than one board<br>to cover.  The boards may not cover any grass and deprive the cows<br>of grazing area but they can overlap each other.<br><br>Compute the minimum number of boards FJ requires to cover all the mud in<br>the field.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: R and C<br><br>* Lines 2..R+1: Each line contains a string of C characters, with '*'<br>        representing a muddy patch, and '.' representing a grassy<br>        patch. No spaces are present.<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: A single integer representing the number of boards FJ needs.<br><br></p> 
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
<tr><td>4 4
*.*.
.***
***.
..*.
</td><td>4

OUTPUT DETAILS:

Boards 1, 2, 3 and 4 are placed as follows:
1.2.
.333
444.
..2.
Board 2 overlaps boards 3 and 4.</td></tr></table>
