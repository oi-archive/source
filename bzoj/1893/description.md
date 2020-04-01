
# Description

<div class="content">Imagine that you are in a building with F floors (starting at floor 1, the lowest floor), and you have a large number of identical eggs, each in its own identical protective container. For each floor in the building, you want to know whether or not an egg dropped from that floor will break. If an egg breaks when dropped from floor i, then all eggs are guaranteed to break when dropped from any floor j ≥ i. Likewise, if an egg doesn&#39;t break when dropped from floor i, then all eggs are guaranteed to never break when dropped from any floor j ≤ i.
We can define Solvable(F, D, B) to be true if and only if there exists an algorithm to determine whether or not an egg will break when dropped from any floor of a building with F floors, with the following restrictions: you may drop a maximum of D eggs (one at a time, from any floors of your choosing), and you may break a maximum of B eggs. You can assume you have at least D eggs in your possession.
</div>

# Input

<div class="content">The first line of input gives the number of cases, N. N test cases follow. Each case is a line formatted as:
F D B
Solvable(F, D, B) is guaranteed to be true for all input cases.
</div>

# Output

<div class="content">For each test case, output one line containing &#34;Case #x: &#34; followed by three space-separated integers: Fmax, Dmin, and Bmin. 
The definitions are as follows:
1.	Fmax is defined as the largest value of F&#39; such that Solvable(F&#39;, D, B) is true, or -1 if this value would be greater than or equal to 232 .(In other words, Fmax = -1 if and only if Solvable(232, D, B) is true.)
2.	Dmin is defined as the smallest value of D&#39; such that Solvable(F, D&#39;, B) is true.
3.	Bmin is defined as the smallest value of B&#39; such that Solvable(F, D, B&#39;) is true.

Limits
1 ≤ N ≤ 100. 
Small dataset
1 ≤ F ≤ 100,
1 ≤ D ≤ 100,
1 ≤ B ≤ 100. 
Large dataset
1 ≤ F ≤ 2000000000,
1 ≤ D ≤ 2000000000,
1 ≤ B ≤ 2000000000. 
</div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3 3 3<br/>
7 5 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1: 7 2 1<br/>
Case #2: 25 3 2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

