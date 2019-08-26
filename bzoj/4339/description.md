
# Description

<div class="content"><div>
<div>小强和阿米巴是好朋友。连接北京和小强的家乡的是错综复杂的铁路网。一共有N个站点，站点之间有长短不一的</div>
<div>双向的铁路。小强每次回家的时候，会从所有的最短路中随机选择一条。阿米巴门前有一条铁路。他想在不改变北</div>
<div>京到小强的家乡的最短路的距离的前提下，给这个铁路网再添一条长度为K的单向 单向铁路，使得小强路过阿米巴</div>
<div>家门口的那条铁路的概率最大。请输出这个最大概率。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行是三个正整数N,M和K，表示站点的数量，铁路线的数量和新开的铁路线的长度。站点从1编号到N。北京是1</div>
<div>号点，小强的家乡是N号。接下来M行，每行三个正整数u,v,s表示有一条连接站点u和v的铁路线长度是s。这M行中</div>
<div>的第一行描述的是阿米巴家门口的铁路。两个点之间可能有多条铁路。也有可能u=v，即，有自环。你新修建的铁</div>
<div>路也可以和已有线路重合，也可以是自环。1和N之间一定是连通的。</div>
<div>3≤N≤100000，M≤400000，1≤s,K≤10000,保证无论如何加边图中任两点之间的最短路的数量都不超过2^16000.</div>
</div>
<div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>
<div>输出一行两个正整数A,B，表示从A向B修建一条单向铁路。你的修建方案得出的小强路过的概率和标准答案之间的</div>
<div>差距不超过10-6即可算对。</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 1<br/>
1 2 1<br/>
2 3 1<br/>
1 3 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 3<br/>
//添加边之后，一共有3条最短路，小强会路过阿米巴门前的概率由1/2变为2/3.</span></div>

# Hint

<div class="content"><p></p><div>尚无Spj，请谨慎提交!</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

