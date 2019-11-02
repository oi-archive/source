# 

 
 # 题目描述 
<p>
<br>A particular subgroup of K (1 <= K <= 25,000) of Farmer John's cows<br>likes to make trouble. When placed in a line, these troublemakers<br>stand together in a particular order. In order to locate these<br>troublemakers, FJ has lined up his N (1 <= N <= 100,000) cows. The<br>cows will file past FJ into the barn, staying in order. FJ needs<br>your help to locate suspicious blocks of K cows within this line<br>that might potentially be the troublemaking cows.<br><br>FJ distinguishes his cows by the number of spots 1..S on each cow's<br>coat (1 <= S <= 25). While not a perfect method, it serves his<br>purposes. FJ does not remember the exact number of spots on each<br>cow in the subgroup of troublemakers. He can, however, remember<br>which cows in the group have the same number of spots, and which<br>of any pair of cows has more spots (if the spot counts differ). He<br>describes such a pattern with a sequence of K ranks in the range<br>1..S.  For example, consider this sequence:<br><br>      1 4 4 3 2 1<br><br>In this example, FJ is seeking a consecutive sequence of 6 cows<br>from among his N cows in a line. Cows #1 and #6 in this sequence<br>have the same number of spots (although this number is not necessarily<br>1) and they have the smallest number of spots of cows #1..#6 (since<br>they are labeled as '1').  Cow #5 has the second-smallest number<br>of spots, different from all the other cows #1..#6.  Cows #2 and<br>#3 have the same number of spots, and this number is the largest<br>of all cows #1..#6.<br><br>If the true count of spots for some sequence of cows is:<br><br> 5 6 2 10 10 7 3 2 9<br><br>then only the subsequence 2 10 10 7 3 2 matches FJ's pattern above.<br><br>Please help FJ locate all the length-K subsequences in his line of<br>cows that match his specified pattern.<br></p> 

 
 # 输入格式 
<p>
* Line 1: Three space-separated integers: N, K, and S<br><br>* Lines 2..N+1: Line i+1 describes the number of spots on cow i.<br><br>* Lines N+2..N+K+1: Line i+N+1 describes pattern-rank slot i.<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: The number of indices, B, at which the pattern matches<br><br>* Lines 2..B+1: An index (in the range 1..N) of the starting location<br>        where the pattern matches.<br><br></p> 
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
9 6 10
5
6
2
10
10
7
3
2
9
1
4
4
3
2
1

INPUT DETAILS:

The sample input corresponds to the example given in the problem statement.

</td><td>
1
3

OUTPUT DETAILS:

There is only one match, at position 3 within FJ's sequence of N cows.</td></tr></table>
