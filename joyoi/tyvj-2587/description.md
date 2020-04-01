# 

 
 # 题目描述 
<p>
<br>It is a little known fact that cows love apples.  Farmer John has<br>two apple trees (which are conveniently numbered 1 and 2) in his<br>field, each full of apples.  Bessie cannot reach the apples when<br>they are on the tree, so she must wait for them to fall.  However,<br>she must catch them in the air since the apples bruise when they<br>hit the ground (and no one wants to eat bruised apples).  Bessie<br>is a quick eater, so an apple she does catch is eaten in just a few<br>seconds.<br><br>Each minute, one of the two apple trees drops an apple. Bessie,<br>having much practice, can catch an apple if she is standing under<br>a tree from which one falls. While Bessie can walk between the two<br>trees quickly (in much less than a minute), she can stand under<br>only one tree at any time. Moreover, cows do not get a lot of<br>exercise, so she is not willing to walk back and forth between the<br>trees endlessly (and thus misses some apples).<br><br>Apples fall (one each minute) for T (1 <= T <= 1,000) minutes.<br>Bessie is willing to walk back and forth at most W (1 <= W <= 30)<br>times. Given which tree will drop an apple each minute, determine<br>the maximum number of apples which Bessie can catch.  Bessie starts<br>at tree 1.<br><br></p> 

 
 # 输入格式 
<p>
<br>* Line 1: Two space separated integers: T and W<br><br>* Lines 2..T+1: 1 or 2: the tree that will drop an apple each minute.<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: The maximum number of apples Bessie can catch without<br>        walking more than W times.<br><br></p> 
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
7 2
2
1
1
2
2
1
1

INPUT DETAILS:

Seven apples fall - one from tree 2, then two in a row from tree 1, then
two in a row from tree 2, then two in a row from tree 1. Bessie is 
willing to walk from one tree to the other twice.

</td><td>
6

OUTPUT DETAILS:

Bessie can catch six apples by staying under tree 1 until the first two
have dropped, then moving to tree 2 for the next two, then returning back
to tree 1 for the final two.</td></tr></table>
