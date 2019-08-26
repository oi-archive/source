
# Description

<div class="content"><div>JOI君所居住的IOI市以一年四季都十分炎热著称。</div>
<div>IOI市是一个被分成纵H*横W块区域的长方形，每个区域都是建筑物、原野、墙壁之一。建筑物的区域有P个，编号为1...P。</div>
<div>JOI君只能进入建筑物与原野，而且每次只能走到相邻的区域中，且不能移动到市外。</div>
<div>JOI君因为各种各样的事情，必须在各个建筑物之间往返。虽然建筑物中的冷气设备非常好，但原野上的日光十分强烈，因此在原野上每走过一个区域都需要1单位的水。此外，原野上没有诸如自动售货机、饮水处之类的东西，因此IOI市的市民一般都携带水壶出行。大小为x的水壶最多可以装x单位的水，建筑物里有自来水可以将水壶装满。</div>
<div>由于携带大水壶是一件很困难的事情，因此JOI君决定携带尽量小的水壶移动。因此，为了随时能在建筑物之间移动，请你帮他写一个程序来计算最少需要多大的水壶。</div>
<div>现在给出IOI市的地图和Q个询问，第i个询问(1&lt;=i&lt;=Q)为“在建筑物Si和Ti之间移动，最小需要多大的水壶？”，请你对于每个询问输出对应的答案。</div>
<p></p></div>

# Input

<div class="content"><div>第一行四个空格分隔的整数H,W,P,Q，表示IOI市被分成了纵H*横W块区域，有P个建筑物，Q次询问。</div>
<div>接下来H行，第i行(1&lt;=i&lt;=H)有一个长度为W的字符串，每个字符都是’.’或’#’之一，’.’表示这个位置是建筑物或原野，’#’表示这个位置是墙壁。</div>
<div>接下来P行描述IOI市每个建筑物的位置，第i行(1&lt;=i&lt;=P)有两个空格分隔的整数Ai和Bi，表示第i个建筑物的位置在第Ai行第Bi列。保证这个位置在地图中是’.’</div>
<div>接下来Q行，第i行(1&lt;=i&lt;=Q)有两个空格分隔的整数Si和Ti，表示第i个询问为“在建筑物Si和Ti之间移动，最小需要多大的水壶？”</div>
<p></p></div>

# Output

<div class="content"><div>
<div>输出Q行，第i行(1&lt;=i&lt;=Q)一个整数，表示在建筑物Si和Ti之间移动最小需要多大的水壶。</div>
<div>如果无法到达，输出-1。此外，如果不需要经过原野就能到达，输出0。</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5 4 4<br/>
.....<br/>
..##.<br/>
.#...<br/>
..#..<br/>
.....<br/>
1 1<br/>
4 2<br/>
3 3<br/>
2 5<br/>
1 2<br/>
2 4<br/>
1 3<br/>
3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
4<br/>
4<br/>
2</span></div>

# Hint

<div class="content"><p></p><div>1&lt;=H&lt;=2000</div><br/>
<div>1&lt;=W&lt;=2000</div><br/>
<div>2&lt;=P&lt;=2*10^5</div><br/>
<div>1&lt;=Q&lt;=2*10^5</div><br/>
<div>1&lt;=Ai&lt;=H(1&lt;=i&lt;=P)</div><br/>
<div>1&lt;=Bi&lt;=W(1&lt;=i&lt;=P)</div><br/>
<div>(Ai,Bi)≠(Aj,Bj)(1&lt;=i&lt;j&lt;=P)</div><br/>
<div>1&lt;=Si&lt;Ti&lt;=P(1&lt;=i&lt;=Q)</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=JOI 2013~2014 春季training合宿 竞技2 By PoPoQQQ">JOI 2013~2014 春季training合宿 竞技2 By PoPoQQQ</a></p></div>

