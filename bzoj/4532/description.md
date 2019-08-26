
# Description

<div class="content"><div>Alex喜欢玩网络游戏，认为这是智力和体力的综合锻炼。在一次游戏活动中，他意外获得了一个传说中威力极其强大的法宝：珠链。 </div>
<div>珠链，顾名思义，就是由许多小珠子串起来的一条链。珠子有很多种颜色。Alex听说过，只有将珠链打磨纯净，珠链才能发挥最大的威力。 </div>
<div>纯净珠链是指这样的珠链：它可以分成若干个长度相等的段，使任何两段的任何相同位置的珠子的颜色均不同，相同位置指珠子在段内的相对位置相同；而且每段的长度以及划分的段数也是有规范的，Alex记得，每段包含的珠子数目必须在L到R之间，而且划分的段数不能少于S。 </div>
<div>所谓打磨，就是从珠链的首和尾拿掉连续的若干个珠子。打磨后的纯净珠链的威力等于它的每个珠子具有的魔力值之和。一个珠子的魔力值只与它在打磨前的珠链中的位置有关。在查找和分析了大量实验数据以后，Alex发现珠子的魔力值等于珠子原来位置编号的约数个数！ </div>
<div>兴奋不已的Alex想将珠链打磨成威力最大的纯净珠链。然而，马上要参加期末考试的Alex来不及计算了，你能否帮助Alex算出最大的威力值呢？ </div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行是四个整数N, L, R, S。 </div>
<div>第二行是一个长度等于N的字符串，表示Alex得到的珠链。字符串的第i个字符表示珠链的第i个珠子的颜色。相同字母表示相同颜色。珠子的位置从1编号到N。 </div>
<div>1 ≤ N ≤ 500,000，1 ≤ L, R, S ≤ N, 0 ≤ R – L ≤ 10. 输入的字符串只包含大写和小写的英文字母。字母区分大小写。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出一行，表示打磨后的纯净珠链的最大威力值。如果无法打磨成满足要求的纯净珠链，输出 -1. </div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 2 3 2 <br/>
abcbcaa </span></div>

# Sample Output

<div class="content"><span class="sampledata">15 <br/>
【样例解释】 <br/>
能够打磨出的合乎要求的纯净珠链有三种：bc/aa, abc/bca和bcb/caa。其中威力最大的是第三种，其威力值等于2+2+3+2+4+2 = 15。 <br/>
如果给出的珠链是纯净珠链，那么可以不打磨。纯净珠链必须能划分成不少于S个等长的段且每段长度在L到R之间。  </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

