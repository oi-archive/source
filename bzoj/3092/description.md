
# Description

<div class="content"><div style="margin: 11.75pt -1.5pt 0pt 0cm; line-height: 17.25pt" align="left"></div>
<div style="margin: 10.5pt 19.85pt 0pt 0cm; line-height: 12.85pt"><span style="font-size: medium"><span style="color: black">Mr. B is the chief engineer in the Kingdom of FDUCS. Recently, the King asks Mr. B to develop a new plan of the road network in the country, since the existing one is so outdated that traffic jam often occurs. Unfortunately, Mr. B is now busy preparing for the ICPC World Finals. Therefore, He asks his friends Mr. G and Mr. M to help him finish that work. When Mr. B gets the solution from his friends, he realizes some problems: Mr. B forgot to specify the budget plan to Mr. G and Mr. M, thus the new solution contains too many new roads which the government cannot afford. After a precise calculation, Mr. B finds that he only need to delete exactly two roads in term of the financial facts (Of course, Mr. B will not delete more than two roads because he wants people in his country to have a convenient traffic). </span></span></div>
<div style="margin: 10.5pt 19.9pt 0pt 0cm; line-height: 12.75pt"><span style="font-size: medium"><span style="color: black">Can Mr. B delete two roads arbitrarily? The answer is negative. The King would like to take a travel on the new road system to review Mr. B&#39;s work. However, the King is so busy that he does not want to take travel with redundancy. That is, the King wants Mr. B to design a road system so that he can travel from the palace (in one city), pass each road exactly once, and then return to the palace. Moreover, during his travelling, the king must visit each city at least once. </span></span></div>
<div style="margin: 10.5pt 20.05pt 0pt 0cm; line-height: 12pt"><span style="font-size: medium"><span style="color: black">Mr. B feels hard to satisfy the King’s demand by deleting two roads from the original design. As an ICPC candidate with unlimited potential, can you help him? </span></span></div></div>

# Input

<div class="content"><div style="margin: 0cm 19.85pt 0pt 0cm; line-height: 12.65pt"><span style="font-size: medium"><span style="color: black">For each test case, the first line contains two integers, n and m (1 &lt;= n, m &lt;= 200,000), indicating the number of cities in the Kingdom and the roads in Mr. B&#39;s original plan. Following this are m lines, each contains a pair of integers a and b, denoting a bidirectional road between city a and city b (1 &lt;= a, b &lt;= n and a != b), the number of cities are counted from 1. No two roads connect the same pair of cities. </span></span></div></div>

# Output

<div class="content"><div style="margin: 10.5pt -1.1pt 0pt 0cm; line-height: 13.5pt" align="left"> </div>
<div style="margin: 0cm 19.8pt 0pt 0cm; line-height: 12.75pt"><span style="font-size: medium"><span style="color: black">For each test case, if Mr. B can satisfy the King’s requirement, then output “YES” in the first line, otherwise output “NO” (quotes for clarifying). If the answer is “YES”, output two integers X and Y (X &lt; Y) in the following line, specifying the two roads that Mr. B should delete from the original design. X and Y are the indexes of roads in the input, counting from 1. If there are more than one possible answer, output the one that makes the pair of (X, Y) lexicographically smallest. </span></span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4  6<br/>
1  2<br/>
1  3<br/>
1  4<br/>
2  3<br/>
2  4<br/>
3  4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: YES <br/>
1  6<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

