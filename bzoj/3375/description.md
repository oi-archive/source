
# Description

<div class="content"><div><span style="font-size: medium">    约翰有N(1≤N≤100000)头奶牛，它们都可以控制自己的产奶量．一头产奶不多的奶牛会被其它奶牛嘲笑, 约翰制订一张产奶时间表，第i头奶牛在Ai_Bi时间段里产奶(0≤Ai&lt;Bi≤10^9)．这头奶牛必须在Ai的时候进入奶棚在Bi的时候离开．奶棚的门很小，同一时刻只能有一头奶牛通过． 如果第i头奶牛产奶的时间段包含第j头奶牛产奶的时间段，即A&lt;Aj&lt;Bj&lt;Bi.那么，我们称这两个时间段是“巢段”．  “巢段”是一件很糟糕的事，因为第j头奶牛在奶棚的时间里第i头奶牛一直都在．这样第i头奶牛就能估计第j头奶牛的产奶量．由于产奶量被别的奶牛知道了的奶牛会发疯，所以约翰不希望“巢段”的发生．</span></div>
<div><span style="font-size: medium">    帮助约翰确定最大的k(1≤K≤N)，在1到K的奶牛中不存在“巢段”．</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第1行：奶牛的数量N．</span></div>
<div><span style="font-size: medium">    第2到N+1行：每行有两个用空格隔开的数字，表示这头奶牛的产奶时间段．</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">    一个整数K</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
7 20<br/>
1 4<br/>
3 12<br/>
6 10<br/>
0 3</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 3<br/>
<br/>
样例说明<br/>
    第4头奶牛( 6-10)被包含于第3头奶牛(3-12)．另外，1至3头奶牛不存在“巢段”</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Orange">Orange</a></p></div>

