
# Description

<div class="content"><div>农夫小Q将他的奶牛们饲养在一个长n宽m的矩形网格牧场中。行从上到下依次编号为1到n，列从左往右依次编号为1</div>
<div>到m。为了防止奶牛们逃跑，小Q在牧场外圈安装了一排电网，只要奶牛走出这个n*m的矩形，就会触电死去。在牧</div>
<div>场中，有e个格子塌陷了，一旦奶牛踩在上面，就会掉下去摔死。小Q为了饲养尽可能多的奶牛，在每个没有塌陷的</div>
<div>格子上，都饲养着一头奶牛。tangjz偷走了小Q的口哨，并用口哨向奶牛们依次施放了q条指令，每条指令包含两个</div>
<div>参数d和k，d表示上下左右之一的方向，k表示前进步数。发出指令后，每头奶牛都会听话地执行指令，甚至会因此</div>
<div>丧生。所有奶牛移动完毕之后，tangjz才会施放下一条指令。请写一个程序统计每条指令中小Q损失了多少头奶牛</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含4个正整数n,m,e,q(1&lt;=n,m,q&lt;=2000,0&lt;=e&lt;=min(nm,2000))</div>
<div>分别表示牧场的长宽、塌陷的格子数以及指令数。</div>
<div>接下来e行，每行两个正整数x_i,y_i(1&lt;=x_i&lt;=n,1&lt;=y_i&lt;=m)</div>
<div>表示每个塌陷格子的坐标。输入数据保证每个格子不会被描述多次。</div>
<div>接下来q行，每行包含一个字符d和一个正整数k(1&lt;=k&lt;=2000)</div>
<div>描述每条指令。其中UDLR分别表示上下左右。</div>
<div></div></div>

# Output

<div class="content"><div>输出q行，每行一个整数，即第i条指令中损失的奶牛数量。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 5 3 4<br/>
1 4<br/>
2 2<br/>
3 3<br/>
R 2<br/>
L 1<br/>
D 2<br/>
U 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">10<br/>
0<br/>
2<br/>
0</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=claris原创，本oj版权所有,翻版必究">claris原创，本oj版权所有,翻版必究</a></p></div>

