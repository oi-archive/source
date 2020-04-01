
# Description

<div class="content"><div>
<div>邪教喜欢在各种各样空间内跳。现在，邪教来到了一个二维平面。</div>
<div>在这个平面内，如果邪教当前跳到了(x,y)，那么他下一步可以选择跳到以下4个点：</div>
<div>(x-1,y),(x+1,y),(x,y-1),(x,y+1)。</div>
<div>而每当邪教到达一个点，他需要耗费一些体力，</div>
<div>假设到达(x,y)需要耗费的体力用C(x,y)表示。</div>
<div>对于C(x,y)，有以下几个性质：</div>
<div>1、若x=0或者y=0，则C(x,y)=1。</div>
<div>2、若x&gt;0且y&gt;0，则C(x,y)=C(x,y-1)+C(x-1,y)。</div>
<div>3、若x&lt;0且y&lt;0，则C(x,y)=无穷大。</div>
<div>现在，邪教想知道从(0,0)出发到(N,M)，最少花费多少体力</div>
<div>到达(0,0)点花费的体力也需要被算入）。</div>
<div>由于答案可能很大，只需要输出答案对10^9+7取模的结果。</div>
</div></div>

# Input

<div class="content"><div>读入两个整数 N ，M，表示邪教想到达的点。  </div>
<div>0&lt;=N, M&lt;=10^12   ，N*M&lt;=10^12</div></div>

# Output

<div class="content"><p><span style="line-height: 19px; font-size: 12pt;">输出仅一个整数，表示邪教需要花费的最小体力对</span><span style="line-height: 19px; font-size: 12pt;"> 10^9+7</span><span style="line-height: 19px; font-size: 12pt;">取模的结果。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">1  2</span></div>

# Sample Output

<div class="content"><span class="sampledata">6 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

