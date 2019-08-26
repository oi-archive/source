
# Description

<div class="content"><div><span style="font-size: medium">约翰和他的奶牛组建了一只乐队“后街奶牛”，现在他们正在牧场里排练．奶牛们分成一堆一堆，共N(1≤N≤1000)堆．每一堆里，30只奶牛一只踩在另一只的背上，叠成一座牛塔．牧场里还有M(1≤M≤1000)个高高的草垛． 作为出色的指挥家，约翰可以通过口哨指挥奶牛们移动．他的口哨有四个音，分别能使所有的牛塔向东南西北四个方向移动一格．</span></div>
<div><span style="font-size: medium">    每一次，当一个牛塔到达了一个草垛所在的格子，牛塔最上方的奶牛就会跳到草垛上，而且不再下来，而其他奶牛仍然呈塔状站在草垛所在的格子里．当牛塔只剩一只奶牛时，这只奶牛也会跳到草垛上． 突然，约翰大惊失色：原来邻家的奶缸爆炸了！滚滚而下的牛奶正朝着约翰的牧场冲来，不久就要将牧场淹没．约翰必须马上行动，用口哨声挽救奶牛们的生命．他要指挥奶牛尽量多地跳上草垛，草垛上的奶牛将不会被淹死．    约翰还有K次吹口哨的机会．那他最多还能救多少奶牛呢？请计算最多能挽救的奶牛数，以及达到这个数目约翰需要吹的口哨调子序列．序列用E，W，S，N表示东西南北．如果有多种序列能达到</span></div>
<div><span style="font-size: medium">要求，输出作为字符串最小的．</span></div></div>

# Input

<div class="content"><div></div>
<div></div>
<div></div>
<div>
<div>第1行输入三个整数N，M，K，之后N行每行输入一对整数(Xi，Yi)表示一座牛塔所在的位置，1&lt;=K&lt;=30</div>
<div>之后M行每行输入一对整数(Xi，Yi)表示一个草垛所在的位置．1≤Xi≤1000;1≤Yi≤1000.</div>
</div>
<p></p></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">    第1行输出最多能挽救的奶牛数．第2行输出口哨调子序列．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 6 3 <br/>
3 4 <br/>
6 2 <br/>
5 7 <br/>
8 2 <br/>
9 2 <br/>
6 4 <br/>
5 4 <br/>
6 7 <br/>
8 7 <br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Use the &#39;east&#39; whistle three times, at which point the milk floods<br/>
the area.  Each haystack ends up saving 1 cow.<br/>
<br/>
6 <br/>
EEE <br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

