
# Description

<div class="content"><div>Forced by students&#39; parents, ZCC&#39;s teacher GPS has to open the scoreboard of the students. But this will bring many problems. So GPS intends only to open the first k ranklists of the tests. In order to avoid the arrogancy and the abandonment, GPS wants to make the difference between the highest ranking sum and the lowest ranking sum as small as possible.</div>
<div>At the same time, in order to reflect that each student is different, GPS defines the Progress Index.Progress Index exists between two exams. For two adjacent examinations, define NewRank as the ranking of the latter test, OldRank as the ranking of the formal one, and n as the number of students in the class.</div>
<div></div>
<div>ProgressIndex=</div>
<div>   0,if NewRank=OldRank</div>
<div>   OldRank-NewRank-max(OldRank,NewRank)/n,if NewRank&gt;OldRank</div>
<div>   OldRank-NewRank+max(OldRank,NewRank)/n,if NewRank&lt;OldRank</div>
<div></div>
<div>If there are two Pogress Indexs in different tests have the same absolute value or there are two Pogress Indexs in the same test have the same value, GPS will be unhappy, he thinks it violated the differences between students. GPS wants to know if this situation can keep to the end of exactly n exams. Because this problem is too hard so GPS only ask you to give the answers when n&lt;=100.</div>
<div>(Note: No two students can have the same rank in a test, the ranks will be 1..n)</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>There are multiple test cases end with EOF(no more than 10 test cases).</div>
<div>Each test case contain a line of two integers n,k indicating the number of students and the number of tests in the first question.(2&lt;=n&lt;=10000,1&lt;=k&lt;=n,n*k&lt;=10000)</div>
</div>
<p></p></div>

# Output

<div class="content"><div>
<div>For each test case:</div>
<div>The first question: The first line contain an integer indicating the smallest difference between the highest ranking sum and the lowest ranking sum. Next n lines each line contain k integers, the i+1-th line indicating the ranks of the student i.</div>
<div>The second question: The first line contain &#34;Yes&#34; or &#34;No&#34;(without quotes) indicating if the situation can keep to the end of exactly n exams. If the answer is &#34;Yes&#34; and n&lt;=100 then next n lines each line contain n integers, the i+1-th line indicating the ranks of the student i.</div>
<div>If there are multiple solutions, output any.</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
4 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1:<br/>
0<br/>
1 2 3<br/>
2 3 1<br/>
3 1 2<br/>
No<br/>
Case #2:<br/>
0<br/>
1 4<br/>
2 3<br/>
3 2<br/>
4 1<br/>
Yes<br/>
1 2 4 1<br/>
2 1 3 2<br/>
3 4 2 3<br/>
4 3 1 4</span></div>

# Hint

<div class="content"><p></p><p>请不要提交，期待SPJ</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 镇海中学">By 镇海中学</a></p></div>

