
# Description

<div class="content"><div>所谓的考试，就一定有一道绝版题使得男人沉默女人流泪，而不有理有据的绝版题怎么称得上绝版呢？火车国一开</div>
<div>始只有一座城市，也就是1号城市。不过火车国的领土是在不断变化的，经常会新添加一个城市，那么小火车就会</div>
<div>用一条铁路把它和某个老城市连接起来。偶尔火车国会发生自然灾害，那么小火车就得找到一个合适的城市指挥赈</div>
<div>灾，这个城市满足所有城市到其距离乘以城市人口的和最小，如果有不止一个最小的城市时小火车会选择距离1号</div>
<div>城市最近的。当然火车国人口也是不断变化的，也就是说有时候某个城市的人口会改变。现在小火车请你告诉他每</div>
<div>次指挥赈灾应该选择的城市。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数m和t1，表示事件数量以及1号城市初始人口。</div>
<div>接下来m行每行先是一个整数type表示事件种类。</div>
<div>如果type=1表示新建一个城市，编号为当前城市最大编号加一</div>
<div>接下来读入两个整数u和t表示新建一条连接着城市u和新城市的铁路，新城市的人口为t。</div>
<div>如果type=2表示一个城市的人口发生了变化，读入两个整数u和t表示城市u的人口变成了t。</div>
<div>否则type一定为3，表示一次询问。</div>
<div>为了体现问题的在线性，小火车对输入顺序进行了加密，用lastans表示上一次的答案（初始为0），</div>
<div>则读入的u和t都需要按位异或lastans得到真正的操作。</div>
<div>m&lt;=300000，其中1操作和2操作个数不超过150000，保证任意城市人口数量不超过1000000且不低于1</div>
<p></p></div>

# Output

<div class="content"><div>对于每个询问输出一行一个整数表示答案。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 1<br/>
1 1 1<br/>
1 1 1<br/>
1 2 2<br/>
1 2 1<br/>
3<br/>
2 1 1<br/>
3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Newnode原创，本站版权所有">Newnode原创，本站版权所有</a></p></div>

