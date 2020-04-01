
# Description

<div class="content"><div>在遥远的S星系中一共有N个星球，编号为1…N。其中的一些星球决定组成联盟，以方便相互间的交流。但是，组成</div>
<div>联盟的首要条件就是交通条件。初始时，在这N个星球间有M条太空隧道。每条太空隧道连接两个星球，使得它们能</div>
<div>够相互到达。若两个星球属于同一个联盟，则必须存在一条环形线路经过这两个星球，即两个星球间存在两条没有</div>
<div>公共隧道的路径。为了壮大联盟的队伍，这些星球将建设P条新的太空隧道。这P条新隧道将按顺序依次建成。一条</div>
<div>新轨道建成后，可能会使一些星球属于同一个联盟。你的任务是计算出，在一条新隧道建设完毕后，判断这条新轨</div>
<div>道连接的两个星球是否属于同一个联盟，如果属于同一个联盟就计算出这个联盟中有多少个星球。</div>
<p></p></div>

# Input

<div class="content"><div>第1行三个整数N，M和P，分别表示总星球数，初始时太空隧道的数目和即将建设的轨道数目。</div>
<div>第2至第M+1行，每行两个整数，表示初始时的每条太空隧道连接的两个星球编号。</div>
<div>第M+2行至第M+P+1行，每行两个整数，表示新建的太空隧道连接的两个星球编号。</div>
<div>这些太空隧道按照输入的顺序依次建成。</div>
<div>1≤N,M,P≤200000</div>
<p></p></div>

# Output

<div class="content"><div>输出共P行。</div>
<div>如果这条新的太空隧道连接的两个星球属于同一个联盟，就输出一个整数，表示这两个星球所在联盟的星球数。</div>
<div>如果这条新的太空隧道连接的两个星球不属于同一个联盟，就输出&#34;No&#34;（不含引号）。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3 4<br/>
1 2<br/>
4 3<br/>
4 5<br/>
2 3<br/>
1 3<br/>
4 5<br/>
2 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">No<br/>
3<br/>
2<br/>
5</span></div>

# Hint

<div class="content"><p></p><p><img src="/source/bzoj/4998/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwOC8xMSgxKS5wbmc=.png" width="737" height="430" alt=""/></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

