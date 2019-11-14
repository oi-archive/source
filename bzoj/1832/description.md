
# Description

<div class="content"><p>Y岛风景美丽宜人，气候温和，物产丰富。Y岛上有N个城市，有N-1条城市间的道路连接着它们。每一条道路都连接某两个城市。幸运的是，小可可通过这些道路可以走遍Y岛的所有城市。神奇的是，乘车经过每条道路所需要的费用都是一样的。小可可，小卡卡和小YY经常想聚会，每次聚会，他们都会选择一个城市，使得3个人到达这个城市的总费用最小。 由于他们计划中还会有很多次聚会，每次都选择一个地点是很烦人的事情，所以他们决定把这件事情交给你来完成。他们会提供给你地图以及若干次聚会前他们所处的位置，希望你为他们的每一次聚会选择一个合适的地点。</p></div>

# Input

<div class="content"><p>第一行两个正整数，N和M。分别表示城市个数和聚会次数。后面有N-1行，每行用两个正整数A和B表示编号为A和编号为B的城市之间有一条路。城市的编号是从1到N的。再后面有M行，每行用三个正整数表示一次聚会的情况：小可可所在的城市编号，小卡卡所在的城市编号以及小YY所在的城市编号。</p></div>

# Output

<div class="content"><p>一共有M行，每行两个数Pos和Cost，用一个空格隔开。表示第i次聚会的地点选择在编号为Pos的城市，总共的费用是经过Cost条道路所花费的费用。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 4<br/>
1 2<br/>
2 3<br/>
2 4<br/>
4 5<br/>
5 6<br/>
4 5 6<br/>
6 3 1<br/>
2 4 4<br/>
6 6 6<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5 2<br/>
2 5<br/>
4 1<br/>
6 0<br/>
<br/>
数据范围：<br/>
100%的数据中，N&lt;=500000，M&lt;=500000。<br/>
40%的数据中N&lt;=2000，M&lt;=2000。<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day1">Day1</a></p></div>

