
# Description

<div class="content"><div>
<div>给出一棵n个点、以1为根的有根树，点有点权。要求支持如下两种操作：</div>
<div>M x y：将点x的点权改为y；</div>
<div>Q x：求以x为根的子树的最大连通子块和。</div>
<div>其中，一棵子树的最大连通子块和指的是：该子树所有子连通块的点权和中的最大值</div>
<div>（本题中子连通块包括空连通块，点权和为0）。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数n、m，表示树的点数以及操作的数目。</div>
<div>第二行n个整数，第i个整数w_i表示第i个点的点权。</div>
<div>接下来的n-1行，每行两个整数x、y，表示x和y之间有一条边相连。</div>
<div>接下来的m行，每行输入一个操作，含义如题目所述。保证操作为M x y或Q x之一。</div>
<div>1≤n,m≤200000 ，任意时刻 |w_i|≤10^9 。</div>
<p></p></div>

# Output

<div class="content"><div>对于每个Q操作输出一行一个整数，表示询问子树的最大连通子块和。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4<br/>
3 -2 0 3 -1<br/>
1 2<br/>
1 3<br/>
4 2<br/>
2 5<br/>
Q 1<br/>
M 4 1<br/>
Q 1<br/>
Q 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
3<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=CQzhangyu&amp;GXZlegend原创，本OJ版权所有，翻版必究">CQzhangyu&amp;GXZlegend原创，本OJ版权所有，翻版必究</a></p></div>

