
# Description

<div class="content"><div>一颗树n个点，n-1条边，经过每条边都要花费一定的时间，任意两个点都是联通的。</div>
<div>有K个人（分布在K个不同的点）要集中到一个点举行聚会。</div>
<div>聚会结束后需要一辆车从举行聚会的这点出发，把这K个人分别送回去。</div>
<div>请你回答，对于i=1~n，如果在第i个点举行聚会，司机最少需要多少时间把K个人都送回家。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个数，n，K。</div>
<div>接下来n-1行，每行三个数，x，y，z表示x到y之间有一条需要花费z时间的边。</div>
<div>接下来K行，每行一个数，表示K个人的分布。</div>
<p></p></div>

# Output

<div class="content"><div>输出n个数，第i行的数表示：如果在第i个点举行聚会，司机需要的最少时间。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 2<br/>
1 2 4<br/>
1 3 1<br/>
2 5 1<br/>
2 4 2<br/>
4 7 3<br/>
4 6 2<br/>
3<br/>
7</span></div>

# Sample Output

<div class="content"><span class="sampledata">11<br/>
15<br/>
10<br/>
13<br/>
16<br/>
15<br/>
10</span></div>

# Hint

<div class="content"><p></p><div>【数据规模】</div><br/>
<div>K &lt;= N &lt;= 500000</div><br/>
<div>1 &lt;= x,y &lt;= N, 1 &lt;= z &lt;= 1000000</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

