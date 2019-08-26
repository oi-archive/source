
# Description

<div class="content"><div>从前有张图。图里n个顶点两两之间有N^2种最小割。告诉你这N^2个最小割。还原出这张图。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行一个正整数n，表示图的顶点数。</div>
<div>接下来n行每行N个非负整数，第i行第j列的数表示第i个点与第j个点的最小割。</div>
<div>点的编号从1开始。</div>
<div>Vi&lt;=10^5,n&lt;=100</div>
<div>保证vii=0。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>第一行一个整数m，表示图的边数。</div>
<div>接下来每行三个整数u,v,z。</div>
<div>表示从“到”存在一条权值为z的边。</div>
<div>l&lt;=u,v&lt;=N</div>
<div>0&lt;Z&lt;=10^9。</div>
<div>m&lt;=n*(n-l)/2。</div>
<div>请注意你给出的图要求联通。</div>
<div>如果无解请输出-l。</div>
<div>若有多解则输出任意一组解。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
0 2 2 <br/>
2 0 2<br/>
2 2 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
2 3 2<br/>
1 3 2</span></div>

# Hint

<div class="content"><p></p><p>请不要提交！</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

