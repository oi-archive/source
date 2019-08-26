
# Description

<div class="content"><div>Farmer John owns Ncows with spots and N cows without spots. Having just completed a course in bovine</div>
<div> genetics, he is convinced that the spots on his cows are caused by mutations in the bovine genome.A</div>
<div>t great expense, Farmer John sequences the genomes of his cows. Each genome is a string of length Mb</div>
<div>uilt from the four characters A, C, G, and T. When he lines up the genomes of his cows, he gets a ta</div>
<div>ble like the following, shown here for N=3 and M=8:</div>
<div>Positions:    1 2 3 4 5 6 7 8</div>
<div></div>
<div>Spotty Cow 1: A A T C C C A T</div>
<div>Spotty Cow 2: A C T T G C A A</div>
<div>Spotty Cow 3: G G T C G C A A</div>
<div></div>
<div>Plain Cow 1:  A C T C C C A G</div>
<div>Plain Cow 2:  A C T C G C A T</div>
<div>Plain Cow 3:  A C T T C C A T</div>
<div>Looking carefully at this table, he surmises that the sequence from position 2 through position 5 is</div>
<div> sufficient to explain spottiness. That is, by looking at the characters in just these these positio</div>
<div>ns (that is, positions 2…5), Farmer John can predict which of his cows are spotty and which are not</div>
<div>. For example, if he sees the characters GTCG in these locations, he knows the cow must be spotty.Pl</div>
<div>ease help FJ find the length of the shortest sequence of positions that can explain spottiness.</div>
<div>
<div>
<div>FJ拥有有斑点的牛和没有斑点的牛。他刚刚完成了牛基因的一门课程，他相信牛身上的斑点是由牛的基因突变引起</div>
<div>的。FJ花费了巨大的代价，将他的牛的基因组排序。每个基因组都是长度为M的字符串。当他把牛的基因组排列起</div>
<div>来的时候，他得到了一个像下面这样的表格，这里显示的是N=3和M=8</div>
<div></div>
<div>位置:<span class="Apple-tab-span" style="white-space:pre">	</span> 1 2 3 4 5 6 7 8</div>
<div></div>
<div>斑点牛1: A A T C C C A T</div>
<div>斑点牛2: A C T T G C A A</div>
<div>斑点牛3: G G T C G C A A</div>
<div></div>
<div>普通牛1: A C T C C C A G</div>
<div>普通牛2: A C T C G C A T</div>
<div>普通牛3: A C T T C C A T</div>
<div></div>
<div>如果在某一段区间内，斑点牛和普通牛没有相同的基因段（即两组集合没有交集），那么FJ就能通过这段区间分辨两种牛。</div>
<div>请你帮FJ找出最短的满足条件的区间。</div>
<div></div>
<div>如样例</div>
<div>1~3 这段区间，斑点牛集合为{AAT,ACT,GGT},普通牛集合为{ACT,ACT,ACT}  斑点牛和普通牛都含有ACT这个字符串，不满足条件。</div>
<div>2~5 这段区间，斑点牛集合为{ATCC,CTTG,GTCG}，普通牛集合为{CTCC,CTCG,CTTC}  无公共字符串，满足条件。</div>
</div>
</div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N(1≤N≤500) and M (3≤M≤500). The next N lines each contain a str</div>
<div>ing of M characters; these describe the genomes of the spotty cows. The final Nlines describe the ge</div>
<div>nomes of the plain cows. No spotty cow has the same exact genome as a plain cow.</div>
<div>
<div>输入的第一行包含N(1≤N≤500)和M(3≤≤500)。</div>
<div>接下来的N行，每行一个由M个字符组成的字符串，描述了斑牛的基因组。</div>
<div>最后N行描述了普通奶牛的基因组。</div>
</div>
<p></p></div>

# Output

<div class="content"><div>Please print the length of the shortest sequence of positions that is sufficient to explain spottine</div>
<div>ss. A sequence of positions explains spottiness if the spottiness trait can be predicted with perfec</div>
<div>t accuracy among Farmer John&#39;s population of cows by looking at just those locations in the genome.</div>
<div>
<div>输出仅一行，满足条件的最短区间的长度。</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 8<br/>
AATCCCAT<br/>
ACTTGCAA<br/>
GGTCGCAA<br/>
ACTCCCAG<br/>
ACTCGCAT<br/>
ACTTCCAT<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

