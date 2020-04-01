
# Description

<div class="content"><p><span style="font-size: medium; ">Farmer John&#39;s N (1 &lt;= N &lt;= 50,000) cows are standing in a very straight row and mooing. Each cow has a unique height h in the range 1..2,000,000,000 nanometers (FJ really is a stickler for precision). Each cow moos at some volume v in the range 1..10,000. This &#34;moo&#34; travels across the row of cows in both directions (except for the end cows, obviously). Curiously, it is heard only by the closest cow in each direction whose height is strictly larger than that of the mooing cow (so each moo will be heard by 0, 1 or 2 other cows, depending on not whether or taller cows exist to the mooing cow&#39;s right or left).  The total moo volume heard by given cow is the sum of all the moo volumes v for all cows whose mooing reaches the cow. Since some (presumably taller) cows might be subjected to a very large moo volume, FJ wants to buy earmuffs for the cow whose hearing is most threatened. Please compute the loudest moo volume heard by any cow. </span></p>
<p></p>
<p><span style="font-size: medium; ">  Farmer John的N(1&lt;=N&lt;=50,000)头奶牛整齐地站成一列“嚎叫”。每头奶牛有一个确定的高度h(1&lt;=h&lt;=2000000000)，叫的音量为v (1&lt;=v&lt;=10000)。每头奶牛的叫声向两端传播，但在每个方向都只会被身高严格大于它的最近的一头奶牛听到，所以每个叫声都只会 被0，1，2头奶牛听到（这取决于它的两边有没有比它高的奶牛）。  一头奶牛听到的总音量为它听到的所有音量之和。自从一些奶牛遭受巨大的音量之后，Farmer John打算买一个耳罩给被残害得最厉 害的奶牛，请你帮他计算最大的总音量。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium; ">* Line 1: A single integer, N. </span></p>
<p><span style="font-size: medium; "> * Lines 2..N+1: Line i+1 contains two space-separated integers, h and         v, for the cow standing at location i.</span></p>
<p></p><p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">第</span><span lang="EN-US">1</span><span style="font-family: 宋体; ">行：一个正整数</span><span lang="EN-US">N.</span></span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">第</span><span lang="EN-US">2</span><span style="font-family: 宋体; ">到</span><span lang="EN-US">N+1</span><span style="font-family: 宋体; ">行：每行包括</span><span lang="EN-US">2</span><span style="font-family: 宋体; ">个用空格隔开的整数，分别代表站在队伍中第</span><span lang="EN-US">i</span><span style="font-family: 宋体; ">个位置的奶牛的身高以及她唱歌时的音量．</span></span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium; ">* Line 1: The loudest moo volume heard by any single cow.</span></p>
<p><span style="font-size: medium; "><br type="_moz"/>
</span></p>
<p><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">队伍中的奶牛所能听到的最高的总音量．</span></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
4 2<br/>
3 5<br/>
6 10<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
Three cows: the first one has height 4 and moos with volume 2, etc.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium; "> </span><a id="fck_paste_padding"><span style="font-size: medium; ">﻿</span></a><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">队伍中的第</span><span lang="EN-US">3</span><span style="font-family: 宋体; ">头奶牛可以听到第</span><span lang="EN-US">1</span><span style="font-family: 宋体; ">头和第</span><span lang="EN-US">2</span><span style="font-family: 宋体; ">头奶牛的歌声，于是她能听到的总音量为</span><span lang="EN-US">2+5=7</span><span style="font-family: 宋体; ">．虽然她唱歌时的音量为</span><span lang="EN-US">10</span><span style="font-family: 宋体; ">，但并没有奶牛可以听见她的歌声．</span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

