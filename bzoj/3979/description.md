
# Description

<div class="content"><div>早上好，特工W-12，你需要完成的以下的任务。</div>
<div>我们已经渗透到一个叫混乱与祸害的组织中，希望能掌握该组织的管理权。不幸的是，它们似乎已经准备好应对这样的事件了，它们使用了一个很复杂的设计分配管理权力，这使得我们的渗透工作非常艰难。</div>
<div>那家组织的管理系统被分成若干个单位，对于任意两个单位A和B，要么A管理B要么B管理A，同时这个管理关系可以形成环，因此可以出现A管理B、B管理C、C管理A的情况。</div>
<div>我们可以安排特工去渗透到任意一个单位，那将使得我们控制该单位和那个单位直接管理的单位，但是不包括间接管理的单位。比如之前的样例，渗透到A单位会让我们控制A和B，但不能控制C。</div>
<div>对于一个成功的渗透工作来说，我们必须要控制所有的单位才行，否则其他单位会发现我们，同时破坏我们的计划。而你也知道，我们现在从更高的部门那里拿到的经费十分紧缺，我们必须最高效地完成任务。你的任务就是要找出控制单位最少的可行方案。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个整数n，表示该组织的单位数。接下来n行每行n个二进制位。在其中的第i行第j列位置，若为1表示i单位控制j单位，否则j单位控制i单位</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>共一行，第一个整数ans表示最少的控制单位数量</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
00<br/>
10<br/>
3<br/>
010<br/>
001<br/>
100<br/>
5<br/>
01000<br/>
00011<br/>
11001<br/>
10100<br/>
10010<br/>
4<br/>
0100<br/>
0000<br/>
1100<br/>
1110<br/>
4<br/>
0011<br/>
1011<br/>
0001<br/>
0000<br/>
4<br/>
0101<br/>
0010<br/>
1001<br/>
0100<br/>
6<br/>
001110<br/>
100001<br/>
010010<br/>
011010<br/>
010001<br/>
101100<br/>
4<br/>
0000<br/>
1001<br/>
1100<br/>
1010<br/>
7<br/>
0100011<br/>
0000100<br/>
1100001<br/>
1110111<br/>
1010011<br/>
0110000<br/>
0100010<br/>
7<br/>
0010001<br/>
1011111<br/>
0001111<br/>
1000110<br/>
1000000<br/>
1000100<br/>
0001110<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 1<br/>
Case 2: 2<br/>
Case 3: 2<br/>
Case 4: 1<br/>
Case 5: 1<br/>
Case 6: 2<br/>
Case 7: 2<br/>
Case 8: 2<br/>
Case 9: 1<br/>
Case 10: 1<br/>
</span></div>

# Hint

<div class="content"><p></p><div>100%的数据n&lt;=75。</div><br/>
<div>保证n*n的01矩阵中所有的i行i列位置为0，i行j列和j行i列两个位置恰好一个为1一个为0（i≠j）。</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

