
# Description

<div class="content"><p><span style="font-size: medium">21 世纪，许多人得了一种奇怪的病：起床困难综合症，其临床表现为：起床难，起床后精神不佳。作为一名青春阳光好少年，atm 一直坚持与起床困难综合症作斗争。通过研究相关文献，他找到了该病的发病原因：在深邃的太平洋海底中，出现了一条名为 drd 的巨龙，它掌握着睡眠之精髓，能随意延长大家的睡眠时间。正是由于 drd 的活动，起床困难综合症愈演愈烈，以惊人的速度在世界上传播。为了彻底消灭这种病，atm 决定前往海底，消灭这条恶龙。</span><span style="font-size: medium">历经千辛万苦，atm 终于来到了 drd 所在的地方，准备与其展开艰苦卓绝的战斗。drd 有着十分特殊的技能，他的防御战线能够使用一定的运算来改变他受到的伤害。具体说来，drd 的防御战线由<span style="position: relative; top: 5.5pt"> </span><i>n</i>扇防御门组成。每扇防御门包括一个运算op和一个参数<i>t</i>，其中运算一定是OR,XOR,AND中的一种，参数则一定为非负整数。如果还未通过防御门时攻击力为<i>x</i>，则其通过这扇防御门后攻击力将变为<i>x op t</i>。最终drd 受到的伤害为对方初始攻击力<i>x</i><b><u>依次经过所有</u></b><b><u><i>n</i>扇防御门</u></b>后转变得到的攻击力。</span><span style="font-size: medium">由于atm水平有限，他的初始攻击力只能为0到<i>m</i>之间的一个整数（即他的初始攻击力只能在0,1,...,<i>m</i>中任选，但在通过防御门之后的攻击力不受<span style="position: relative; top: 3pt"> </span><i>m</i>的限制）。为了节省体力，他希望通过选择合适的初始攻击力使得他的攻击能让 drd 受到最大的伤害，请你帮他计算一下，他的一次攻击最多能使 drd 受到多少伤害。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第1行包含2个整数，依次为n,m，表示drd有n扇防御门，atm的初始攻击力为0到m之间的整数。接下来n行，依次表示每一扇防御门。每行包括一个字符串op和一个非负整数t，两者由一个空格隔开，且op在前，t在后，op表示该防御门所对应的操作， t表示对应的参数。</span><span style="font-family: arial, verdana, helvetica, sans-serif;">n&lt;=10^5</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><span style="display: none" id="1406442039948S"> </span>一行一个整数，表示atm的一次攻击最多使 drd 受到多少伤害。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 10<br/>
AND 5<br/>
OR 6<br/>
XOR 7 </span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
</span></div>

# Hint

<div class="content"><p></p><div>【样例说明1】</div><br/>
<div>atm可以选择的初始攻击力为0,1,...,10。</div><br/>
<div>假设初始攻击力为4，最终攻击力经过了如下计算</div><br/>
<div>4 AND 5 = 4</div><br/>
<div>4 OR 6 = 6</div><br/>
<div>6 XOR 7 = 1</div><br/>
<div>类似的，我们可以计算出初始攻击力为1,3,5,7,9时最终攻击力为0，初始攻击力为0,2,4,6,8,10时最终攻击力为1，因此atm的一次攻击最多使 drd 受到的伤害值为1。</div><br/>
<div>0&lt;=m&lt;=10^9</div><br/>
<div>0&lt;=t&lt;=10^9  </div><br/>
<div>一定为OR,XOR,AND 中的一种</div><br/>
<div>【运算解释】</div><br/>
<div>在本题中，选手需要先将数字变换为二进制后再进行计算。如果操作的两个数二进制长度不同，则在前补0至相同长度。OR为按位或运算，处理两个长度相同的二进制数，两个相应的二进制位中只要有一个为1，则该位的结果值为1，否则为0。XOR为按位异或运算，对等长二进制模式或二进制数的每一位执行逻辑异或操作。如果两个相应的二进制位不同（相异），则该位的结果值为1，否则该位为0。 AND 为按位与运算，处理两个长度相同的二进制数，两个相应的二进制位都为1，该位的结果值才为1，否则为0。</div><br/>
<div>例如，我们将十进制数5与十进制数3分别进行OR，XOR 与 AND 运算，可以得到如下结果：</div><br/>
<div></div><br/>
<div>              0101 (十进制 5)           0101 (十进制 5)           0101 (十进制 5)</div><br/>
<div></div><br/>
<div>              OR 0011 (十进制 3)    XOR 0011 (十进制 3)    AND 0011 (十进制 3)</div><br/>
<div></div><br/>
<div>           = 0111 (十进制 7)       = 0110 (十进制 6)        = 0001 (十进制 1)</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

