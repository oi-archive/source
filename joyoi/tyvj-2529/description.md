# 

 
 # 题目描述 
<p>
Bessie's been appointed the new watch-cow for the farm. Every night,<br>it's her job to walk across the farm and make sure that no evildoers<br>are doing any evil. She begins at the barn, makes her patrol, and<br>then returns to the barn when she's done.<br><br>If she were a more observant cow, she might be able to just walk<br>each of M (1 <= M <= 50,000) bidirectional trails numbered 1..M<br>between N (2 <= N <= 10,000) fields numbered 1..N on the farm once<br>and be confident that she's seen everything she needs to see.  But<br>since she isn't, she wants to make sure she walks down each trail<br>exactly twice.  It's also important that her two trips along each<br>trail be in opposite directions, so that she doesn't miss the same<br>thing twice.<br><br>A pair of fields might be connected by more than one trail.  Find<br>a path that Bessie can follow which will meet her requirements.<br>Such a path is guaranteed to exist.<br><br>从1开始访问,将每条边正向走一遍,反向也走一遍.</p> 

 
 # 输入格式 
<p>
* Line 1: Two integers, N and M.<br><br>* Lines 2..M+1: Two integers denoting a pair of fields connected by a<br>        path.<br><br></p> 

 
 # 输出格式 
<p>
* Lines 1..2M+1: A list of fields she passes through, one per line,<br>        beginning and ending with the barn at field 1. If more than<br>        one solution is possible, output any solution.<br><br></p> 

 
 # 提示 
<p>
请不要提交....</p> 
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
<tr><td>4 5//四个点,五条边
1 2
1 4
2 3
2 4
3 4
</td><td>1
2
3
4
2
1
4
3
2
4
1

OUTPUT DETAILS:

Bessie starts at 1 (barn), goes to 2, then 3, etc...</td></tr></table>
