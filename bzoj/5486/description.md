
# Description

<div class="content"><div>漫长的一天结束了，饥困交加的奶牛们准备返回牛棚。农场由N片牧场组成（2≤N≤50,000），方便起见编号为1…</div>
<div>N。所有奶牛都要前往位于牧场N的牛棚。其他N?1片牧场中每片有一头奶牛。奶牛们可以通过M条无向的小路在牧场</div>
<div>之间移动（1≤M≤100,000）。第i条小路连接牧场ai和bi，通过需要时间ti。每头奶牛都可以经过一些小路回到牛</div>
<div>棚。由于饥饿，奶牛们很乐于在他们回家的路上停留一段时间觅食。农场里有K个有美味的干草捆，第i个干草捆的</div>
<div>美味值为yi。每头奶牛都想要在她回牛棚的路上在某一个干草捆处停留，但是她这样做仅当经过这个干草捆使她回</div>
<div>牛棚的时间增加不超过这个干草捆的美味值。注意一头奶牛仅仅“正式地”在一个干草捆处因进食而停留，即使她</div>
<div>的路径上经过其他放有干草捆的牧场；她会简单地无视其他的干草捆。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含三个空格分隔的整数N，M和K。</div>
<div>以下M行每行包含三个整数ai，bi和ti，表示牧场ai和bi之间有一条需要ti时间通过的小路</div>
<div>（ai不等于bi，ti为不超过104的正整数）。</div>
<div>以下K行，每行以两个整数描述了一个干草捆：该干草捆所在牧场的编号，以及它的美味值（一个不超过10^9的正整数）。</div>
<div>同一片牧场中可能会有多个干草捆。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出包含N-1行。</div>
<div>如果牧场i里的奶牛可以在回牛棚的路上前往某一个干草捆并且在此进食，则第i行为一个整数1，否则为一个整数0</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5 1<br/>
1 4 10<br/>
2 1 20<br/>
4 2 3<br/>
2 3 5<br/>
4 3 2<br/>
2 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
1<br/>
1<br/>
在这个例子中，牧场3里的奶牛可以停留进食，因为她回去的时间仅会增加6（从2增加到8），而这个增加量并没有<br/>
超过干草捆的美味值7。牧场2里的奶牛显然可以吃掉牧场2里的干草，因为这并不会导致她的最佳路径发生变化。<br/>
对于牧场1里的奶牛是一个有趣的情况，因为看起来她的最佳路径（10）可能会因为前去进食而有过大的增加量。<br/>
然而，确实存在一条路径使得她可以前去干草捆处停留：先到牧场4，然后去牧场2（吃草），然后回到牧场4。 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

