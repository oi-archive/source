
# Description

<div class="content"><div>有一天，tangjz造了一个Hash函数：</div>
<div>unsigned int Hash(unsigned int v){</div>
<div>    unsigned int t = v;</div>
<div>    t = t + (t &lt;&lt; 10);</div>
<div>    t = t ^ (t &gt;&gt; 6);</div>
<div>    t = t + (t &lt;&lt; 3);</div>
<div>    t = t ^ (t &gt;&gt; 11);</div>
<div>    t = t + (t &lt;&lt; 16);</div>
<div>    return t;</div>
<div>}</div>
<div><img src="/source/bzoj/4917/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwNi9waWNBLmpwZw==.jpg" width="720" height="247" alt=""/></div>
<div>小Q发现这个函数非常不靠谱，对于任意的t，他可以随手构出个数字v使得Hash(v)=t。</div>
<div>小Q现在想考考你，他将给出Q个t，你需要构造出满足条件的v。</div></div>

# Input

<div class="content"><div>第一行包含一个正整数Q(1&lt;=Q&lt;=100000)，表示询问的个数。</div>
<div>接下来Q行，每行一个整数t(0&lt;=t&lt;2^32)，表示询问的t。</div>
<div>输入数据保证对于每个t至少存在一组解。</div></div>

# Output

<div class="content"><div>对于每组数据输出一行一个整数，即合法的v，若有多组可行解，输出任意一组。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
614278301<br/>
1228622139<br/>
1841720774<br/>
2457244278</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
3<br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本Oj付费获得">本Oj付费获得</a></p></div>

