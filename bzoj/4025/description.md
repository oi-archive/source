
# Description

<div class="content"><div>神犇有一个n个节点的图。因为神犇是神犇，所以在T时间内一些边会出现后消失。神犇要求出每一时间段内这个图是否是二分图。这么简单的问题神犇当然会做了，于是他想考考你。</div>
<p></p></div>

# Input

<div class="content"><div>输入数据的第一行是三个整数n,m,T。</div>
<div>
<div>第2行到第m+1行，每行4个整数u,v,start,end。第i+1行的四个整数表示第i条边连接u,v两个点，这条边在start时刻出现，在第end时刻消失。</div>
</div>
<p></p></div>

# Output

<div class="content"><div>
<div>输出包含T行。在第i行中，如果第i时间段内这个图是二分图，那么输出“Yes”，否则输出“No”，不含引号。</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 3<br/>
1 2 0 2<br/>
2 3 0 3<br/>
1 3 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">Yes<br/>
No<br/>
Yes</span></div>

# Hint

<div class="content"><p></p><div>样例说明：</div><br/>
<div>0时刻，出现两条边1-2和2-3。</div><br/>
<div>第1时间段内，这个图是二分图，输出Yes。</div><br/>
<div>1时刻，出现一条边1-3。</div><br/>
<div>第2时间段内，这个图不是二分图，输出No。</div><br/>
<div>2时刻，1-2和1-3两条边消失。</div><br/>
<div>第3时间段内，只有一条边2-3，这个图是二分图，输出Yes。</div><br/>
<div></div><br/>
<div>数据范围：</div><br/>
<div>n&lt;=100000，m&lt;=200000，T&lt;=100000，1&lt;=u,v&lt;=n，0&lt;=start&lt;=end&lt;=T。</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

