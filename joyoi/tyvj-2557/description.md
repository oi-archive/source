# 

 
 # 题目描述 
<p>
<br>The N (1 <= N <= 50,000) cows, conveniently numbered 1..N, are<br>trying to learn some encryption algorithms. After studying a few<br>examples, they have decided to make one of their own! However, they<br>are not very experienced at this, so their algorithm is very simple:<br><br>Each cow i is given a starting number C_i (0 <= C_i < 90,000,000),<br>and then all the cows perform the following process in parallel:<br><br>    * First, each cow finds the sum of the numbers of the other N-1<br>      cows.<br><br>    * After all cows are finished, each cow replaces her number<br>      with the sum she computed. To avoid very large numbers, the<br>      cows will keep track of their numbers modulo 98,765,431.<br><br>They told Canmuu the moose about it in November; he was quite<br>impressed.<br><br>Then one foggy Christmas Eve, Canmuu came to say:<br><br>    "Your algorithm is too easy to break! You should repeat it T<br>     (1 <= T <= 1,414,213,562) times instead."<br><br>Obviously, the cows were very frustrated with having to perform so<br>many repetitions of the same boring algorithm, so after many hours<br>of arguing, Canmuu and the cows reached a compromise: You are to<br>calculate the numbers after the encryption is performed!<br><br>*Some extra feedback will be provided for the first 10 submissions to this<br>problem.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: N and T<br><br>* Lines 2..N+1: Line i+1 contains a single integer: C_i<br><br></p> 

 
 # 输出格式 
<p>
<br>* Lines 1..N: Line i contains a single integer representing the number<br>        of cow i (modulo 98,765,431) at the end of the encryption.<br><br></p> 
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
<tr><td>3 4
1
0
4

INPUT DETAILS:

Three cows, with starting numbers 1, 0, and 4; four repetitions of the
encryption algorithm.
</td><td>
26
25
29

OUTPUT DETAILS:

The following is a table of the cows' numbers for each turn:

          Cows' numbers
Turn    Cow1  Cow2  Cow3
 0        1     0     4
 1        4     5     1
 2        6     5     9
 3       14    15    11
 4       26    25    29</td></tr></table>
