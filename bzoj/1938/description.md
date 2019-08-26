
# Description

<div class="content">有一个长度为 N 的序列P 和两种操作，共 Q个： 
1.  给定 L, R, A, B，将第 L 到第 R 个之间的每个元素 Px 变成（（X-L+1）×A）mod B  。  
2.  给定 L, R，询问第 L 到第 R 个元素的和。 
数据规模：N≤10^9  ，Q≤50000  ，  A, B≤106
 </div>

# Input

<div class="content">The first line contains two integers N i Q (1 ≤ N ≤ 1 000 000 000) (1 ≤ Q ≤ 50 
000), number of boxes and number of queries.
The next Q lines contain information about the simulation.
If the line starts with 1, than it follows the format &#34;1 L R A B&#34; (1 ≤ L ≤ R ≤ N) (1 
≤ A, B ≤ 1 000 000), meaning that Aladin keyed in numbers L, R, A and B in the 
device and allowed the device to do its job.
If the line starts with 2, than it follows the format &#34;2 L R&#34; (1 ≤ L ≤ R ≤ N). 
Meaning that Aladin wonders how many stones in total are ther stones are in 
boxes labeled L to R (inclusive).</div>

# Output

<div class="content">For each query beginning with 2 output the answer to that particular query. 
Queries should be processed in the order they are given in the input.</div>

# Sample Input

<div class="content"><span class="sampledata">6 3<br/>
2 1 6<br/>
1 1 5 1 2<br/>
2 1 6<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
3</span></div>

# Hint

<div class="content"><p>The boxes start containing {0, 0, 0, 0, 0, 0}, 0 stones in total. <br/>
After that the device sets the stones to {1 mod 2, 2 mod 2, 3 mod 2, 4 mod 2, <br/>
5 mod 2, 0} = {1,0,1,0,1,0}, or 3 stones in total.</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=CONTEST #1 24.10.2009.">CONTEST #1 24.10.2009.</a></p></div>

