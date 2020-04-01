
# Description

<div class="content"><div>给一棵N个节点的树，树的每个节点都有一个值xi，从树的根到每个叶子节点都是一条链，不妨假设其中一条链为a</div>
<div>0,a1,a2,a3 … an，其中a0为根，我们忽略这个根，则有序列a1,a2,a3…an。我们将每个序列看成一个长度为n的</div>
<div>数组a[1..n]，数组中每个数都满足0≤a[i]+i≤n。我们按照如下的过程来遍历这个数组：</div>
<div>Counter &lt;--0</div>
<div>I&lt;--0</div>
<div>While I &lt; n</div>
<div>I &lt;--I + 1</div>
<div>Counter &lt;--Counter + 1</div>
<div>If I = n Then Break</div>
<div>I &lt;--I + a[I]</div>
<div>EndWhile</div>
<div>不过作为一个牛逼的程序员，你可以在程序运行的过程中修改a[I]的值，但是有如下限制：</div>
<div>1、修改a[I]变为x，则需要使Counter 加上|a[I]-x|。</div>
<div>2、修改完的a[I]任然需要满足0≤a[I]+I≤n。</div>
<div></div>
<div>现在我们希望知道对于每个数上的链所对应的数组，运行完上述程序这个数组的最小Counter为多少(可以随意修改</div>
<div>a[I]的值，对于每一个链都可以修改不同的a[I])。将所有不同链所对应的最小Counter排序后，从小到大输出。</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个数N，表示树的节点数。</div>
<div>接下来N行，第i+1行描述第i个节点。每行有xi, mi, y1,y2…ym。</div>
<div>其中xi为节点i对应的值，mi表示i节点的儿子个数，y1~ym分别表示这mi个儿子的编号。</div>
<div>数据保证节点1的x1 = -1，且每条链都满足上述要求。</div>
<div>N≤1000000</div>
<p></p></div>

# Output

<div class="content"><div>输出K行，K为不同链数（也就是叶节点的数目）。</div>
<div>从小到大输出，表示不同链对应的最小Counter。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
-1 1 2<br/>
1 2 3 7<br/>
3 1 4<br/>
0 1 5<br/>
0 1 6<br/>
0 0<br/>
0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
3<br/>
<br/>
样例解释<br/>
样例有两个链 -1, 1, 3, 0, 0, 0 以及 -1, 1, 0。<br/>
对于第一个链，首先花费1的代价，将1修改为0，然后按上述程序运行，最后Counter=3。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

