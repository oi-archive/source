
# Description

<div class="content"><p><span style="font-size: medium"> 众所周知，Hzwer学长是一名高富帅，他打算投入巨资发展一些小城市。<br/>
 Hzwer打算在城市中开N个宾馆，由于Hzwer非常壕，所以宾馆必须建在空中，但是这样就必须建立宾馆之间的连接通道。机智的Hzwer在宾馆中修建了N-1条隧道，也就是说，宾馆和隧道形成了一个树形结构。<br/>
 Hzwer有时候会花一天时间去视察某个城市，当来到一个城市之后，Hzwer会分析这些宾馆的顾客情况。对于每个顾客，Hzwer用三个数值描述他：（S， T， V）表示该顾客这天想要从宾馆S走到宾馆T，他的速度是V。<br/>
 Hzwer需要做一些收集一些数据，这样他就可以规划他接下来的投资。<br/>
 其中有一项数据就是收集所有顾客可能的碰面次数。<br/>
 每天清晨，顾客同时从S出发以V的速度前往T（注意S可能等于T），当到达了宾馆T的时候，顾客显然要找个房间住下，那么别的顾客再经过这里就不会碰面了。特别的，两个顾客同时到达一个宾馆是可以碰面的。同样，两个顾客同时从某宾馆出发也会碰面。</span></p></div>

# Input

<div class="content"><p><font size="4"> 第一行一个正整数T(1&lt;=T&lt;=20)，表示Hzwer发展了T个城市，并且在这T个城市分别视察一次。<br/>
 对于每个T，第一行有一个正整数N(1&lt;=N&lt;=10^5)表示Hzwer在这个城市开了N个宾馆。<br/>
 接下来N-1行，每行三个整数X，Y，Z表示宾馆X和宾馆Y之间有一条长度为Z的隧道<br/>
 再接下来一行M表示这天顾客的数量。<br/>
 紧跟着M行每行三个整数（S， T， V）表示该顾客会从宾馆S走到宾馆T，速度为v</font></p></div>

# Output

<div class="content"><p><font size="4"> 对于每个T，输出一行，表示顾客的碰面次数。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata"> 1<br/>
 3<br/>
 1 2 1<br/>
 2 3 1<br/>
 3<br/>
 1 3 2<br/>
 3 1 1<br/>
 1 2 3<br/>
 1<br/>
 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 2<br/>
 0<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">【数据规模】<br/><br/>
 1&lt;=T&lt;=20   1&lt;=N&lt;=10^5   0&lt;=M&lt;=10^3   1&lt;=V&lt;=10^6   1&lt;=Z&lt;=10^3<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

