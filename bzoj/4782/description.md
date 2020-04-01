
# Description

<div class="content"><div>Farmer John owns Ncows with spots and N cows without spots. Having just completed a course in bovine</div>
<div> genetics, he is convinced that the spots on his cows are caused by mutations in the bovine genome.A</div>
<div>t great expense, Farmer John sequences the genomes of his cows. Each genome is a string of length Mb</div>
<div>uilt from the four characters A, C, G, and T. When he lines up the genomes of his cows, he gets a ta</div>
<div>ble like the following, shown here for N=3:</div>
<div></div>
<div>Positions:    1 2 3 4 5 6 7 ... M</div>
<div></div>
<div>Spotty Cow 1: A A T C C C A ... T</div>
<div>Spotty Cow 2: G A T T G C A ... A</div>
<div>Spotty Cow 3: G G T C G C A ... A</div>
<div></div>
<div>Plain Cow 1:  A C T C C C A ... G</div>
<div>Plain Cow 2:  A G T T G C A ... T</div>
<div>Plain Cow 3:  A G T T C C A ... T</div>
<div></div>
<div>Looking carefully at this table, he surmises that positions 2 and 4 are sufficient to explain spotti</div>
<div>ness. That is, by looking at the characters in just these two positions, Farmer John can predict whi</div>
<div>ch of his cows are spotty and which are not (for example, if he sees G and C, the cow must be spotty</div>
<div>).Farmer John is convinced that spottiness can be explained not by just one or two positions in the </div>
<div>genome, but by looking at a set of three distinct positions. Please help him count the number of set</div>
<div>s of three distinct positions that can each explain spottiness.</div>
<div>
<div>给定n个A串和n个B串，长度均为m，求有多少三元组(x,y,z)，使得不存在一个A串a和一个B串b，使得</div>
<div>(a[x],a[y],a[z])=(b[x],b[y],b[z])</div>
<div>n≤500,m≤50</div>
</div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N(1≤N≤500) and M (3≤M≤50). The next N lines each contain a stri</div>
<div>ng of M characters; these describe the genomes of the spotty cows. The final Nlines describe the gen</div>
<div>omes of the plain cows.</div>
<p></p></div>

# Output

<div class="content"><div>Please count the number of sets of three distinct positions that can explain spottiness. A set of th</div>
<div>ree positions explains spottiness if the spottiness trait can be predicted with perfect accuracy amo</div>
<div>ng Farmer John&#39;s population of cows by looking at just those three locations in the genome.</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 8<br/>
AATCCCAT<br/>
GATTGCAA<br/>
GGTCGCAA<br/>
ACTCCCAG<br/>
ACTCGCAT<br/>
ACTTCCAT<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">22</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

