
# Description

<div class="content"><div><span style="font-size: medium">    为了避开老农场边上的烦人的风景，农夫约翰决定搬到一个靠山的地方．在这里，如果360度环视四周，他可以看到一些地方有山，而一些地方没有．    有N(1≤N≤1000)座山环绕着约翰的新居．当他看见其中一座时，它所呈现的是一个连续的范围．假想，视线是一个被分成360份的圆，每份代表1度．每度被分成60份，称为“分”．又将“分”分成60份，称“秒”．为了精确的记录自己视线里山的范围，约翰写下了每座山的角度范围．如：</span></div>
<div><span style="font-size: medium">范围34：始于45度2分59秒，终于120度10分0秒</span></div>
<div><span style="font-size: medium">    约翰发现不同的山所占的角度可能会重叠，且没有一座山的范围超过180度（所以不必担心范围所指的是顺时针还是逆时针）．上例中，山占的总范围是270421秒．约翰希望计算出视线中被山所占范围的总秒数．</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第1行：一个整数N.</span></div>
<div><span style="font-size: medium">    第2到N+1行：每行描述一座山的范围，包含6个分开的整数．前3个表示起始的角度（度，</span></div>
<div><span style="font-size: medium">分，秒），后三个数表示终止的角度（度，分，秒）．</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">    一个单独的整数，表示约翰视线中被山所占范围的总秒数．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">    3<br/>
    45  2  59  60  30  30<br/>
    50  10  2  1 20  1 0  0<br/>
    355  0  0  356  0  0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">    274021<br/>
<br/>
样例说明<br/>
    前两个范围有重叠，总秒数为270421;第三个范围为3600秒．</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Orange">Orange</a></p></div>

