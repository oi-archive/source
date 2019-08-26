
# Description

<div class="content"><div class="plm"></div>
<div class="ptx" lang="en-US">Mr. Young wishes to take a picture of his class. The students will stand in rows with each row no longer than the row behind it and the left ends of the rows aligned. For instance, 12 students could be arranged in rows (from back to front) of 5, 3, 3 and 1 students. <br/>
<pre>X X X X X
<br/>X X X
<br/>X X X
<br/>X</pre>
<br/>
In addition, Mr. Young wants the students in each row arranged so that heights decrease from left to right. Also, student heights should decrease from the back to the front. Thinking about it, Mr. Young sees that for the 12-student example, there are at least two ways to arrange the students (with 1 as the tallest etc.): <br/>
<pre> 1  2  3  4  5     1  5  8 11 12
<br/> 6  7  8           2  6  9
<br/> 9 10 11           3  7 10
<br/>12                 4</pre>
<br/>
Mr. Young wonders how many different arrangements of the students there might be for a given arrangement of rows. He tries counting by hand starting with rows of 3, 2 and 1 and counts 16 arrangements: <br/>
<pre>123 123 124 124 125 125 126 126 134 134 135 135 136 136 145 146
<br/>45  46  35  36  34  36  34  35  25  26  24  26  24  25  26  25
<br/>6   5   6   5   6   4   5   4   6   5   6   4   5   4   3   3</pre>
<br/>
Mr. Young sees that counting by hand is not going to be very effective for any reasonable number of students so he asks you to help out by writing a computer program to determine the number of different arrangements of students for a given set of rows.</div>
<p>杨先生要给他的学生们拍照片。首先，站队状况是确定的，若第i行站了a[i]个人，则有a[1] ≥ a[2] ≥ ... ≥ a[n]，所有的行都是靠左对齐的。并且，在同一行和同一列里面，从左到右或者从上到下身高都是递减的。现在所有学生的身高都不相同，学生数不超过30个，行数不超过5。你需要求出所有可能的排队方法的总数。</p></div>

# Input

<div class="content"><div class="ptx" lang="en-US">The input for each problem instance will consist of two lines. The first line gives the number of rows, k, as a decimal integer. The second line contains the lengths of the rows from back to front (n1, n2,..., nk) as decimal integers separated by a single space. The problem set ends with a line with a row count of 0. There will never be more than 5 rows and the total number of students, N, (sum of the row lengths) will be at most 30.</div></div>

# Output

<div class="content"><div class="ptx" lang="en-US">The output for each problem instance shall be the number of arrangements of the N students into the given rows so that the heights decrease along each row from left to right and along each column from back to front as a decimal integer. (Assume all heights are distinct.) The result of each problem instance should be on a separate line. The input data will be chosen so that the result will always fit in an unsigned 32 bit integer.</div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
30<br/>
5<br/>
1 1 1 1 1<br/>
3<br/>
3 2 1<br/>
4<br/>
5 3 3 1<br/>
5<br/>
6 5 4 3 2<br/>
2<br/>
15 15<br/>
0<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
1<br/>
16<br/>
4158<br/>
141892608<br/>
9694845<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

