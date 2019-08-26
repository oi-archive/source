
# Description

<div class="content"><div>pupil喜欢给图的顶点染颜色。有一天，master想刁难他，于是给了他一个无重边和自环的无向图，并且对每个点</div>
<div>分别给了一个大小为2的颜色集合，pupil只能从这个集合中选一种颜色给这个点染色。master希望pupil的染色方</div>
<div>案使得没有两个有边相连的点被染了相同的颜色。现在pupil想知道，是否无论master的颜色集合是什么，他均有</div>
<div>办法按照要求染色。</div>
<div></div></div>

# Input

<div class="content"><div>输入包含多组数据。</div>
<div>第一行一个正整数T，表示数据组数。</div>
<div>之后每组数据第一行两个空格隔开的整数n,m表示这个无向图的点数和边数。</div>
<div>之后m行，每行两个空格隔开的正整数i,j表示图中的一条连接点i和点j的边。</div>
<div>图的节点从1开始标号。</div>
<div>1≤n≤10000 ，0≤m≤20000 ，1≤T≤10</div>
<div></div></div>

# Output

<div class="content"><div>对于每组数据，如果pupil无论如何均能染色，输出一行一个字符串YES，否则输出一行一个字符串NO。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
6 9<br/>
1 2<br/>
1 4<br/>
1 6<br/>
3 2<br/>
3 4<br/>
3 6<br/>
5 2<br/>
5 4<br/>
5 6<br/>
2 1<br/>
1 2<br/>
3 3<br/>
1 2<br/>
1 3<br/>
2 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">NO<br/>
YES<br/>
NO<br/>
对于第一组数据，如果第一个点和第二个点的集合为A,B ，第三个点和第四个点的集合为A,C ，第五个点和第六个<br/>
点的集合为B,C ，则奇数点至少使用了两种颜色，偶数点至少使用了两种颜色，因此至少有一个奇数点和一个偶数<br/>
点颜色相同。但每两个奇数点和每两个偶数点之间均有边，因此无法满足‘‘没有两个有边相连的点被染了相同的<br/>
颜色’’。<br/>
对于第二组数据，无论两个集合是什么，第一个点随便染它的集合中的其中一种颜色，第二个点染它的集合中某个<br/>
与第一个点不同的颜色即可。<br/>
对于第三组数据，如果三个点的集合均是A,B , 那么无法满足‘‘没有两个有边相连的点被染了相同的颜色’’</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢佚名上传">鸣谢佚名上传</a></p></div>

