
# Description

<div class="content"><p><span style="font-size: medium">“寄没有地址的信，这样的情绪有种距离，你放着谁的歌曲，是怎样的心心静，能不能说给我听。”<br/>
失忆的Eden总想努力地回忆起过去，然而总是只能清晰地记得那种思念的感觉，却不能回忆起她的音容笑貌。 记忆中，她总是喜欢给Eden出谜题：在 valentine’s day 的夜晚，两人在闹市中闲逛时，望着礼品店里精巧玲珑的各式玩偶，她突发奇想，问了 Eden这样的一个问题：有n个玩偶，每个玩偶有对应的价值、价钱，每个玩偶都可以被买有限次，在携带的价钱m固定的情况下，如何选择买哪些玩偶以及每个玩偶买多少个，才能使得选择的玩偶总价钱不超过m，且价值和最大。众所周知的，这是一个很经典的多重背包问题，Eden很快解决了，不过她似乎因为自己的问题被飞快解决感到了一丝不高兴，于是她希望把问题加难：多次 询问，每次询问都将给出新的总价钱，并且会去掉某个玩偶（即这个玩偶不能被选择），再问此时的多重背包的答案（即前一段所叙述的问题）。  <br/>
这下Eden 犯难了，不过Eden不希望自己被难住，你能帮帮他么？  <br/>
</span></p></div>

# Input

<div class="content"><p><font size="4"> <br/>
第一行一个数n，表示有n个玩偶，玩偶从0开始编号 <br/>
第二行开始后面的 n行，每行三个数 ai, bi, c i，分别表示买一个第i个玩偶需<br/>
要的价钱，获得的价值以及第i个玩偶的限购次数。 <br/>
接下来的一行为q，表示询问次数。 <br/>
接下来q行，每行两个数di. ei表示每个询问去掉的是哪个玩偶（注意玩偶从0开始编号）以及该询问对应的新的总价钱数。（去掉操作不保留，即不同询问互相独立） <br/>
</font></p></div>

# Output

<div class="content"><p><font size="4"> <br/>
输出q行，第i行输出对于第 i个询问的答案。 <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 <br/>
2  3 4<br/>
1  2 1<br/>
4  1 2<br/>
2  1 1<br/>
3  2 3<br/>
5 <br/>
1  10 <br/>
2  7<br/>
3  4<br/>
4  8<br/>
0  5<br/>
 <br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">13 <br/>
11 <br/>
6 <br/>
12 <br/>
4 <br/>
 <br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"> <br/><br/>
一共五种玩偶，分别的价钱价值和限购次数为 (2,3,4)， (1,2,1)， (4,1,2)， (2,1,1)，(3,2,3)。五个询问，以第一个询问为例。第一个询问表示的是去掉编号为1的玩偶，且拥有的钱数为10时可以获得的最大价值，则此时剩余玩偶为(2,3,4)，(4,1,2)，(2,1,1)，(3,2,3)，若把编号为0的玩偶买4个（即全买了），然后编号为3的玩偶买一个，则刚好把10元全部花完，且总价值为13。可以证明没有更优的方案了。注意买某种玩偶不一定要买光。 </span></p><br/>
<p><span style="font-size: medium">100. 数据满足1 ≤ n ≤ 1000, 1 ≤ q ≤ 3*105 , 1 ≤  a<br/><br/>
 <br/><br/>
i、bi、c i ≤ 100, 0 ≤ d i &lt; n,  0  ≤ei ≤ 1000。 <br/><br/>
 <br/><br/>
 <br/><br/>
 </span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

