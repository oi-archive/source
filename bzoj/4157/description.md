
# Description

<div class="content"><div>环网曾经是人类文明史上的奇迹，银河系中的无数星球被时空之门联系在一起，从此时间和空间不再是阻碍。一旦两个星球之间建立了时空联系，那么通过时空之门可以在一瞬间从一个星球到达另外一个星球。人类文明因此以前所未有的速度扩张到银河系的每个角落。</div>
<div><span class="Apple-tab-span" style="white-space:pre">	</span>在被称为末日浩劫的上古事件中，人工智能消失了，而时空之门从此再也没有响应人类的呼唤。人类文明的n个星球中，如今只剩下k个尚有人类居住，而他们只能进行简单的实时通讯，再也不能互相访问。</div>
<div><span class="Apple-tab-span" style="white-space:pre">	</span>更可怕的事情发生了，某个尚有人类居住的星球r上爆发了电子瘟疫。这种瘟疫大肆破坏人类的电子植入设备，几乎毁灭了r星。r星被毁灭之前传送过来的信息证实该电子瘟疫和上古人工智能的相似性将会允许它们通过部分上古时空之门。由于时空之门已经有几个世纪没人维护了，所以电子瘟疫利用时空之门进行的传送甚至不是双向的。</div>
<div><span class="Apple-tab-span" style="white-space:pre">	</span>为了阻止电子瘟疫，人类决定使用他们剩余的总和为w的空间能量对环网中的某个星球进行空间打击（可以是r星）。空间打击可以让一个星球彻底消失。然而由于星球的参数不同，打击每个星球需要的空间能是不一样的。人类指挥官很想知道，人类能否打击某个星球使得电子瘟疫不能到达剩下的k-1个人类居住星，如果能的话，最小需要多少空间能。注意到如果电子瘟疫本来就不能到达剩下的k-1个人类居住星，那么就不需要打击了。</div>
<div><span class="Apple-tab-span" style="white-space:pre">	</span>由于多重宇宙的存在，在不同宇宙中，k个人类居住点是不同的，为此，我们将对你进行多组询问。</div>
<p class="MsoNormal"></p>
<p></p></div>

# Input

<div class="content"><div><span class="Apple-tab-span" style="white-space: pre;">	</span>第1行两个整数n，m，r。表示环网的星球数量、电子瘟疫尚能利用的时空连接数量以及r星的编号。</div>
<div><span class="Apple-tab-span" style="white-space: pre;">	</span>第2行到第m+1行，每行两个整数u[i]，v[i]。表示电子瘟疫可以从u[i]星利用时空之门传送到v[i]星，这个传送不是双向的。保证每个有序对u[i]，v[i]只会出现最多一次，而且不存在u[i]=v[i]。</div>
<div><span class="Apple-tab-span" style="white-space: pre;">	</span>第m+2行有n个整数e[i]，表示打击每个星球需要的空间能。</div>
<div><span class="Apple-tab-span" style="white-space: pre;">	</span>第m+3行有一个整数q。表示有q组询问。</div>
<div><span class="Apple-tab-span" style="white-space: pre;">	</span>对于每组询问，第1行有两个整数t(t=k-1)，w。表示除了r星以外尚有t个星球有人居住，w表示人类空间能总和，</div>
<div><span class="Apple-tab-span" style="white-space: pre;">	</span>接下来一行有t个数字，是这t个星球的编号。</div>
<p></p></div>

# Output

<div class="content"><div>对于每组询问，如果人类无法阻止瘟疫到达某个人类居住星球，请输出1。否则输出最小需要的空间能。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 7 3<br/>
4 1<br/>
1 5<br/>
3 4<br/>
2 4<br/>
3 1<br/>
1 3<br/>
1 6<br/>
3 0 8 6 1 8<br/>
3<br/>
2 9<br/>
1 2<br/>
2 0<br/>
6 2<br/>
2 4<br/>
5 2<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
1<br/>
3<br/>
</span></div>

# Hint

<div class="content"><p></p><div>2&lt;=n&lt;=2*10^5</div><br/>
<div>0&lt;=m&lt;=5*10^5</div><br/>
<div>0&lt;=e[i]&lt;=10^9</div><br/>
<div>1&lt;=q&lt;=5*10^5</div><br/>
<div>1&lt;=t&lt;=n-1</div><br/>
<div>1&lt;=∑t&lt;=5*10^5</div><br/>
<div>0&lt;=w&lt;=10^9</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Martin">By Martin</a></p></div>

