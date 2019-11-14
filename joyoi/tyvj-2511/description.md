# 

 
 # 题目描述 
<p>
<br>FJ and his cows enjoy playing a mental game. They write down the<br>numbers from 1 to N (1 <= N <= 10) in a certain order and then sum<br>adjacent numbers to produce a new list with one fewer number.  They<br>repeat this until only a single number is left.  For example, one<br>instance of the game (when N=4) might go like this:<br><br>    3   1   2   4<br>      4   3   6<br>        7   9<br>         16<br><br>Behind FJ's back, the cows have started playing a more difficult<br>game, in which they try to determine the starting sequence from<br>only the final total and the number N.  Unfortunately, the game is<br>a bit above FJ's mental arithmetic capabilities.<br><br>Write a program to help FJ play the game and keep up with the cows.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: N and the final sum.<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: An ordering of the integers 1..N that leads to the given<br>        sum.  If there are multiple solutions, choose the one that is<br>        lexicographically least, i.e., that puts smaller numbers<br>        first.<br></p> 
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
4 16
</td><td>
3 1 2 4

OUTPUT DETAILS:

There are other possible sequences, such as 3 2 1 4, but 3 1 2 4
is the lexicographically smallest.</td></tr></table>
