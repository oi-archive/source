
# Description

<div class="content"><div>
<div>
<div>Every day, Farmer John walks through his pasture to check on the well-being of each of his cows. Onh</div>
<div>is farm he has two breeds of cows, Holsteins and Guernseys. His HH Holsteins are conveniently number</div>
<div>ed 1…H, and his GG Guernseys are conveniently numbered 1…G (1≤H≤1000,1≤G≤1000). Each cowis loc</div>
<div>ated at a point in the 2D plane (not necessarily distinct).Farmer John starts his tour at Holstein 1</div>
<div>, and ends at Holstein HH. He wants to visit each cow along the way, and for convenience in maintain</div>
<div>ing his checklist of cows visited so far, he wants to visit the Holsteins and Guernseys in theorder </div>
<div>in which they are numbered. In the sequence of all H+GH+G cows he visits, the Holsteins numbered 1…</div>
<div>H should appear as a (not necessarily contiguous) subsequence, and likewise for the Guernseys. Other</div>
<div>wise stated, the sequence of all H+GH+G cows should be formed by interleaving the list of Holsteins </div>
<div>numbered 1…H with the list of Guernseys numbered 1…GWhen FJ moves from one cow to another cow trav</div>
<div>eling a distance of D, he expends D2 energy. Please help him determine the minimum amount ofenergy r</div>
<div>equired to visit all his cows according to a tour as described above.</div>
<div>有A、B两类点在一个二维平面上，A类的点有n个，B类的点有m个，要求从A类点的第1个开始走，走到第n个结束，</div>
<div>所有点必须有序（编号从小到大）但可以不连续地经过一次。</div>
<div>求在满足条件的情况下，最短的所经过的路径的欧几里得距离平方和是多少。</div>
</div>
<div></div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains H and G, separated by a space.</div>
<div>
<div>The next H lines contain the xx and yy coordinates of the HH Holsteins, and the next G lines after </div>
<div>that contain coordinates of the Guernseys. Each coordinate is an integer in the range 0…1000</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>Write a single line of output, giving the minimum energy required for FJ&#39;s tour of all the cows.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2<br/>
0 0<br/>
1 0<br/>
2 0<br/>
0 3<br/>
1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">20</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

