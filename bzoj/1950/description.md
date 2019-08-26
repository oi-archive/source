
# Description

<div class="content">给 N个点N 条边的有向图。 
  要求添最小的边，使得点1 到达其他所有点的最短路长度不超过K。 </div>

# Input

<div class="content">The first line of input contains two integers N and K (2 ≤ N ≤ 500 000, 1 ≤ K ≤ 20 000) – the number of pages 
and the target maximum number of links to be followed. 
Each of the following N lines contains two different integers A and B (1 ≤ A, B ≤ N) meaning that the link on 
page A points to page B. 
 </div>

# Output

<div class="content">The first and only line of output should contain a single integer, the minimum number of additional links 
required to make the website K-reachable. </div>

# Sample Input

<div class="content"><span class="sampledata">14 4 <br/>
1 2 <br/>
2 3 <br/>
3 4 <br/>
4 5 <br/>
7 5 <br/>
5 6 <br/>
6 3 <br/>
8 10 <br/>
10 9 <br/>
9 8 <br/>
14 13 <br/>
13 12 <br/>
12 11 <br/>
11 14 </span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p>one possible solution is to add the links 1→7, 1→14 and 14→10</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

