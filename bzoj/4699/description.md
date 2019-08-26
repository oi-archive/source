
# Description

<div class="content"><div>
<div>下水道的主干路由n个节点和n-l条边组成，每条边有一个通过它所需的时间Ti。换言之，这是一棵n个节点的带权</div>
<div>树。现在，要用最快的速度赶往目标节点k。下水道有一些塌陷，这导致主干路的某一段路径可以通过该塌陷到另</div>
<div>一条路径。对于一个塌陷，我们用(L1，ri，L2，R2，c)来描述，即对于主干路上L1到R1路径上的任意节点x，L2到</div>
<div>r2路径上的任意节点y，都可以在c的时间内从x走到y。因为不知道自己所在的到底是哪个节点，所以要求出每个节</div>
<div>点到目标节点K的最短距离。注意边是单向的</div>
<div></div>
</div>
<p></p></div>

# Input

<div class="content"><div>
<div style="font-size: 11.8181819915771px;">第一行两个数n，m，k，表示节点数、塌陷数和目标节点编号，空格分隔。</div>
<div style="font-size: 11.8181819915771px;">接下来n-l行，每行3个数x,y,t，表示主干路的一条边连接点x,y，通过的时间为t。</div>
<div style="font-size: 11.8181819915771px;">接下来m行，每行5个数L1，r1，L2，r2，c，表示一个塌陷。</div>
<div style="font-size: 11.8181819915771px;">N&lt;=250000  </div>
<div style="font-size: 11.8181819915771px;">m&lt;=100000</div>
<div style="font-size: 11.8181819915771px;">1 &lt; = L1,L2, R1, R2,x,y &lt; = N</div>
<div style="font-size: 11.8181819915771px;">1&lt; = t,c&lt; = 2^31-1。</div>
</div>
<p></p></div>

# Output

<div class="content"><div>n行，每行一个数，表示第i个节点到第k个节点的最短路径长度。</div>
<div>特别的，在第k行你应当输出0。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3 5<br/>
1 2 100<br/>
2 3 100<br/>
3 4 100<br/>
4 5 100<br/>
1 2 4 5 200<br/>
2 2 4 4 90<br/>
3 3 2 2 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">200<br/>
190<br/>
195<br/>
100<br/>
0</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

