
# Description

<div class="content"><div>In a village called Byteville, there are   houses connected with N-1 roads. For each pair of houses, there is a unique way to get from one to another. The houses are numbered from 1 to  . The house no. 1 belongs to the village administrator Byteasar. As part of enabling modern technologies for rural areas framework,   computers have been delivered to Byteasar&#39;s house. Every house is to be supplied with a computer, and it is Byteasar&#39;s task to distribute them. The citizens of Byteville have already agreed to play the most recent version of FarmCraft (the game) as soon as they have their computers.</div>
<div>Byteasar has loaded all the computers on his pickup truck and is about to set out to deliver the goods. He has just the right amount of gasoline to drive each road twice. In each house, Byteasar leaves one computer, and immediately continues on his route. In each house, as soon as house dwellers get their computer, they turn it on and install FarmCraft. The time it takes to install and set up the game very much depends on one&#39;s tech savviness, which is fortunately known for each household. After he delivers all the computers, Byteasar will come back to his house and install the game on his computer. The travel time along each road linking two houses is exactly 1 minute, and (due to citizens&#39; eagerness to play) the time to unload a computer is negligible.</div>
<div>Help Byteasar in determining a delivery order that allows all Byteville&#39;s citizens (including Byteasar) to start playing together as soon as possible. In other words, find an order that minimizes the time when everyone has FarmCraft installed.</div>
<div><span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23px;">mhy住在一棵有n个点的树的1号结点上，每个结点上都有一个妹子。</span></div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23px;">
<div>mhy从自己家出发，去给每一个妹子都送一台电脑，每个妹子拿到电脑后就会开始安装zhx牌杀毒软件，第i个妹子安装时间为Ci。</div>
<div>树上的每条边mhy能且仅能走两次，每次耗费1单位时间。mhy送完所有电脑后会回自己家里然后开始装zhx牌杀毒软件。</div>
<div>卸货和装电脑是不需要时间的。</div>
<div>求所有妹子和mhy都装好zhx牌杀毒软件的最短时间。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>The first line of the standard input contains a single integer N(2&lt;=N&lt;=5 00 000)  that gives the number of houses in Byteville. The second line contains N integers C1,C2…Cn(1&lt;=Ci&lt;=10^9), separated by single spaces; Ci is the installation time (in minutes) for the dwellers of house no. i.</div>
<div>
<div>The next N-1  lines specify the roads linking the houses. Each such line contains two positive integers a and b(1&lt;=a&lt;b&lt;=N) , separated by a single space. These indicate that there is a direct road between the houses no. a and b.</div>
</div>
<p></p></div>

# Output

<div class="content"><div>
<div>The first and only line of the standard output should contain a single integer: the (minimum) number of minutes after which all citizens will be able to play FarmCraft together.</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
1 8 9 6 3 2<br/>
1 3<br/>
2 3<br/>
3 4<br/>
4 5<br/>
4 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">11<br/>
</span></div>

# Hint

<div class="content"><p></p><div>Explanation: Byteasar should deliver the computers to the houses in the following order: 3, 2, 4, 5, 6, and 1. The game will be installed after 11, 10, 10, 10, 8, and 9 minutes respectively, in the house number order. Thus everyone can play after 11 minutes.</div><br/>
<div>If Byteasar delivered the game in the following order: 3, 4, 5, 6, 2, and 1, then the game would be installed after: 11, 16, 10, 8, 6, and 7 minutes respectively. Hence, everyone could play only after 16 minutes,</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢zhonghaoxi">鸣谢zhonghaoxi</a></p></div>

