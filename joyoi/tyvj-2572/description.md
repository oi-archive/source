# 

 
 # 题目描述 
<p>
<br>Farmer John has N (1 <= N <= 25,000) rectangular barns on his farm, all<br>with sides parallel to the X and Y axes and integer corner coordinates in<br>the range 0..1,000,000. These barns do not overlap although they may<br>share corners and/or sides with other barns.<br><br>Since he has extra cows to milk this year, FJ would like to expand some of<br>his barns.  A barn has room to expand if it does not share a corner or a<br>wall with any other barn.  That is, FJ can expand a barn if all four of its<br>walls can be pushed outward by at least some amount without bumping into<br>another barn.  If two barns meet at a corner, neither barn can expand.<br><br>Please determine how many barns have room to expand.<br><br></p> 

 
 # 输入格式 
<p>
<br>* Line 1: A single integer, N<br><br>* Lines 2..N+1: Four space-separated integers A, B, C, and D,<br>        describing one barn. The lower-left corner of the barn is at<br>        (A,B) and the upper right corner is at (C,D).<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: A single integer that is the number of barns that can be<br>        expanded.<br></p> 
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
0 2 2 7
3 5 5 8
4 2 6 4
6 1 8 6
0 0 8 1

INPUT DETAILS:

There are 5 barns.  The first barn has its lower-left corner at (0,2) and
its upper-right corner at (2,7), and so on.
</td><td>
2

OUTPUT DETAILS:

Only two barns can be expanded --- the first two listed in the input.
All other barns are each in contact with at least one other barn.</td></tr></table>
