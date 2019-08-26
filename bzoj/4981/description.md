
# Description

<div class="content"><div>sl又做白日梦了。他梦到若干年后的一天，他成为了地球最高统治者。地球上共有n个城市，被n条双向公路连成一</div>
<div>个环，第i条公路连接i-1号城市和i号城市（第一条连接n号城市和1号城市），第i条公路的长度为d[i]。sl曾受到</div>
<div>食堂饭菜的摧残，而且他认为食堂饭菜之所以这么难吃，是因为大家可以在外面吃到美味的饭菜，突出了食堂饭菜</div>
<div>的难吃。所以他决定在这n个城市中建一个公共食堂，所有人都只能吃这个食堂里的饭菜。假设食堂建在i号城市，</div>
<div>那么j号城市需要将饭菜从i号城市运到j号城市，设从i到j的两条路径长度分别为l1,l2，j号城市对饭菜的需求为w</div>
<div>[j]，运费则为l1*l2*w[j]。sl会选一个让总运费最少的城市建食堂，如果有多个，他会等概率选一个。1～n-1号</div>
<div>城市的w已经知道了，但n号城市不太支持sl的统治，所以sl只知道它的w在实数区间[a,b]内等概率分布。所以他想</div>
<div>知道他在每个城市建食堂的概率是多少。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行三个正整数n、a、b。</div>
<div>接下来n-1行每行一个正实数，为w[1]到w[n-1]。</div>
<div>接下来n行每行一个正实数，为d[1]到d[n]。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>n行，每行一个实数，第i行的实数为在i号城市建食堂的概率。</div>
<div>绝对误差在0.001以内为正确。</div>
<div>n≤100000,a≤b≤10000,w[i]≤10000,d[i]≤10</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 1 100<br/>
50<br/>
25<br/>
25<br/>
50<br/>
1<br/>
2<br/>
3<br/>
2<br/>
1</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.090<br/>
0.000<br/>
0.000<br/>
0.090<br/>
0.821</span></div>

# Hint

<div class="content"><p></p><p> 请不要提交！</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

