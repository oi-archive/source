# 

 
 # 题目描述 
<p>
<br>Farmer John is quite the nature artist: he often constructs large<br>works of art on his farm. Today, FJ wants to construct a giant<br>"field web". FJ's field is large convex polygon with fences along<br>the boundary and fence posts at each of the N corners (1 <= N <=<br>150). To construct his field web, FJ wants to run as many ropes as<br>possible in straight lines between pairs of non-adjacent fence posts<br>such that no two ropes cross.<br><br>There is one complication: FJ's field is not completely usable.<br>Some evil aliens have created a total of G (0 <= G <= 100) grain<br>circles in the field, all of radius R (1 <= R <= 100,000). FJ is<br>afraid to upset the aliens, and therefore doesn't want the ropes<br>to pass through, or even touch the very edge of a grain circle.<br>Note that although the centers of all the circles are contained<br>within the field, a wide radius may make it extend outside of the<br>field, and both fences and fence posts may be within a grain circle.<br><br>Given the locations of the fence posts and the centers of the<br>circles, determine the maximum number of ropes that FJ can use to<br>create his field web.<br><br>FJ's fence posts and the circle centers all have integer coordinates<br>X and Y each of which is in the range 0..1,000,000.<br></p> 

 
 # 输入格式 
<p>
* Line 1: Three space-separated integers: N, G, and R<br><br>* Lines 2..N+1: Each line contains two space-separated integers that<br>        are the X,Y position of a fence post on the boundary of FJ's<br>        field.<br><br>* Lines N+2..N+G+1: Each line contains two space-separated integers<br>        that are the X,Y position of a circle's center inside FJ's<br>        field.<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: A single integer that is the largest number of ropes FJ can<br>        use for his artistic creation.<br></p> 
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
<tr><td>5 3 1
6 10
10 7
9 1
2 0
0 3
2 2
5 6
8 3

INPUT DETAILS:

A pentagonal field, in which all possible ropes are blocked by three
grain circles, except for the rope between fenceposts 2 and 4.
</td><td>
1</td></tr></table>
