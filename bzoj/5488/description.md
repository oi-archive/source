
# Description

<div class="content"><div>在Farmer John最喜欢的节日里，他想要给他的朋友们赠送一些礼物。由于他并不擅长包装礼物，他想要获得他的</div>
<div>奶牛们的帮助。你可能能够想到，奶牛们本身也不是很擅长包装礼物，而Farmer John即将得到这一教训。Farmer </div>
<div>John的N头奶牛（1≤N≤104）排成一行，方便起见依次编号为1…N。奶牛i的包装礼物的技能水平为si。她们的技</div>
<div>能水平可能参差不齐，所以FJ决定把她的奶牛们分成小组。每一组可以包含任意不超过K头的连续的奶牛（1≤K≤1</div>
<div>03），并且一头奶牛不能属于多于一个小组。由于奶牛们会互相学习，这一组中每一头奶牛的技能水平会变成这一</div>
<div>组中水平最高的奶牛的技能水平。请帮助FJ求出，在他合理地安排分组的情况下，可以达到的技能水平之和的最大</div>
<div>值。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入的第一行包含N和K。</div>
<div>以下N行按照N头奶牛的排列顺序依次给出她们的技能水平。技能水平是一个不超过10^5的正整数。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出FJ通过将连续的奶牛进行分组可以达到的最大技能水平和。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 3<br/>
1<br/>
15<br/>
7<br/>
9<br/>
2<br/>
5<br/>
10</span></div>

# Sample Output

<div class="content"><span class="sampledata">84<br/>
在这个例子中，最优的方案是将前三头奶牛和后三头奶牛分别分为一组，中间的奶牛单独成为一组（注意一组的奶<br/>
牛数量可以小于K）。这样能够有效地将7头奶牛的技能水平提高至15、15、15、9、10、10、10，和为84。 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

