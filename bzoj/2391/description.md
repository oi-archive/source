
# Description

<div class="content"><div> </div>
<div>Cirno闲着无事的时候喜欢冰冻青蛙。</div>
<div>Cirno每次从雾之湖中固定的n个结点中选出一些点构成一个简单多边形，Cirno运用自己的能力能将此多边形内所有青蛙冰冻。</div>
<div>雾之湖生活着m只青蛙,青蛙有大有小，所以每只青蛙的价值为一个不大于10000的正整数。</div>
<div>Cirno很想知道每次冻住的青蛙的价值总和。因为智商有限，Cirno将这个问题交给完美算术教室里的你。</div>
<div>因为爱护动物，所以每次冻结的青蛙会被放生。也就是说一只青蛙可以被多次统计。</div>
<div> </div></div>

# Input

<div class="content"><div> </div>
<div>第一行2个正整数 n,m。</div>
<div>以下n行，每行2个整数xi,yi,表示第i个结点的坐标。</div>
<div>再以下m行，每行3个整数xj,yj,vj，表示第j个青蛙的坐标和价值。</div>
<div>第n+m+1行一个整数q，表示有q组询问。</div>
<div>每组询问有2行，第一行一个整数s（3&lt;=s&lt;=n），表示简单多边形的结点数。第二行s个正整数，顺时针或逆时针给出多边形的结点的编号(1--n)</div>
<div> </div></div>

# Output

<div class="content"><div> </div>
<div>q行。</div>
<div>对于每个询问，每行输出一个整数表示冻结的青蛙的价值之和</div>
<div> </div></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
2 2<br/>
3 5<br/>
7 4<br/>
5 1<br/>
3 4 2<br/>
4 3 7<br/>
6 3 90<br/>
2<br/>
3<br/>
1 2 3<br/>
4<br/>
1 4 3 2<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">9<br/>
99<br/>
【</span></div>

# Hint

<div class="content"><p></p><p>数据范围】<br/><br/>
对于30%的数据，n,m&lt;=100; q&lt;=100<br/><br/>
对于60%的数据，n,m&lt;=100; q&lt;=10000<br/><br/>
对于100%的数据，n,m&lt;=1000; q&lt;=10000<br/><br/>
                -10000&lt;=x,y&lt;=10000; 0&lt;v&lt;=10000<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

