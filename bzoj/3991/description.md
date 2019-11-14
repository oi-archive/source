
# Description

<div class="content"><p> <span style="font-family: 宋体;">小</span><span lang="EN-US">B</span><span style="font-family: 宋体;">最近正在玩一个寻宝游戏，这个游戏的地图中有</span><span lang="EN-US">N</span><span style="font-family: 宋体;">个村庄和</span><span lang="EN-US">N-1</span><span style="font-family: 宋体;">条道路，并且任何两个村庄之间有且仅有一条路径可达。游戏开始时，玩家可以任意选择一个村庄，瞬间转移到这个村庄，然后可以任意在地图的道路上行走，若走到某个村庄中有宝物，则视为找到该村庄内的宝物，直到找到所有宝物并返回到最初转移到的村庄为止。<span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">小</span><span lang="EN-US">B</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;">希望评测一下这个游戏的难度，因此他需要知道玩家找到所有宝物需要行走的最短路程。但是这个游戏中宝物经常变化，有时某个村庄中会突然出现宝物，有时某个村庄内的宝物会突然消失，因此小</span><span lang="EN-US">B</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">需要不断地更新数据，但是小</span><span lang="EN-US">B</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;">太懒了，不愿意自己计算，因此他向你求助。</span></span><span style="font-family: 宋体;">为了简化问题，我们认为最开始时所有村庄内均没有宝物<br/>
</span></p>
<p class="NOI1"></p></div>

# Input

<div class="content"><p> 第一行，两个整数N、M，其中M为宝物的变动次数。</p>
<div>接下来的N-1行，每行三个整数x、y、z，表示村庄x、y之间有一条长度为z的道路。</div>
<div>接下来的M行，每行一个整数t，表示一个宝物变动的操作。若该操作前村庄t内没有宝物，则操作后村庄内有宝物；若该操作前村庄t内有宝物，则操作后村庄内没有宝物。</div>
<div></div></div>

# Output

<div class="content"><p> M行，每行一个整数，其中第i行的整数表示第i次操作之后玩家找到所有宝物需要行走的最短路程。若只有一个村庄内有宝物，或者所有村庄内都没有宝物，则输出0。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 5<br/>
1 2 30<br/>
2 3 50<br/>
2 4 60<br/>
2<br/>
3<br/>
4<br/>
2<br/>
1</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
100<br/>
220<br/>
220<br/>
280</span></div>

# Hint

<div class="content"><p></p><p> 1&lt;=N&lt;=100000</p><br/>
<div>1&lt;=M&lt;=100000</div><br/>
<div>对于全部的数据，1&lt;=z&lt;=10^9</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round 1 感谢yts1999上传">Round 1 感谢yts1999上传</a></p></div>

