
# Description

<div class="content">让我们来建造一艘新的海盗船。船上有 N个旗杆，每根旗杆被分成单位长度的小节。旗杆的长度等于它被分成的小节的数目。每根旗杆上会挂一些帆，每张帆正好占据旗杆上的一个小节。在一根旗杆上的帆可以任意排布在不同的小节中，但是每个小节上至多能挂一张帆。

在风中，帆的不同排布方式会产生不同的推动力。靠近船头的帆比它后面的相同高度上的帆获得的推动力少，换句话说，靠近船头的帆的推动力由于受它后面相同高度的帆的影响而打了折扣。对于任意一张帆，它的推动力折扣等于在它后面并且和它在同一高度的帆的数目。

所有帆的任意一种位置组合的推动力折扣总和等于在该位置下所有帆的推动力折扣的总和。
  
<img border="0" src="/source/bzoj/1805/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE4MDUuanBn.jpg"/> 
前                                                                                               后
这条船上有6个旗杆，从前（图上的左边）到后的高度分别是3，5，4，2，4和3。图中所示的帆的位置组合的总推动力折扣是10。上图给出了每张帆自己的推动力折扣。

任务

给定N个旗杆的高度和每个旗杆上挂的帆的数目，写一个程序求出所有位置组合中的可能达到的最小的总推动力折扣。
</div>

# Input

<div class="content">第一行包含一个整数N（2 ≤ N ≤ 100 000），表示旗杆的数目。
接下来的N行每行包含两个整数H和K（1 ≤ H ≤ 100 000, 1 ≤ K ≤ H），分别表示对应旗杆的高度及其上的帆的数目。旗杆按照从船头到船尾的顺序给出。

</div>

# Output

<div class="content">输出包含一个整数，表示可以达到的最小的总推动力折扣。
注意：计算和输出结果时使用64位整数类型（在C/C++中用long long, 在Pascal中用int64）。

评分

在25分的测试数据中，帆的不同位置组合的总数目不超过1 000 000。

</div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
3 2<br/>
5 3<br/>
4 1<br/>
2 1<br/>
4 3<br/>
3 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">10<br/>
<br/>
这个样例数据和上页中图示的样例相同。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

