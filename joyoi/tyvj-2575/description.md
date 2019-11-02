# 

 
 # 题目描述 
<p>
<br>Farmer John is constructing a new milking machine and wishes to<br>keep it secret as long as possible. He has hidden in it deep within<br>his farm and needs to be able to get to the machine without being<br>detected.  He must make a total of T (1 <= T <= 200) trips to the<br>machine during its construction. He has a secret tunnel that he<br>uses only for the return trips.<br><br>The farm comprises N (2 <= N <= 200) landmarks (numbered 1..N)<br>connected by P (1 <= P <= 40,000) bidirectional trails (numbered<br>1..P) and with a positive length that does not exceed 1,000,000.<br>Multiple trails might join a pair of landmarks.<br><br>To minimize his chances of detection, FJ knows he cannot use any<br>trail on the farm more than once and that he should try to use the<br>shortest trails.<br><br>Help FJ get from the barn (landmark 1) to the secret milking machine<br>(landmark N) a total of T times.  Find the minimum possible length<br>of the longest single trail that he will have to use, subject to the<br>constraint that he use no trail more than once. (Note well: The goal<br>is to minimize the length of the longest trail, not the sum of the<br>trail lengths.)<br><br>It is guaranteed that FJ can make all T trips without reusing a trail.<br><br></p> 

 
 # 输入格式 
<p>
<br>* Line 1: Three space-separated integers: N, P, and T<br><br>* Lines 2..P+1: Line i+1 contains three space-separated integers, A_i,<br>        B_i, and L_i, indicating that a trail connects landmark A_i to<br>        landmark B_i with length L_i.<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: A single integer that is the minimum possible length of the<br>        longest segment of Farmer John's route.<br><br></p> 
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
7 9 2
1 2 2
2 3 5
3 7 5
1 4 1
4 3 1
4 5 7
5 7 1
1 6 3
6 7 3
</td><td>
5

OUTPUT DETAILS:

Farmer John can travel trails 1 - 2 - 3 - 7 and 1 - 6 - 7.  None of
the trails travelled exceeds 5 units in length.  It is impossible
for Farmer John to travel from 1 to 7 twice without using at least
one trail of length 5.</td></tr></table>
