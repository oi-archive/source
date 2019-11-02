# 

 
 # 题目描述 
<p>
<br>For the daily milking, Farmer John's N cows (1 <= N <= 50,000)<br>always line up in the same order. One day Farmer John decides to<br>organize a game of Ultimate Frisbee with some of the cows. To keep<br>things simple, he will take a contiguous range of cows from the<br>milking lineup to play the game. However, for all the cows to have<br>fun they should not differ too much in height.<br><br>Farmer John has made a list of Q (1 <= Q <= 200,000) potential<br>groups of cows and their heights (1 <= height <= 1,000,000). For<br>each group, he wants your help to determine the difference in height<br>between the shortest and the tallest cow in the group.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers, N and Q.<br><br>* Lines 2..N+1: Line i+1 contains a single integer that is the height<br>        of cow i<br><br>* Lines N+2..N+Q+1: Two integers A and B (1 <= A <= B <= N),<br>        representing the range of cows from A to B inclusive.<br><br></p> 

 
 # 输出格式 
<p>
6 3<br>1<br>7<br>3<br>4<br>2<br>5<br>1 5<br>4 6<br>2 2<br><br><br></p> 
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
<tr><td>* Lines 1..Q: Each line contains a single integer that is a response
        to a reply and indicates the difference in height between the
        tallest and shortest cow in the range.
</td><td>
6
3
0</td></tr></table>
