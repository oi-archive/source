
# Description

<div class="content"><div><span style="font-size: medium">【背景】</span></div>
<div><span style="font-size: medium">    lll6924在某游戏中有n件装备。</span></div>
<div><span style="font-size: medium">【描述】</span></div>
<div><span style="font-size: medium">    游戏中共有m种属性，装备有属性加成。当将A装备合成到B装备上时，A装备消失，B装备的所有小于A装备的属性更新为A装备的这个属性。然而lll6924的记性不太好，因为装备很多，所以一些属性常常记错，他在合成时会突然想起，某个装备的某个属性的初始值应该是多少（暂且认为修改后是正确的，这个属性可能会被修改多次）（请注意，这是理解题意的难点，请结合样例）。在合成过程中lll6924想知道一些装备的一些属性（根据之前给出的数据（初始属性、合成、修改），输出装备当前认为是正确的属性）。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    输入有n+1+q行，第一行有三个用空格隔开的正整数n、m、q，q表示操作（合成操作、询问操作和修改操作）数。接下来的n行，每行有m个用空格隔开的正整数，表示这个装备的各个属性。接下来的q行，每行格式为“k a b c”，若k为1，则为将第a个装备合成到第b个装备，输入数据保证a、b装备存在，此时c=0。若k为2，则为询问第a个装备的第b个属性（若第a个装备已被合成掉，则输出该装备在被合成前的第b个属性是多少），此时c=0。若k为3，则为将第a个装备的第b个属性的初始值更新为c（注意，若a装备已被合成掉，该操作仍然有效，会影响他合成到的装备的属性）。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">    输出如输入格式所述，每个输出占一行。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 5 10<br/>
1 2 3 4 3<br/>
0 0 0 0 0<br/>
2 0 0 0 0<br/>
1 1 2 0<br/>
2 2 3 0<br/>
3 2 4 5<br/>
1 2 3 0<br/>
3 1 3 2<br/>
2 3 1 0<br/>
3 3 1 0<br/>
2 3 1 0<br/>
2 3 4 0<br/>
2 2 3 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
2<br/>
1<br/>
5<br/>
2<br/>
【数据范围及约定】<br/>
100%的数据，0＜n≤1500,0＜m≤400，0＜q≤200000，0≤装备属性≤50000。<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img height="487" alt="" width="606" src="source/bzoj/3443/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMi8xMS5qcGc=.jpg"/></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By lll6924 at“冬令营后竞速放松赛”">By lll6924 at“冬令营后竞速放松赛”</a></p></div>

