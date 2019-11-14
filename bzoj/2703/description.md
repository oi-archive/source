
# Description

<div class="content"><div style="text-indent: 20.5pt"><span style="font-size: 12pt">有</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">个城市，被公路依次连成了一个环，小月想在这些城市中建一个玩具厂。城市和公路都被编号为</span><span style="font-size: 12pt">1..N</span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">号公路连接</span><span style="font-size: 12pt">i-1</span><span style="font-size: 12pt">号城市与</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">号城市（</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">号公路连接</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">号城市与</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">号城市），每个城市对玩具的需求为</span><span style="font-size: 12pt">wi</span><span style="font-size: 12pt">，每条公路的长度为</span><span style="font-size: 12pt">di</span><span style="font-size: 12pt">。当我们在第</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">号城市建玩具厂时，我们需要将玩具运输到其他城市（当然</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">城市除外）。设第</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">号城市到第</span><span style="font-size: 12pt">j</span><span style="font-size: 12pt">号城市的两条路径长度分别为</span><span style="font-size: 12pt">l1</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">l2</span><span style="font-size: 12pt">，则将玩具运输到第</span><span style="font-size: 12pt">j</span><span style="font-size: 12pt">号城市的费用为</span><span style="font-size: 12pt">l1*l2*wj</span><span style="font-size: 12pt">。总的运输费用为将玩具运到所有城市的运输费用的总和。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: 12pt">小月当然想要总的运输费用最少，所以他会选最优的城市建玩具厂，如果有多个最优的城市，小月会等概率的选取其中一个建玩具厂。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: 12pt">由于小月的调查工作没做好，我们只知道</span><span style="font-size: 12pt">1..N-1</span><span style="font-size: 12pt">号城市的</span><span style="font-size: 12pt">wi</span><span style="font-size: 12pt">，而</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">号城市的</span><span style="font-size: 12pt">wi</span><span style="font-size: 12pt">我们只知道它的取值范围</span><span style="font-size: 12pt">[a,b]</span><span style="font-size: 12pt">，我们假设</span><span style="font-size: 12pt">wi</span><span style="font-size: 12pt">的值在实数区间</span><span style="font-size: 12pt">[a,b]</span><span style="font-size: 12pt">上的概率是均匀分布的。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: 12pt">没办法，现在小月只好去进行第二次调查，于是我们想知道每个城市建玩具厂的概率是多少。</span></div></div>

# Input

<div class="content"><div style="text-indent: 20.5pt"><span style="font-size: 12pt">第一行有三个正整数</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">a</span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">b</span><span style="font-size: 12pt">。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: 12pt">接下来</span><span style="font-size: 12pt">N-1</span><span style="font-size: 12pt">行每行一个正实数，为</span><span style="font-size: 12pt">w[1]</span><span style="font-size: 12pt">到</span><span style="font-size: 12pt">w[N-1]</span><span style="font-size: 12pt">。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: 12pt">接下来</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">行每行一个正实数，为</span><span style="font-size: 12pt">d[1]</span><span style="font-size: 12pt">到</span><span style="font-size: 12pt">d[N]</span><span style="font-size: 12pt">。</span></div></div>

# Output

<div class="content"><div style="text-indent: 20.5pt"><span style="font-size: 12pt">一共有</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">行，每行一个实数，表示</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">到</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">号城市建玩具厂的概率，保留</span><span style="font-size: 12pt">3</span><span style="font-size: 12pt">位小数。</span></div></div>

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
1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.090<br/>
0.000<br/>
0.000<br/>
0.090<br/>
0.821<br/>
</span></div>

# Hint

<div class="content"><p></p><p>【样例说明】<br/><br/>
当w[5]&lt;18.75时，将在1或4号城市建玩具厂，当w[5]&gt;18.75时，将在5号城市建玩具厂，当w[5]=18.75时，将在1或4或5建玩具厂。<br/><br/>
【数据规模和约定】<br/><br/>
30%的数据中：N&lt;=1000。<br/><br/>
30%的数据中：a=b。<br/><br/>
100%的数据中：N&lt;=100000,a&lt;=b&lt;=10000,w[i]&lt;=10000,d[i]&lt;=10。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

