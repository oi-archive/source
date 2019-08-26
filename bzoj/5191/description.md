
# Description

<div class="content"><div>FarmerJohn最讨厌的农活是运输牛粪。为了精简这个过程，他产生了一个新奇的想法：与其使用拖拉机拖着装满牛</div>
<div>粪的大车从一个地点到另一个地点，为什么不用一个巨大的便便弹弓把牛粪直接发射过去呢？（事实上，好像哪里</div>
<div>不太对……）FarmerJohn的农场沿着一条长直道路而建，所以他农场上的每个地点都可以简单地用该地点在道路上</div>
<div>的位置来表示（相当于数轴上的一个点）。FJ建造了N个弹弓（1≤N≤10^5），其中第i个弹弓可以用三个整数xi，</div>
<div>yi以及ti描述，表示这个弹弓可以在ti单位时间内将牛粪从位置xi发射到位置yi。FJ有M堆牛粪需要运输（1≤M≤1</div>
<div>0^5）。第j堆牛粪需要从位置aj移动到位置bj。使用拖拉机运输牛粪，经过路程d需要消耗d单位时间。FJ希望通过</div>
<div>对每一堆牛粪使用至多一次弹弓来减少运输时间。FJ驾驶没有装载牛粪的拖拉机的时间不计。对这M堆牛粪的每一</div>
<div>堆，在FJ可以在运输过程中使用至多一次弹弓的条件下，帮助FJ求出其最小运输时间。</div>
<div></div></div>

# Input

<div class="content"><div>
<div>输入的第一行包含N和M。</div>
<div>下面N行，每行用xi，yi，ti（0≤xi,yi,ti≤10^9）描述了一个弹弓。</div>
<div>最后M行用aj和bj描述了需要移动的牛粪。</div>
</div>
<div></div></div>

# Output

<div class="content"><p>输出M行，每堆牛粪一行，表示运输这堆牛粪需要的最短时间。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 3<br/>
0 10 1<br/>
13 8 2<br/>
1 12<br/>
5 2<br/>
20 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
3<br/>
10<br/>
<br/>
在这里，第一堆牛粪需要从位置1移动到位置12。不使用弹弓的话，会消耗11单位时间。但是，如果使用第一个弹<br/>
弓，只需消耗1单位时间移动到位置0（弹弓的发射点），1单位时间将弹弓通过空中弹射并着陆在位置10（弹弓的<br/>
目的地），然后2单位时间把牛粪移动到位置12。第二堆牛粪的最佳移动方案是不使用弹弓，第三堆牛粪应该使用<br/>
第二个弹弓。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum">Platinum</a></p></div>

