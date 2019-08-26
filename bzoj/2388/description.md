
# Description

<div class="content"><div align="center">OIVillage是一个风景秀美的乡村，为了更好的利用当地的旅游资源，吸引游客，推动经济发展，xkszltl决定修建了一条铁路将当地n个最著名的经典连接起来，让游客可以通过火车从铁路起点（1号景点）出发，依次游览每个景区。为了更好的评价这条铁路，xkszltl为每一个景区都哦赋予了一个美观度，而一条旅行路径的价值就是它所经过的景区的美观度之和。不过，随着天气与季节的变化，某些景点的美观度也会发生变化。</div>
<div style="text-indent: 21pt">xkszltl希望为每位旅客提供最佳的旅行指导，但是由于游客的时间有限，不一定能游览全部景区，然而他们也不希望旅途过于短暂，所以每个游客都希望能在某一个区间内的车站结束旅程，而xkszltl的任务就是为他们选择一个终点使得旅行线路的价值最大。可是当地的景点与前来观光的旅客实在是太多了，xkszltl无法及时完成任务，于是找到了准备虐杀NOI2011的你，希望你能帮助他完成这个艰巨的任务。</div></div>

# Input

<div class="content"><div style="text-indent: 21pt">第一行给出一个整数n，接下来一行给出n的景区的初始美观度。</div>
<div style="text-indent: 21pt">第三行给出一个整数m，接下来m行每行为一条指令：</div>
<div style="margin: 0cm 0cm 0pt 63pt; text-indent: -21pt"><span>1.<span style="font: 7pt &#39;Times New Roman&#39;">         </span></span>0 x y k：表示将x到y这段铁路边上的景区的美观度加上k；</div>
<div style="margin: 0cm 0cm 0pt 63pt; text-indent: -21pt"><span>2.<span style="font: 7pt &#39;Times New Roman&#39;">         </span></span>1 x y：表示有一名旅客想要在x到y这段（含x与y）中的某一站下车，你需要告诉他最大的旅行价值。</div></div>

# Output

<div class="content"><div style="text-indent: 21pt">对于每个询问，输出一个整数表示最大的旅行价值。</div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 8 -8 3 -7<br/>
3<br/>
1 1 5<br/>
0 1 3 6<br/>
1 2 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">9<br/>
22</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
Data Limit:<br/><br/>
对于20%的数据，n，m≤3000；<br/><br/>
对于40%的数据，n，m≤30000；<br/><br/>
对于50%的数据，n，m≤50000；<br/><br/>
另外20%的数据，n，m≤100000，修改操作≤20；<br/><br/>
对于100%的数据，n，m≤100000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

