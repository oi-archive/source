
# Description

<div class="content"><p><span style="font-size: medium">给一列数，要求支持操作： 1.修改某个数的值 2.读入l,r,k，询问在[l,r]内选不相交的不超过k个子段，最大的和是多少。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">The first line contains integer <span class="tex-span"><i>n</i></span> <span class="tex-span">(1 ≤ <i>n</i> ≤ 10<sup class="upper-index">5</sup>)</span>, showing how many numbers the sequence has. The next line contains <span class="tex-span"><i>n</i></span> integers <span class="tex-span"><i>a</i><sub class="lower-index">1</sub>, <i>a</i><sub class="lower-index">2</sub>, ..., <i>a</i><sub class="lower-index"><i>n</i></sub></span> <span class="tex-span">(|<i>a</i><sub class="lower-index"><i>i</i></sub>| ≤ 500)</span>. </span></p>
<p><span style="font-size: medium">The third line contains integer <span class="tex-span"><i>m</i></span> <span class="tex-span">(1 ≤ <i>m</i> ≤ 10<sup class="upper-index">5</sup>)</span> — the number of queries. The next <span class="tex-span"><i>m</i></span> lines contain the queries in the format, given in the statement.</span></p>
<p><span style="font-size: medium">All changing queries fit into limits: <span class="tex-span">1 ≤ <i>i</i> ≤ <i>n</i></span>, <span class="tex-span">|<i>val</i>| ≤ 500</span>.</span></p>
<p><span style="font-size: medium">All queries to count the maximum sum of at most <span class="tex-span"><i>k</i></span> non-intersecting subsegments fit into limits: <span class="tex-span">1 ≤ <i>l</i> ≤ <i>r</i> ≤ <i>n</i></span>, <span class="tex-span">1 ≤ <i>k</i> ≤ 20</span>. It is guaranteed that the number of the queries to count the maximum sum of at most <span class="tex-span"><i>k</i></span> non-intersecting subsegments doesn&#39;t exceed <span class="tex-span">10000</span>.</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">For each query to count the maximum sum of at most <span class="tex-span"><i>k</i></span> non-intersecting subsegments print the reply — the maximum sum. Print the answers to the queries in the order, in which the queries follow in the input.</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">9<br/>
9 -8 9 -1 -1 -1 9 -8 9<br/>
3<br/>
1 1 9 1<br/>
1 1 9 2<br/>
1 4 6 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">17<br/>
25<br/>
0</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">In the first query of the first example you can select a single pair <span class="tex-span">(1, 9)</span>. So the described sum will be 17.</span></p><br/>
<p><span style="font-size: medium">Look at the second query of the first example. How to choose two subsegments? (1, 3) and (7, 9)? Definitely not, the sum we could get from (1, 3) and (7, 9) is 20, against the optimal configuration (1, 7) and (9, 9) with 25.</span></p><br/>
<p><span style="font-size: medium">The answer to the third query is 0, we prefer select nothing if all of the numbers in the given interval are negative.</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By xiaodao">By xiaodao</a></p></div>

