
# Description

<div class="content"><div>OItown周围有n个小村庄。村庄与村庄之间有公路，每一条公路连接两个村庄。因为这些村庄并不富裕，所以，当</div>
<div>初建公路时，这些公路只是恰好将这些村庄连通，也就是说要任意从一个村庄沿着公路走到另一个村庄的方式都是</div>
<div>唯一的。于是，有时两个很近的村庄之间要走很长的路。所以，村民们就希望能开通在这些公路上的公共交通路线</div>
<div>，方便大家的出行。巴士运营公司采纳了这个意见。同时，巴士公司认为这些巴士线路必须满足下述条件： </div>
<div>1． 每条巴士线路的起点和终点都在村庄内，巴士开行的线路都沿着公路； </div>
<div>2． 每条公路都要有巴士线路覆盖，这样村民们的出行就只需要换成巴士车就行了； </div>
<div>3． 每条公路只被一条巴士线路覆盖，且只被覆盖一次，否则巴士公司觉得在成本上不划算； </div>
<div>4． 巴士线路的总数应当最少，这样才能方便管理。例如，如果6个村庄之间的5条公路是这样的：</div>
<p> <img border="0" alt="" src="/source/bzoj/2027/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzIwMjcuanBn.jpg"/> </p>
<div>那么这样的3条巴士线路就能满足上面的条件：1-2-3，2-4，5-4-6。不过，居民们自然认为“巴士换乘”是不方便</div>
<div>的，因此他们希望从在一个村庄乘车去另一个村庄的路上换乘次数的最大值尽可能少。例如上面这个线路安排中，</div>
<div>从村庄1到村庄6需要换成2次，是最大的换乘次数。另一方面，巴士公司认为，一条公交线路越长意味着，如果巴</div>
<div>士车发生故障，因此而受影响耽误时间的乘客就越多。所以巴士公司希望，最长的一条线路尽可能短。所谓短，就</div>
<div>是途经的村庄少。现在，这个巴士线路设计的任务交给了参加SHTSC的你，你当然要同时考虑上面两方面的因素，</div>
<div>所以，你必须先计算出：(1)换乘次数的最大值的最小可能值(2)最长的巴士线路途经的村庄数的最小可能值。</div></div>

# Input

<div class="content"><div>输入数据的第一行是一个整数n，表示村庄的数目。</div>
<div>接下去每行有两个整数x、y，分别描述一条公路，表示村庄x、y之间有一条公路。</div>
<div>输入文件保证，每条公路只会被描述一次。</div></div>

# Output

<div class="content"><div>第一行是一个整数，表示巴士线路安排中包含的路线数。</div>
<div>第二行是一个整数，表示换乘次数的最大值的最小可能值。</div>
<div>第三行是一个整数，表示最长的巴士线路途经的村庄数的最小可能值。</div></div>

# Sample Input

<div class="content"><span class="sampledata">12<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 5<br/>
5 6<br/>
6 7<br/>
2 8<br/>
3 9<br/>
4 10<br/>
5 11<br/>
6 12<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
2<br/>
3<br/>
</span></div>

# Hint

<div class="content"><p></p><p>N &lt; = 10^5</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

