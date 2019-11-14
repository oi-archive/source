
# Description

<div class="content"><div>给定一个n个点、m条边的带权无向图，其中有s个点是加油站。</div>
<div>每辆车都有一个油量上限b，即每次行走距离不能超过b，但在加油站可以补满。</div>
<div>q次询问，每次给出x,y,b，表示出发点是x，终点是y，油量上限为b，且保证x点和y点都是加油站，请回答能否从x走到y。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含三个正整数n,s,m(2&lt;=s&lt;=n&lt;=200000,1&lt;=m&lt;=200000)，表示点数、加油站数和边数。</div>
<div>第二行包含s个互不相同的正整数c[1],c[2],...c[s](1&lt;=c[i]&lt;=n)，表示每个加油站。</div>
<div>接下来m行，每行三个正整数u[i],v[i],d[i](1&lt;=u[i],v[i]&lt;=n,u[i]!=v[i],1&lt;=d[i]&lt;=10000)，表示u[i]和v[i]之间有一条长度为d[i]的双向边。</div>
<div>接下来一行包含一个正整数q(1&lt;=q&lt;=200000)，表示询问数。</div>
<div>接下来q行，每行包含三个正整数x[i],y[i],b[i](1&lt;=x[i],y[i]&lt;=n,x[i]!=y[i],1&lt;=b[i]&lt;=2*10^9)，表示一个询问。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出q行。第i行输出第i个询问的答案，如果可行，则输出TAK，否则输出NIE。</div>
<div>
<div></div>
<div></div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 4 5<br/>
1 5 2 6<br/>
1 3 1<br/>
2 3 2<br/>
3 4 3<br/>
4 5 5<br/>
6 4 5<br/>
4<br/>
1 2 4<br/>
2 6 9<br/>
1 5 9<br/>
6 5 8<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
TAK<br/>
TAK<br/>
NIE</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris上传">鸣谢Claris上传</a></p></div>

