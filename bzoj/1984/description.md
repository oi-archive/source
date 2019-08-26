
# Description

<div class="content"><p>毛毛虫经过及时的变形，最终逃过的一劫，离开了菜妈的菜园。 毛毛虫经过千山万水，历尽千辛万苦，最后来到了小小的绍兴一中的校园里。爬啊爬~爬啊爬~~毛毛虫爬到了一颗小小的“毛景树”下面，发现树上长着他最爱吃的毛毛果~~~ “毛景树”上有N个节点和N-1条树枝，但节点上是没有毛毛果的，毛毛果都是长在树枝上的。但是这棵“毛景树”有着神奇的魔力，他能改变树枝上毛毛果的个数： 	Change k w：将第k条树枝上毛毛果的个数改变为w个。 	Cover u v w：将节点u与节点v之间的树枝上毛毛果的个数都改变为w个。 	Add u v w：将节点u与节点v之间的树枝上毛毛果的个数都增加w个。 由于毛毛虫很贪，于是他会有如下询问： 	Max u v：询问节点u与节点v之间树枝上毛毛果个数最多有多少个。</p></div>

# Input

<div class="content"><p>第一行一个正整数N。 接下来N-1行，每行三个正整数Ui，Vi和Wi，第i+1行描述第i条树枝。表示第i条树枝连接节点Ui和节点Vi，树枝上有Wi个毛毛果。 接下来是操作和询问，以“Stop”结束。</p></div>

# Output

<div class="content"><p>对于毛毛虫的每个询问操作，输出一个答案。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 2 8<br/>
1 3 7<br/>
3 4 9<br/>
Max 2 4<br/>
Cover 2 4 5<br/>
Add 1 4 10<br/>
Change 1 16<br/>
Max 2 4<br/>
Stop<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">9<br/>
16<br/>
<br/>
【Data Range】<br/>
1&lt;=N&lt;=100,000，操作+询问数目不超过100,000。<br/>
保证在任意时刻，所有树枝上毛毛果的个数都不会超过10^9个。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

