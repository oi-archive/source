# 

 
 # 题目描述 
<p>
<br>Farmer John is making the difficult transition from raising mountain<br>goats to raising cows.  His farm, while ideal for mountain goats,<br>is far too mountainous for cattle and thus needs to be flattened<br>out a bit. Since flattening is an expensive operation, he wants to<br>remove the smallest amount of earth possible.<br><br>The farm is long and narrow and is described in a sort of two-dimensional<br>profile by a single array of N (1 <= N <= 1000) integer elevations<br>(range 1..1,000,000) like this:<br><br>1 2 3 3 3 2 1 3 2 2 1 2,<br><br>which represents the farm's elevations in profile, depicted below<br>with asterisks indicating the heights:<br><br>    * * *     *<br>  * * * * *   * * *   *<br>* * * * * * * * * * * *<br>1 2 3 3 3 2 1 3 2 2 1 2<br><br>A contiguous range of one or more equal elevations in this array<br>is a "peak" if both the left and right hand sides of the range are<br>either the boundary of the array or an element that is lower in<br>elevation than the peak. The example above has three peaks.<br><br>Determine the minimum volume of earth (each unit elevation reduction<br>counts as one unit of volume) that must be removed so that the<br>resulting landscape has no more than K (1 <= K <= 25) peaks.  Note<br>well that elevations can be reduced but can never be increased.<br><br>If the example above is to be reduced to 1 peak, the optimal solution<br>is to remove 2 + 1 + 1 + 1 = 5 units of earth to obtain this set<br>of elevations:<br><br>    * * *     -<br>  * * * * *   - - -   -<br>* * * * * * * * * * * *<br>1 2 3 3 3 2 1 1 1 1 1 1<br><br>where '-'s indicate removed earth.<br><br></p> 

 
 # 输入格式 
<p>
<br>* Line 1: Two space-separated integers: N and K<br><br>* Lines 2..N+1: Each line contains a single integer elevation. Line<br>        i+1 contains the elevation for index i.<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: The minimum volume of earth that must be removed to reduce<br>        the number of peaks to K.<br><br></p> 
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
12 1
1
2
3
3
3
2
1
3
2
2
1
2

INPUT DETAILS:

This is the example used above.

</td><td>
5</td></tr></table>
