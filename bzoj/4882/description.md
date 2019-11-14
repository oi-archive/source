
# Description

<div class="content"><div>小Q最近沉迷底层优化，他终于将他的MST模板优化到了很可怕的地步，所以他出了这道题来试验模板的速度。给定</div>
<div>一个n个点的带权无向连通图，点的编号从1到n，请求出这个图的最小生成树。为了避免输入数据过于庞大，数据</div>
<div>进行了压缩，解压方式可用下面这段代码解释：</div>
<div>void encode(int seed, int n){</div>
<div>    int x = seed;</div>
<div>    for(int i = 2; i &lt;= n; i++){</div>
<div>        x = x * 907 % 2333333;</div>
<div>        int T = x;</div>
<div>        for(int j = max(1, i - 5); j &lt;= i - 1; j++){</div>
<div>            x = x * 907 % 2333333;</div>
<div>            int w = T ^ x;</div>
<div>            add_edge(i, j, w);//在点i与点j之间添加一条边权为w的边</div>
<div>        }</div>
<div>    }</div>
<div>}</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含一个正整数T(1&lt;=T&lt;=50)，表示测试数据的组数。</div>
<div>每组数据只包含一行两个正整数n,seed(1&lt;=n&lt;=10^7,1&lt;=seed&lt;=2333332)，含义如题面所述。</div>
<div></div></div>

# Output

<div class="content"><div>对于每组数据，输出一行一个整数，即最小生成树的树边的权值之和。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
3010 2016<br/>
3 14159<br/>
31415 926</span></div>

# Sample Output

<div class="content"><span class="sampledata">750887251<br/>
3382896<br/>
9210525875</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获得">本OJ付费获得</a></p></div>

