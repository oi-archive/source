# 

 
 # 题目描述 
<p>
<br>Farmer John wishes to build a corral for his cows. Being finicky<br>beasts, they demand that the corral be square and that the corral<br>contain at least C (1 <= C <= 500) clover fields for afternoon<br>treats. The corral's edges must be parallel to the X,Y axes. <br><br>FJ's land contains a total of N (C <= N <= 500) clover fields, each<br>a block of size 1 x 1 and located at with its lower left corner at<br>integer X and Y coordinates each in the range 1..10,000. Sometimes<br>more than one clover field grows at the same location; such a field<br>would have its location appear twice (or more) in the input. A<br>corral surrounds a clover field if the field is entirely located<br>inside the corral's borders.<br><br>Help FJ by telling him the side length of the smallest square<br>containing C clover fields.<br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: C and N<br><br>* Lines 2..N+1: Each line contains two space-separated integers that<br>        are the X,Y coordinates of a clover field.<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: A single line with a single integer that is length of one<br>        edge of the minimum size square that contains at least C<br>        clover fields.<br><br></p> 
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
3 4
1 2
2 1
4 1
5 2

找一个区域至少包含3个草地,它会给出这些草地的坐标...
注意是X_Y坐标系....

INPUT DETAILS:

|*   *
| * *
+------

</td><td>
4

OUTPUT DETAILS:

Below is one 4x4 solution (C's show most of the corral's area); many
others exist.

|CCCC
|CCCC
|*CCC*
|C*C*
+------</td></tr></table>
