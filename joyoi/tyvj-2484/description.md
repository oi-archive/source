# 

 
 # 题目描述 
<p>
Farmer John's cows have taken an interest in exploring the territory<br>around the farm. Initially, all N (1 <= N <= 1,000,000,000) cows<br>commence traveling down a road in one big group. Upon encountering<br>a fork in the road, the group sometimes chooses to break into two<br>smaller (nonempty) groups with each group continuing down one of<br>the roads.  When one of those groups arrives at another fork, it<br>might split again, and so on.<br><br>The cows have crafted a peculiar way of splitting: if they can split<br>into two groups such that the sizes of the groups differ by exactly<br>K (1 <= K <= 1000), then they will split in that way; otherwise,<br>they stop exploring and just start grazing peacefully.<br><br>Assuming that there will always be new forks in the road, compute<br>the final number of groups of peacefully grazing cows.<br>N个牛走路,遇到分叉,如果能分成人数之差为K的两堆,则分头行进.<br>否则就不走了.问最多分成几个块.<br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: N and K<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: A single integer representing the number of groups of<br>        grazing cows<br><br></p> 
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
<tr><td>6 2

INPUT DETAILS:

There are 6 cows and the difference in group sizes is 2.

</td><td>3

OUTPUT DETAILS:

There are 3 final groups (with 2, 1, and 3 cows in them).

   6
  / \
 2   4
    / \
   1   3</td></tr></table>
