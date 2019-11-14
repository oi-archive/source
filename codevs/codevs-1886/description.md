<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    “寄没有地址的信，这样的情绪有种距离，你放着谁的歌曲，是怎样的心情。能不能说给我听。<br>    失忆的Eden 总想努力地回忆起过去，然而总是只能清晰地记得那种思念的 感觉，却不能回忆起她的音容笑貌。<br>    记忆中，她总是喜欢给Eden 出谜题：在valentine’s day 的夜晚，两人在闹市 中闲逛时，望着礼品店里精巧玲珑的各式玩偶，她突发奇想，问了Eden 这样的 一个问题：有n 个玩偶，每个玩偶有对应的价值、价钱，每个玩偶都可以被买有 限次，在携带的价钱m 固定的情况下，如何选择买哪些玩偶以及每个玩偶买多少个，才能使得选择的玩偶总价钱不超过m，且价值和最大。</p>
<p>     众所周知的，这是一个很经典的多重背包问题，Eden 很快解决了，不过她似乎因为自己的问题被飞快解决感到了一丝不高兴，于是她希望把问题加难：多次询问，每次询问都将给出新的总价钱，并且会去掉某个玩偶（即这个玩偶不能被选择），再问此时的多重背包的答案（即前一段所叙述的问题）。 <br>    这下Eden 犯难了，不过Eden 不希望自己被难住，你能帮帮他么？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个数n，表示有n 个玩偶，玩偶从0 开始编号<br>第二行开始后面的n 行，每行三个数ai, bi, ci，分别表示买一个第i 个玩偶需<br>要的价钱，获得的价值以及第i 个玩偶的限购次数。<br>接下来的一行为q，表示询问次数。<br>接下来q 行，每行两个数di, ei 表示每个询问去掉的是哪个玩偶（注意玩偶<br>从0 开始编号）以及该询问对应的新的总价钱数。（去掉操作不保留，即不同询问互相独立)</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出q 行，第i 行输出对于第i 个询问的答案。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5<br>2 3 4<br>1 2 1<br>4 1 2<br>2 1 1<br>3 2 3<br>5<br>1 10<br>2 7<br>3 4<br>4 8<br>0 5</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>13<br>11<br>6<br>12<br>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><br>【样例说明】<br>一共五种玩偶，分别的价钱价值和限购次数为(2,3,4)，(1,2,1)，(4,1,2)，(<br>2,1,1)，<br>(3,2,3)。<br>五个询问，以第一个询问为例。第一个询问表示的是去掉编号为1 的玩偶，<br>且拥有的钱数为10 时可以获得的最大价值，则此时剩余玩偶为(2,3,4)，(4,1,2)，<br>(2,1,1)，(3,2,3)，若把编号为0 的玩偶买4 个（即全买了），然后编号为3 的玩偶<br>买一个，则刚好把10 元全部花完，且总价值为13。可以证明没有更优的方案了。<br>注意买某种玩偶不一定要买光。<br>【数据规模与约定】<br>10%数据满足1 ≤ n ≤ 10；<br>另20%数据满足1 ≤ n ≤ 100, ci = 1, 1 ≤ q ≤ 100；<br>另20%数据满足1 ≤ n ≤ 100, 1 ≤ q ≤ 100；<br>另30%数据满足ci = 1；<br>100%数据满足1 ≤ n ≤ 1000, 1 ≤ q ≤ 3*105, 1 ≤ ai、bi、ci ≤ 100, 0 ≤ di &lt; n,<br>0 ≤ ei ≤ 1000。</p>
</div>
</div>