
# Description

<div class="content"><div>厌倦了农场生活，奶牛们变卖了所有尘世的财产，加入了一支巡回马戏团。到现在为止，奶牛们已经能够进行简单</div>
<div>的表演了：耍火把、走钢丝、骑独轮车——没什么是拥有灵巧蹄子的奶牛做不到的。但是，马戏团指挥想要为他们</div>
<div>的下一次演出创作一个更加激动人心的表演。新的表演所用的舞台由N个围成一圈的平台组成。在每个平台上，1至</div>
<div>N头奶牛叠成一摞，一头叠在一头上面。当指挥给出信号的时候，每摞奶牛同时顺时针落下，最下面的奶牛不动，</div>
<div>在她上面的奶牛顺时针移动一个平台，再上面的奶牛顺时针移动两个平台，等等。作为技艺高超的体操家，奶牛们</div>
<div>明白她们在这个表演的技术方面没有任何问题。不同摞的奶牛在下落的过程中不会相互“干扰”，所以每头奶牛都</div>
<div>会落在预期的平台上。然后所有落在同一平台上的奶牛又会重新叠成一摞，这次她们不会再落下来。指挥认为，如</div>
<div>果在奶牛们落下之后，每个平台上新的那一摞奶牛的数量和原来这个平台上的那一摞奶牛数量相等的话，这次表演</div>
<div>就会格外激动人心。我们把满足这种性质的各摞奶牛的数量排列称为是“魔幻的”。请帮助奶牛计算魔幻的排列数</div>
<div>。由于这个数字可能非常大，计算该数mod 10^9+7的余数。两个排列被认为是不同的，如果这两个排列在任何一个</div>
<div>平台上分配了不同数量的奶牛。</div>
<div></div></div>

# Input

<div class="content"><p>输入包含一个整数N（1≤N≤10^12）。</p>
<div></div></div>

# Output

<div class="content"><p>输出一个整数，为魔幻的排列数mod 10^9+7的余数。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
当N=4时，魔幻的排列有(1,1,1,1)，(2,2,2,2)，(3,3,3,3)，<br/>
(4,4,4,4)，(2,3,2,3)，以及(3,2,3,2)。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum">Platinum</a></p></div>

