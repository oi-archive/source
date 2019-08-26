
# Description

<div class="content"><div><span style="font-size: 12pt">话说今年</span><span style="font-size: 12pt">HNOI</span><span style="font-size: 12pt">省队集训在一中进行，为此，</span><span style="font-size: 12pt">fmsoi</span><span style="font-size: 12pt">特意准备了一个巨大的电子广告牌，准备在上面写着“一中欢迎你”。</span></div>
<div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">但是这块牌子却出现了问题，经过神一般的小</span><span style="font-size: 12pt">Y</span><span style="font-size: 12pt">的修理后，终于好了，可是却恢复到了默认状态</span><span style="font-size: 12pt">---</span><span style="font-size: 12pt">没有显示任何字了。显然我们还要让它显示出“一中欢迎你”。</span></div>
<div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">众所周知，这类广告牌通常由若干像素点构成，我们考虑其中的一行，最开始每一行都是不发光的。</span></div>
<div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">每一行有</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">个像素点，将其标号</span><span style="font-size: 12pt">1..N</span><span style="font-size: 12pt">。现在给定</span><span style="font-size: 12pt">K</span><span style="font-size: 12pt">个点，要求这</span><span style="font-size: 12pt">K</span><span style="font-size: 12pt">个点发光，其余点不能发光。而这个电子广告牌的操作方式比较畸形，它有</span><span style="font-size: 12pt">L</span><span style="font-size: 12pt">种操作方法，第</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">种为</span><span style="font-size: 12pt">U­­<sub>i </sub></span><span style="font-size: 12pt">，即你能将任意长为</span><span style="font-size: 12pt">U­­<sub>i </sub></span><span style="font-size: 12pt">的连续一段的像素状态取反，即改变发光状态。</span></div>
<div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">现在你被分配了要处理好不同的</span><span style="font-size: 12pt">T</span><span style="font-size: 12pt">行，为了节省时间，对于每一行你都必须用最少的操作次数。</span></div></div>

# Input

<div class="content"><div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">第一行一个数</span><span style="font-size: 12pt">T</span><span style="font-size: 12pt">，表示数据组数</span></div>
<div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">然后是</span><span style="font-size: 12pt">T</span><span style="font-size: 12pt">组数据描述，对于每组数据：</span></div>
<div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">第一行为</span><span style="font-size: 12pt">N,K,L</span><span style="font-size: 12pt">，即一行有</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">个点，要求</span><span style="font-size: 12pt">K</span><span style="font-size: 12pt">个点必须发光，有</span><span style="font-size: 12pt">L</span><span style="font-size: 12pt">种操作方式。</span></div>
<div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">第二行</span><span style="font-size: 12pt">K</span><span style="font-size: 12pt">个数，表示要求发光的</span><span style="font-size: 12pt">K</span><span style="font-size: 12pt">个点。</span></div>
<div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">第三行</span><span style="font-size: 12pt">L</span><span style="font-size: 12pt">个数，表示</span><span style="font-size: 12pt">L</span><span style="font-size: 12pt">种操作。</span></div></div>

# Output

<div class="content"><div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">包含</span><span style="font-size: 12pt">T</span><span style="font-size: 12pt">个数，每个一行，即对于每一组数据的最少操作次数。</span></div>
<div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">如果无法完成，请输出</span><span style="font-size: 12pt">-1</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">       2<br/>
10 8 2<br/>
1 2 3 5 6 7 8 9<br/>
3 5<br/>
3 2 1<br/>
1 2<br/>
3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">       2<br/>
       -1<br/>
【数据规模】<br/>
       有20%较小的数据<br/>
       对于100%的数据:<br/>
       T&lt;=10<br/>
N&lt;=10000<br/>
K&lt;=10,L&lt;=100,1&lt;=Ui&lt;=N</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

