
# Description

<div class="content"><div>
<div>人的脑海中可以看做是2N? 2N的矩阵，操心术可以占领其中的单元格进行操控，每个单元格有一个重要度Wij。操</div>
<div>心术刚进入大脑时由两股力量组成一股位于(1,N)，一股位于(1, N+ 1)。当一股力量位于一个点时，可以操控视线</div>
<div>上的所有点，一个点只能操控一次。你可以移动力量的位置K次。一心不能二用，你一次只可以移动其中一股力量</div>
<div>到其视线中任意一点。视线的范围为力量所在点的两条斜线上的任意一个除自己以外其它点，特别的，如果斜线上</div>
<div>有另一股力量，则无法看到那股力量及其后面的所有格。</div>
</div>
<div><img src="/source/bzoj/4187/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMy8xMS5naWY=.gif" width="587" height="221" alt=""/></div>
<div>你要使得最后控制的单元格的重要度之和尽量大</div></div>

# Input

<div class="content"><div>第一行两个数N,K</div>
<div>第二行到第2N + 1行，每行2N个数，表示重要度。</div>
<div>N≤ 11; K ≤ 100 ,-10^6 ≤ Wij ≤ 10^6</div>
<div></div></div>

# Output

<div class="content"><p>第一行输出一个数，表示正好经过</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 1<br/>
0 -9 -4 0<br/>
0 1 1 0<br/>
1 0 0 1<br/>
0 0 6 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

