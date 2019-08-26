
# Description

<div class="content"><div><span style="font-size: 12pt">在一个没有冬马的世界里，经历了学园祭后的春希着急着想要见到心爱的雪菜。然而在排队想见雪菜的</span><span style="font-size: 12pt">fans</span><span style="font-size: 12pt">太多了，春希一时半会凑不到雪菜面前。</span></div>
<div><span style="font-size: 12pt">作为高帅富，这样的问题怎么能难倒春希？春希从武也手中拿到了取自金闪闪宝库里的多啦</span><span style="font-size: 12pt">A</span><span style="font-size: 12pt">梦的传话筒，并且给每一个排队的</span><span style="font-size: 12pt">fans</span><span style="font-size: 12pt">都发了一个传话筒。</span></div>
<div><span style="font-size: 12pt">于是现在有</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">个人排成一列，第一个人是雪菜，后面</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">个人是雪菜的</span><span style="font-size: 12pt">fans</span><span style="font-size: 12pt">。第</span><span style="font-size: 12pt">I</span><span style="font-size: 12pt">个</span><span style="font-size: 12pt">fan</span><span style="font-size: 12pt">能在他的左侧中选一个距离不超过</span><span style="font-size: 12pt">L</span><span style="font-size: 12pt">的人发出频率在</span><span style="font-size: 12pt">[xi,yi]</span><span style="font-size: 12pt">的音波，并且第</span><span style="font-size: 12pt">I</span><span style="font-size: 12pt">个</span><span style="font-size: 12pt">fan</span><span style="font-size: 12pt">也能接受频率在</span><span style="font-size: 12pt">[xi,yi]</span><span style="font-size: 12pt">的音波。特别的，雪菜能接受所有频率的音波。</span></div>
<div><span style="font-size: 12pt">春希有些话想通过传话筒告诉雪菜，他想选择一个人作为传话的起始点，但不知道选谁比较好，作为春希的好友的你，能告诉他答案吗？</span></div>
<div><span style="font-size: 12pt">传话的具体解释：第</span><span style="font-size: 12pt">I</span><span style="font-size: 12pt">个人能选择其左边的距离不超过</span><span style="font-size: 12pt">L</span><span style="font-size: 12pt">的一个人</span><span style="font-size: 12pt">J</span><span style="font-size: 12pt">，只要双方对应的区间有交集，那么第</span><span style="font-size: 12pt">I</span><span style="font-size: 12pt">个人就能将信息传达给</span><span style="font-size: 12pt">J</span><span style="font-size: 12pt">。然后</span><span style="font-size: 12pt">J</span><span style="font-size: 12pt">又可以继续找下一个人传达信息。传达一次信息要</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">单位时间。</span></div></div>

# Input

<div class="content"><div style="text-indent: 24pt" align="left"><span style="font-size: 12pt">第一行两个正整数</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">、L</span><span style="font-size: 12pt">。接下来</span><span style="font-size: 12pt">N-</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">行，第</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">行包含了三个正整数xi</span><i><span style="font-size: 12pt">、</span></i><span style="font-size: 12pt">yi</span><i><span style="font-size: 12pt">、</span></i><span style="font-size: 12pt">li</span><span style="font-size: 12pt">，其中</span><span style="font-size: 12pt">l</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">表示第</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">个人距离雪菜有l</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">的距离</span><span style="font-size: 12pt">，满足</span><span style="font-size: 12pt">l</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">严格递增。</span></div></div>

# Output

<div class="content"><div style="margin: 13pt 0cm"> </div>
<div style="text-indent: 24pt" align="left"><span style="font-size: 12pt">总共</span><span style="font-size: 12pt">N</span><i><span style="font-size: 12pt">-</span></i><span style="font-size: 12pt">1</span><span style="font-size: 12pt">行，每行一个数分别表示</span><span style="font-size: 12pt">2</span><span style="font-size: 12pt">到</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">号fan至少需要多少单位时间，雪菜才能收到信息，如果无法传到雪菜则输出</span><span style="font-size: 12pt">-1</span><span style="font-size: 12pt">。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 1<br/>
1 2 1<br/>
2 3 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
【数据规模和约定】<br/>
30%的数据满足N &lt;=20000; <br/>
100%的数据满足2 &lt;=N&lt;= 2.5*10^5、0&lt;=xi，yi，li&lt;=2*10^9，1&lt;=L&lt;=2*10^9,xi&lt;=yi． </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

