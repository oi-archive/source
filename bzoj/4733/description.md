
# Description

<div class="content"><div>mjy至上主义者dls今天心情很好，准备给mjy准备一个圣诞礼物。他购买了一个圣诞树，这个圣诞树是一个有n个点</div>
<div>的树，点i有一个颜色c_i。dls觉得如果某种颜色太多就不好看了，所以最多会有5个点有相同的颜色。mjy收到了</div>
<div>礼物很高兴，但是她最近对计数问题很感兴趣，于是她有一些问题想要dls解决。每次mjy会关心三种不同的颜色a,</div>
<div>b,c，她想要知道这个圣诞树有多少个不同的联通子图满足里面颜色为a,b,c的点的个数分别为n_a,n_b,n_c。由于</div>
<div>数可能很大，输出关于对10^9+7取模的余数就可以了。dls当然轻松解决了这个问题，你虽然被喂了狗粮，但你也</div>
<div>想锻炼你的数据结构水平，你能解决这个问题吗？</div>
<div></div></div>

# Input

<div class="content"><div>第一行两个数n和Q，表示树的大小和询问的个数。</div>
<div>第二行n个数，其中第i个表示c_i，为第i个节点的颜色。</div>
<div>接下来n-1行，每行两个数a和b，表示点a和点b之间有一条边。</div>
<div>接下来Q行，其中每行有6个数a,n_a,b,n_b,c,n_c，表示如题目中所诉的询问。</div>
<div>n,Q &lt;= 100000</div>
<div></div></div>

# Output

<div class="content"><div>对每个询问输出答案。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
1 2 3 1 2<br/>
1 2<br/>
2 3 <br/>
3 4<br/>
4 5<br/>
1 1 2 1 3 1<br/>
1 0 2 1 3 1<br/>
1 1 2 1 3 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
1<br/>
2</span></div>

# Hint

<div class="content"><p></p><p> 数据如下:<a href="http://www.lydsy.com/JudgeOnline/upload/4733.rar">www.lydsy.com/JudgeOnline/upload/4733.rar</a></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2017年国家集训队清华集训题">2017年国家集训队清华集训题</a></p></div>

