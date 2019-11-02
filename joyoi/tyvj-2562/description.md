# 

 
 # 题目描述 
<p>
<br>In order to get from one of the F (1 <= F <= 5,000) grazing fields<br>(which are numbered 1..F) to another field, Bessie and the rest of<br>the herd are forced to cross near the Tree of Rotten Apples.  The<br>cows are now tired of often being forced to take a particular path<br>and want to build some new paths so that they will always have a<br>choice of at least two separate routes between any pair of fields.<br>They currently have at least one route between each pair of fields<br>and want to have at least two. Of course, they can only travel on<br>Official Paths when they move from one field to another.<br><br>Given a description of the current set of R (F-1 <= R <= 10,000)<br>paths that each connect exactly two different fields, determine the<br>minimum number of new paths (each of which connects exactly two<br>fields) that must be built so that there are at least two separate<br>routes between any pair of fields. Routes are considered separate<br>if they use none of the same paths, even if they visit the same<br>intermediate field along the way.<br><br>There might already be more than one paths between the same pair of<br>fields, and you may also build a new path that connects the same<br>fields as some other path.<br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: F and R<br><br>* Lines 2..R+1: Each line contains two space-separated integers which<br>        are the fields at the endpoints of some path.<br></p> 

 
 # 输出格式 
<p>
* Line 1: A single integer that is the number of new paths that must<br>        be built.<br><br></p> 
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
7 7
1 2
2 3
3 4
2 5
4 5
5 6
5 7

INPUT DETAILS:

One visualization of the paths is:
   1   2   3
   +---+---+  
       |   |
       |   |
 6 +---+---+ 4
      / 5
     / 
    / 
 7 +
</td><td>
2

OUTPUT DETAILS:

Building new paths from 1 to 6 and from 4 to 7 satisfies the conditions.
   1   2   3
   +---+---+  
   :   |   |
   :   |   |
 6 +---+---+ 4
      / 5  :
     /     :
    /      :
 7 + - - - - 
Check some of the routes:
1 - 2:  1 -> 2 and 1 -> 6 -> 5 -> 2
1 - 4:  1 -> 2 -> 3 -> 4 and 1 -> 6 -> 5 -> 4
3 - 7:  3 -> 4 -> 7 and 3 -> 2 -> 5 -> 7
Every pair of fields is, in fact, connected by two routes.

It's possible that adding some other path will also solve the problem
(like one from 6 to 7). Adding two paths, however, is the minimum.</td></tr></table>
