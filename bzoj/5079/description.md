
# Description

<div class="content"><div>你在一个秘密据点门口安装了监控探头，希望监控人员出入情况。探头记录了据点某天从早到晚的人员进出情况，</div>
<div>你不知道据点内开始的人数。同时，进出据点的人可能会进行伪装，你无法从探头记录中得知伪装的人的身份。探</div>
<div>头的每条记录是以下两个形式之一：</div>
<div>E id</div>
<div>当id&gt;0时，表示编号为id的人进入了这个据点；当id为0时，表示一个伪装的人进入了据点。</div>
<div>L id</div>
<div>当id&gt;0时，表示编号为id的人离开了这个据点；当id为0时，表示一个伪装的人离开了据点。</div>
<div></div>
<div>你想弄清楚，这个据点是不是一定有其他出入口，如果没有的话，当一天结束时，待在据点里的人的最少可能数量是多少。</div>
<div></div>
<div>
<div></div>
</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个数T，表示数据组数。</div>
<div>对于每组数据，第一行一个整数N，表示记录数量。</div>
<div>下面N行，每行一个记录，为E id或L id。</div>
<div>N &lt;= 1000，T &lt;= 10, 0 &lt;= id &lt;= 2000。</div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每个数据输出一行，如果该据点一定有其他出入口，输出OTHER。</div>
<div>否则，输出这天结束时据点里的最少可能人数。</div>
<div></div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3<br/>
E 5<br/>
L 0<br/>
E 5<br/>
2<br/>
L 1<br/>
L 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
OTHER</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

