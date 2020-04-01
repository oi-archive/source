
# Description

<div class="content"><div>最近HH公司推出了新型的排序网络。简单的来说，这种排序网络是由一系列的的排序器按顺序组成。某个排序器可</div>
<div>以将排序网络中[L,R]之间的输入端进行排序。经过排序器处理后[L,R]之间排成非递减顺序。不同排序器的L、R值</div>
<div>不同。虽然排序网络很有用，但是很多情况下面我们可能只要排序网络中的最大值，所以Henryy公司决定利用已有</div>
<div>的排序网络再开发一个只求最大值的网络。改造方法很简单，只需要隐蔽原有网络中的某些排序器，使得最后一个</div>
<div>输入端的值是最大值。这样一来既可以减少开发成本，又可以降低网络的功耗。现在的任务是，给定N个不同的排</div>
<div>序器，要求你改造这个网络，使得网络最后一个输入端经过操作后是这个网络的最大值。要求使用的排序器要尽可</div>
<div>能少。（也就是说，不能改变原来排序网络的结构，你可以选择某个排序器是否隐蔽）</div></div>

# Input

<div class="content"><div>第一行是两个数N，M。N表示排序网络有N个输入端。</div>
<div>接下来将会有M行，每行2个数Li，Ri，分别表示排序器I排序的范围[Li，Ri]。</div>
<div>（1&lt;=Li&lt;=Ri&lt;=N）</div></div>

# Output

<div class="content"><div>输出一个数P，表示使用的最少排序器。-1表示无解（由于设计缺陷）。</div>
<p></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">40 6<br/>
20 30<br/>
1 10<br/>
10 20<br/>
20 30<br/>
15 25<br/>
30 40</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
【数据约定】<br/>
0≤N≤50000，0≤M≤500000。</span></div>

# Hint

<div class="content"><p></p><p> 2017.10.12新加数据一组By <span style="color: rgb(61, 136, 45); font-family: &#39;Microsoft Yahei&#39;, verdana; font-size: 14.3999996185303px; font-weight: bold; line-height: 18.659200668335px;">yanQval</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

