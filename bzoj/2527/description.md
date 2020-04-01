
# Description

<div class="content"><div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">Byteotian Interstellar Union (BIU) has recently discovered a new planet in a nearby galaxy. The planet is unsuitable for colonisation due to strange meteor showers, which on the other hand make it an exceptionally interesting object of study. </span></span></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">The member states of BIU have already placed space stations close to the planet&#39;s orbit. The stations&#39; goal is to take samples of the rocks flying by. The BIU Commission has partitioned the orbit into msectors, numbered from 1to m, where the sectors 1and mare adjacent. In each sector there is a single space station, belonging to one of the nmember states. </span></span></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">Each state has declared a number of meteor samples it intends to gather before the mission ends. Your task is to determine, for each state, when it can stop taking samples, based on the meter shower predictions for the years to come. </span></span></div>
<div style="line-height: 140%" align="left"></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium">Byteotian Interstellar Union有N个成员国。现在它发现了一颗新的星球，这颗星球的轨道被分为M份（第M份和第1份相邻），第i份上有第Ai个国家的太空站。</span></div>
<p></p>
<pre style="font-family: arial, verdana, helvetica, sans-serif! important"><span style="font-size: medium">这个星球经常会下陨石雨。BIU已经预测了接下来K场陨石雨的情况。
BIU的第i个成员国希望能够收集Pi单位的陨石样本。你的任务是判断对于每个国家，它需要在第几次陨石雨之后，才能收集足够的陨石。
输入：
第一行是两个数N,M。
第二行有M个数，第i个数Oi表示第i段轨道上有第Oi个国家的太空站。
第三行有N个数，第i个数Pi表示第i个国家希望收集的陨石数量。
第四行有一个数K，表示BIU预测了接下来的K场陨石雨。
接下来K行，每行有三个数Li,Ri,Ai，表示第K场陨石雨的发生地点在从Li顺时针到Ri的区间中（如果Li&lt;=Ri，就是Li,Li+1,...,Ri，否则就是Ri,Ri+1,...,m-1,m,1,...,Li），向区间中的每个太空站提供Ai单位的陨石样本。
输出：
N行。第i行的数Wi表示第i个国家在第Wi波陨石雨之后能够收集到足够的陨石样本。如果到第K波结束后仍然收集不到，输出NIE。
数据范围：
</span><p></p><div style="line-height: 140%" align="left"></div><div style="line-height: 140%" align="left"><span style="font-size: medium">数据范围：
1&lt;=n,m,k&lt;=3*10^5
1&lt;=Pi&lt;=10^9
1&lt;=Ai&lt;10^9

</span></div></pre></div>

# Input

<div class="content"><div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">The first line of the standard input gives two integers, n and m(1&lt;=n,m&lt;=3*10^5) separated by a single space, that denote, respectively, the number of BIU member states and the number of sectors the orbit has been partitioned into. </span></span></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">In the second line there are mintegers Oi(1&lt;=Oi&lt;=n) separated by single spaces, that denote the states owning stations in successive sectors. </span></span></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">In the third line there are nintegers Pi(1&lt;=Pi&lt;=10^9) separated by single spaces, that denote the numbers of meteor samples that the successive states intend to gather. </span></span></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">In the fourth line there is a single integer k(1&lt;=k&lt;=3*10^5) that denotes the number of meteor showers predictions. The following klines specify the (predicted) meteor showers chronologically. The i-th of these lines holds three integers Li, Ri, Ai(separated by single spaces), which denote that a meteor shower is expected in sectors Li,Li+1,…Ri (if Li&lt;=Ri) or sectors Li,Li+1,…,m,1,…Ri (if Li&gt;Ri), which should provide each station in those sectors with Aimeteor samples (1&lt;=Ai&lt;10^9). </span></span></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">In tests worth at least 20% of the points it additionally holds that . </span></span></div></div>

# Output

<div class="content"><div style="line-height: 140%" align="left"> </div>
<div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">Your program should print nlines on the standard output. The i-th of them should contain a single integer Wi, denoting the number of shower after which the stations belonging to the i-th state are expected to gather at least Pi samples, or the word </span><span style="color: #444444; line-height: 140%">NIE</span><span style="color: #444444; line-height: 140%"> (Polish for <i>no</i>) if that state is not expected to gather enough samples in the foreseeable future. </span></span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 5<br/>
1 3 2 1 3<br/>
10 5 7<br/>
3<br/>
4 2 4<br/>
1 3 1<br/>
3 5 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
NIE<br/>
1<br/>
 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢 Object022">鸣谢 Object022</a></p></div>

