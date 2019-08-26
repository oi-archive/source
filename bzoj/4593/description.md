
# Description

<div class="content"><div>曾经发明了零件组装机的发明家SHTSC又公开了他的新发明：聚变反应炉--一种可以产生大量清洁能量的神秘装置</div>
<div>。众所周知，利用核聚变产生的能量有两个难点：一是控制核聚变反应的反应强度，二是使用较少的能量激发聚变</div>
<div>反应。而SHTSC已经完美解决了第一个问题。一个聚变反应炉由若干个相连的聚变块组成，为了能够使得聚变反应</div>
<div>可控，SHTSC保证任意两个聚能块都可以通过相互之间的链接到达，并且没有一个聚能块可以不重复经过一个链接</div>
<div>回到它自己。但是第二个问题SHTSC还没有完全解决。在他设计的聚变反应炉当中，每个聚变块都需要一定的初始</div>
<div>能量di来进行激发，不过SHTSC不需要手动激发所有聚变块，这是因为一旦一个聚变块被激发，则会向与其直接相</div>
<div>连的所有还未被激发的聚变块传送ci个单位的能量。这样后被触发的聚变块可以以更低的初始能量来激发，甚至可</div>
<div>能不需要额外的外界能量就可自行激发，从而降低了总激发能量的消耗。现在给出了一个聚变反应炉，求至少要多</div>
<div>少能量才能激发所有聚变块。</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个整数n。表示共有n个聚能块，由1-n编号。</div>
<div>第二行n个整数，表示di。</div>
<div>第三行n个整数，表示ci。</div>
<div>以下n-1行每行两个整数，u，v。表示编号为u和v的聚能块是相连的。</div>
<div>输入保证符合题目描述。</div>
<div></div>
<div>Type A ：ci &lt;= 1,有 n&lt;=100000。</div>
<div>Type B ：ci &lt;= 5,有n&lt;=2000。</div>
<div>对于所有的数据，1&lt;=di, Sum(di)&lt;=10^9。输入保证符合题目描述。</div>
<p></p></div>

# Output

<div class="content"><div>一行一个整数，表示至少需要多少个单位的能量才能激发所有聚变块。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 1 1 1 1<br/>
1 1 1 1 1<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
//样例1：只需要触发任意一个聚变块即可激活整个聚变反应装置。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

