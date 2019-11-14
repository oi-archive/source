
# Description

<div class="content"><div>有n条河流的发源地，有m个汇合点，每个汇合点都有若干条河流汇合，最后所有的河流汇合到一个点。给每个河流</div>
<div>定义一个长度，即从汇合终点开始，遇到分叉即只保留一条主干，剩下的都是支流。现在对于每条河流询问最好可</div>
<div>能的排名。n,m&lt;=500000。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含两个整数n(1&lt;n&lt;=500000)代表河流源头数，m(0&lt;=m&lt;n)表示汇合点数，这些汇合点被标号为1~m。</div>
<div>接下来n行描述河流，每行包含一个字符串（长度不超过10），表示河流源头的名字，</div>
<div>然后有两个整数c(0&lt;=c&lt;=m)和d(1&lt;=d&lt;=10^9)，c表示离其最近的河流下游交汇处的标号，d是到交汇处的距离。</div>
<div>最后m行描述交汇点1~m。每行两个数该交汇点下游最近的交汇点和距离。</div></div>

# Output

<div class="content"><p>输出n行，每行输出河流的名字和最高的可能排名。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 3<br/>
Chi 1 1047<br/>
Mekong 2 2650<br/>
Mun 1 800<br/>
Nan 3 710<br/>
Salween 0 2815<br/>
Yom 3 787<br/>
2 100<br/>
0 1700<br/>
0 30<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Chi 1<br/>
Mekong 1<br/>
Mun 3<br/>
Nan 6<br/>
Salween 1<br/>
Yom 4<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Yts1999上传，lbn187提供译文">鸣谢Yts1999上传，lbn187提供译文</a></p></div>

