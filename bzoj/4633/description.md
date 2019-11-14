
# Description

<div class="content"><div>SHUXK 位于一个王国之中。这个王国由N个城市构成，城市之间连有双向的道路，通过每条道路都需要一定的时间</div>
<div>。SHUXK 发现这个王国有两个主要城市 A 和 B，这两个城市之间人员来往非常频繁，以致于经常会发生交通堵塞</div>
<div>。他想使用魔法来改善这个情况。他拥有一种“路径魔法”：一次选择一条从 A 城到 B 城的路径（可以经过一条</div>
<div>边多次，也可以经过自环），将这条路径上每条道路的通过时间减少T（ T可以取任意非负实数）。SHUXK 可以使</div>
<div>用这种魔法任意多次，但是仍然有一些限制：</div>
<div>1. 不能使得某一条道路的通过时间T ≤ 0，否则会违反时间法；</div>
<div>2. 由于使用一次魔法所需要的魔力与路径上的道路数量呈指数关系，所以</div>
<div>一次选择的路径上不能有超过??条道路。</div>
<div>想着自己是在为民造福， SHUXK 很高兴。他的愉悦度定义为每一次路径魔法的T值之和再除以 7。（为什么要除以</div>
<div> 7？因为 SHUXK 很喜欢 142857 这个数）SHUXK 想知道他最多可以获得多少愉悦度。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含五个正整数N,M,A,B,L分别表示城市的数量、道路的数量、 A 城和 B 城的编号以及 SHUXK 的路径魔法</div>
<div>限制的道路数量。</div>
<div>以下M行每行含三个正整数x,y,t表示城市x和城市t间连有一条道路，通过所需的时间为t（ 1 ≤ t≤ 10000）。</div>
<div>N&lt;=100,M&lt;=500,L&lt;=6</div>
<p></p></div>

# Output

<div class="content"><div>只有一行一个实数，表示 SHUXK 可以获得的最大的愉悦度。 当你</div>
<div>的答案与标准答案的绝对误差不超过10^-6时即视为正确。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5 1 5 3<br/>
1 2 2<br/>
1 3 2<br/>
2 4 2<br/>
3 4 2<br/>
4 5 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.428571<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

