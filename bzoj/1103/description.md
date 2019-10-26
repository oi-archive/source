
# Description

<div class="content"><p>　　在经济全球化浪潮的影响下,习惯于漫步在清晨的乡间小路的邮递员Blue Mary也开始骑着摩托车传递邮件了。<br/>
不过，她经常回忆起以前在乡间漫步的情景。昔日，乡下有依次编号为1..n的n个小村庄，某些村庄之间有一些双<br/>
向的土路。从每个村庄都恰好有一条路径到达村庄1（即比特堡）。并且，对于每个村庄，它到比特堡的路径恰好<br/>
只经过编号比它的编号小的村庄。另外，对于所有道路而言，它们都不在除村庄以外的其他地点相遇。在这个未开<br/>
化的地方，从来没有过高架桥和地下铁道。随着时间的推移，越来越多的土路被改造成了公路。至今，Blue Mary<br/>
还清晰地记得最后一条土路被改造为公路的情景。现在，这里已经没有土路了——所有的路都成为了公路，而昔日<br/>
的村庄已经变成了一个大都市。 Blue Mary想起了在改造期间她送信的经历。她从比特堡出发，需要去某个村庄，<br/>
并且在两次送信经历的间隔期间,有某些土路被改造成了公路.现在Blue Mary需要你的帮助：计算出每次送信她需<br/>
要走过的土路数目。（对于公路，她可以骑摩托车；而对于土路，她就只好推车了。）</p></div>

# Input

<div class="content"><p>　　第一行是一个数n(1 &lt; = n &lt; = 2 50000).以下n-1行，每行两个整数a，b（1 &lt; =  a以下一行包含一个整数m<br/>
（1 &lt; = m &lt; = 2 50000），表示Blue Mary曾经在改造期间送过m次信。以下n+m-1行，每行有两种格式的若干信息<br/>
，表示按时间先后发生过的n+m-1次事件:若这行为 A a b(a若这行为 W a, 则表示Blue Mary曾经从比特堡送信到<br/>
村庄a。</p></div>

# Output

<div class="content"><p>　　有m行，每行包含一个整数，表示对应的某次送信时经过的土路数目。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2<br/>
1 3<br/>
1 4<br/>
4 5<br/>
4<br/>
W 5<br/>
A 1 4<br/>
W 5<br/>
A 4 5<br/>
W 5<br/>
W 2<br/>
A 1 2<br/>
A 1 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1<br/>
0<br/>
1</span></div>

# Hint

<div class="content"><p></p><p><img border="0" alt="" src="/source/bzoj/1103/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzExMDMuanBn.jpg"/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

