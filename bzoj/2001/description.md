
# Description

<div class="content"><p>PS国是一个拥有诸多城市的大国，国王Louis为城市的交通建设可谓绞尽脑汁。Louis可以在某些城市之间修建道路，在不同的城市之间修建道路需要不同的花费。Louis希望建造最少的道路使得国内所有的城市连通。但是由于某些因素，城市之间修建道路需要的花费会随着时间而改变，Louis会不断得到某道路的修建代价改变的消息，他希望每得到一条消息后能立即知道使城市连通的最小花费总和， Louis决定求助于你来完成这个任务。</p></div>

# Input

<div class="content"><p>文件第一行包含三个整数N,M,Q，分别表示城市的数目，可以修建的道路个数，及收到的消息个数。 接下来M行，第i+1行有三个用空格隔开的整数Xi,Yi,Zi(1≤Xi,Yi≤n, 0≤Zi≤50000000)，表示在城市Xi与城市Yi之间修建道路的代价为Zi。接下来Q行，每行包含两个数k,d，表示输入的第k个道路的修建代价修改为d(即将Zk修改为d)。</p></div>

# Output

<div class="content"><p>输出包含Q行，第i行输出得知前i条消息后使城市连通的最小花费总和。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5 3<br/>
1 2 1<br/>
2 3 2<br/>
3 4 3<br/>
4 5 4<br/>
5 1 5<br/>
1 6<br/>
1 1<br/>
5 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">14<br/>
10<br/>
9<br/>
</span></div>

# Hint

<div class="content"><p></p><p>【数据规模】 对于20%的数据, n≤1000,m≤6000,Q≤6000。 有20%的数据，n≤1000,m≤50000,Q≤8000,修改后的代价不会比之前的代价低。 对于100%的数据, n≤20000,m≤50000,Q≤50000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

