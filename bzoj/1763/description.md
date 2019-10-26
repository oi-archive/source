
# Description

<div class="content"><div>Stockholm城市的地铁是由一些地铁网组成的。在这个题目当中我们会特殊考虑到一条线路，当出现“信号错误”</div>
<div>时，问题就经常发生在这条线路。 一条地铁线路能被看做两条平行并且由结束点连接的轨道。在上层的轨道当中</div>
<div>，火车将会从右往左行驶，下层轨道当中，火车将会从左往右行驶。当一辆火车到达了一条轨道的终点，它就改变</div>
<div>轨道并且向相反的方向行驶。这个变轨是即刻的并且不需要时间， 在正常的交通当中，行驶的火车是持续不断的</div>
<div>并且火车按照一个持续的速度行驶（火车通过1单位的长度所需时间为1）。火车被均匀地分配；也就是说，在轨道</div>
<div>的任何一个位置，火车将会有周期性地通过。我们可以假设火车进站和乘客上下车的时间是可以忽略的。 现在，</div>
<div>因为“信号错误”，火车已经随机地分配在线路上。作为交通经理，你的任务就是尽可能地保证火车重新被均匀地</div>
<div>分配到线路上。现给出火车的位置，你需要编写一个程序，计算最少花费多少时间能达到目标。你能够命令火车在</div>
<div>任何地方即时停止，或者改变方向。如果一辆火车改变了方向，它将会从自己原本的轨道移动到另一个轨道。</div>
<p><img border="0" src="/source/bzoj/1763/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE3NjMuanBn.jpg" alt=""/>  Figure 1：</p>
<div>两条轨道长度均为100。在上面的例子当中，火车处于的位置为5,35,46,75和85。一个能使火车重新均匀地在轨道</div>
<div>上行驶的方法就是，位置46的火车向左行驶1单位，然后改变方向。这样就花了一个单位时间。然而，这并不是最</div>
<div>佳的方法；具体请看下面的样例1。</div></div>

# Input

<div class="content"><div>第一行包含两个由空格分开的数字，轨道长度m和火车的数目n。 </div>
<div>接下来的n行描述了火车的所有初始位置。</div>
<div>每一行会被给出一个数字Xi和方向（L表示左，R表示右），它们由空格分开。</div></div>

# Output

<div class="content"><div>
<div>输出使火车重新均匀地行驶所能够花费的最小时间。</div>
<div>输出单独占一行。</div>
<div>输出需要保留小数点后恰好六位,输出数据保证不大于10^-6。</div>
<div>100≤m≤100,000,000 1≤n≤100,000 0≤Xi≤m </div>
</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">100 5<br/>
55 L<br/>
37 L<br/>
47 L<br/>
89 L<br/>
41 R</span></div>

# Sample Output

<div class="content"><span class="sampledata">19.000000<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

