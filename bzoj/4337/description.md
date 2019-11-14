
# Description

<div class="content"><div>树是一种很常见的数据结构。</div>
<div>我们把N个点，N-1条边的连通无向图称为树。</div>
<div>若将某个点作为根，从根开始遍历，则其它的点都有一个前驱，这个树就成为有根树。</div>
<div>对于两个树T1和T2，如果能够把树T1的所有点重新标号，使得树T1和树T2完全相</div>
<div>同，那么这两个树是同构的。也就是说，它们具有相同的形态。</div>
<div>现在，给你M个有根树，请你把它们按同构关系分成若干个等价类。</div>
<p></p></div>

# Input

<div class="content"><div>第一行，一个整数M。</div>
<div>接下来M行，每行包含若干个整数，表示一个树。第一个整数N表示点数。接下来N</div>
<div>个整数，依次表示编号为1到N的每个点的父亲结点的编号。根节点父亲结点编号为0。</div>
<p></p></div>

# Output

<div class="content"><div>输出M行，每行一个整数，表示与每个树同构的树的最小编号。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 <br/>
4 0 1 1 2 <br/>
4 2 0 2 3 <br/>
4 0 1 1 1 <br/>
4 0 1 2 3 </span></div>

# Sample Output

<div class="content"><span class="sampledata">1 <br/>
1 <br/>
3 <br/>
1 <br/>
 </span></div>

# Hint

<div class="content"><p></p><div>【样例解释】 </div><br/>
<div>编号为1, 2, 4 的树是同构的。编号为3 的树只与它自身同构。 </div><br/>
<div>100% 的数据中，1 ≤ N, M ≤ 50。 </div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

