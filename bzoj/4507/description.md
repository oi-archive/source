
# Description

<div class="content"><div>农夫约翰在管理他的农场的各个方面都相当可靠，除了一条：他总是不能及时地割草。在第1天，他从位置（x1，y</div>
<div>1）开始，在第d天时，他沿着直线行走到位置（xd，yd），约翰总是在他农场的2D地图上水平或垂直移动;即xd = </div>
<div>xd-1或yd = yd-1。在这连续的几天里，FJ会交替着走水平线和竖直线。可是FJ的割草的进度太慢了，一些草可能</div>
<div>会在他完成所有割草之前重新长出来。在第d天切割的草的任何部分将在第d + T天的时候重新出现，因此如果FJ割</div>
<div>草的路径穿过他至少T天以前割过草的路径，他将再次在同一地点割草。 为了努力改革他的可怜的割草战略，FJ想</div>
<div>计算这种情况发生的次数。请计算FJ的割草路径穿过草已经生长的早期区段的次数。你应该只计算“垂直”交叉，</div>
<div>定义为水平线段和垂直线段之间的公共点，包括两者的端点。</div>
<div></div>
<div></div></div>

# Input

<div class="content"><div>第一行输入包含N（2≤N≤100,000）和T（1≤T≤N，T是偶数）。</div>
<div>接下来的N行描述了在1...N天的割草机的位置。每行包含两个整数xi和yi（非负整数，每个最多1,000,000,000）。</div>
<div></div></div>

# Output

<div class="content"><p>请输出FJ重新切割在较早切割之后已经生长的草的点的数量。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">7 4<br/>
0 10<br/>
10 10<br/>
10 5<br/>
3 5<br/>
3 12<br/>
6 12<br/>
6 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
//FJ在第7天穿过了在第2天他曾经切割过的一段草地。其他交叉点不计数</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum 鸣谢g1n0st提供译文">Platinum 鸣谢g1n0st提供译文</a></p></div>

