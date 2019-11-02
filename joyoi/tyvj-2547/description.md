# 

 
 # 题目描述 
<p>
<br>Farmer John's N cows (1 <= N <= 100,000) share many similarities.<br>In fact, FJ has been able to narrow down the list of features shared<br>by his cows to a list of only K different features (1 <= K <= 30).<br>For example, cows exhibiting feature #1 might have spots, cows<br>exhibiting feature #2 might prefer C to Pascal, and so on.<br><br>FJ has even devised a concise way to describe each cow in terms of<br>its "feature ID", a single K-bit integer whose binary representation<br>tells us the set of features exhibited by the cow. As an example,<br>suppose a cow has feature ID = 13. Since 13 written in binary is<br>1101, this means our cow exhibits features 1, 3, and 4 (reading<br>right to left), but not feature 2. More generally, we find a 1 in<br>the 2^(i-1) place if a cow exhibits feature i.<br><br>Always the sensitive fellow, FJ lined up cows 1..N in a long row<br>and noticed that certain ranges of cows are somewhat "balanced" in<br>terms of the features the exhibit. A contiguous range of cows i..j<br>is balanced if each of the K possible features is exhibited by the<br>same number of cows in the range. FJ is curious as to the size of<br>the largest balanced range of cows. See if you can determine it.<br><br></p> 

 
 # 输入格式 
<p>
<br>* Line 1: Two space-separated integers, N and K.<br><br>* Lines 2..N+1: Line i+1 contains a single K-bit integer specifying<br>        the features present in cow i.  The least-significant bit of<br>        this integer is 1 if the cow exhibits feature #1, and the<br>        most-significant bit is 1 if the cow exhibits feature #K.<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: A single integer giving the size of the largest contiguous<br>        balanced group of cows.<br><br></p> 
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

7 3
7
6
7
2
1
4
2

INPUT DETAILS:

The line has 7 cows with 3 features; the table below summarizes the
correspondence:
              Feature 3:   1   1   1   0   0   1   0
              Feature 2:   1   1   1   1   0   0   1
              Feature 1:   1   0   1   0   1   0   0
              Key:         7   6   7   2   1   4   2
              Cow #:       1   2   3   4   5   6   7</td><td>
4

OUTPUT DETAILS:

In the range from cow #3 to cow #6 (of size 4), each feature appears
in exactly 2 cows in this range:
              Feature 3:     1   0   0   1  -> two total
              Feature 2:     1   1   0   0  -> two total
              Feature 1:     1   0   1   0  -> two total
              Key:           7   2   1   4 
              Cow #:         3   4   5   6 </td></tr></table>
