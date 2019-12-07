# 

 
 # 题目描述 
<p>
Farmer John wants to evaluate the quality of the names of his N (1<br><= N <= 1000) cows. Each name is a string with no more than 1000<br>characters, all of which are non-blank.<br><br>He has created a set of M (1 <= M <= 100) 'good' strings (no<br>longer than 30 characters and fully non-blank). If the sequence<br>letters of a cow's name contains the letters of a 'good' string in<br>the correct order as a subsequence (i.e., not necessarily all next<br>to each other), the cow's name gets 1 quality point.<br><br>All strings is case-insensitive, i.e., capital letters and lower<br>case letters are considered equivalent.  For example, the name "Bessie"<br>contains the letters of "Be", "sI", "EE", and "Es" in the correct<br>order, but not "is" or "eB". Help Farmer John determine the number<br>of quality points in each of his cow's names.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: N and M<br><br>* Lines 2..N+1: Line i+1 contains a string that is the name of the ith<br>        cow<br><br>* Lines N+2..N+M+1: Line N+i+1 contains the ith good string<br><br></p> 

 
 # 输出格式 
<p>
<br>* Lines 1..N+1: Line i+1 contains the number of quality points of the<br>        ith name<br></p> 
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
<tr><td>5 3
Bessie
Jonathan
Montgomery
Alicia
Angola
se
nGo
Ont

INPUT DETAILS:

There are 5 cows, and their names are "Bessie", "Jonathan",
"Montgomery", "Alicia", and "Angola". The 3 good strings are "se",
"nGo", and "Ont".



</td><td>
1
1
2
0
1

OUTPUT DETAILS:

"Bessie" contains "se", "Jonathan" contains "Ont", "Montgomery" contains
both "nGo" and "Ont", Alicia contains none of the good strings, and
"Angola" contains "nGo".
</td></tr></table>
