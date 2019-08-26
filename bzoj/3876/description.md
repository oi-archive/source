
# Description

<div class="content"><div>【故事背景】</div>
<div>宅男JYY非常喜欢玩RPG游戏，比如仙剑，轩辕剑等等。不过JYY喜欢的并不是战斗场景，而是类似电视剧一般的充满恩怨情仇的剧情。这些游戏往往</div>
<div>都有很多的支线剧情，现在JYY想花费最少的时间看完所有的支线剧情。</div>
<div>【问题描述】</div>
<div>JYY现在所玩的RPG游戏中，一共有N个剧情点，由1到N编号，第i个剧情点可以根据JYY的不同的选择，而经过不同的支线剧情，前往Ki种不同的新的剧情点。当然如果为0，则说明i号剧情点是游戏的一个结局了。</div>
<div>JYY观看一个支线剧情需要一定的时间。JYY一开始处在1号剧情点，也就是游戏的开始。显然任何一个剧情点都是从1号剧情点可达的。此外，随着游戏的进行，剧情是不可逆的。所以游戏保证从任意剧情点出发，都不能再回到这个剧情点。由于JYY过度使用修改器，导致游戏的“存档”和“读档”功能损坏了，</div>
<div>所以JYY要想回到之前的剧情点，唯一的方法就是退出当前游戏，并开始新的游戏，也就是回到1号剧情点。JYY可以在任何时刻退出游戏并重新开始。不断开始新的游戏重复观看已经看过的剧情是很痛苦，JYY希望花费最少的时间，看完所有不同的支线剧情。</div></div>

# Input

<div class="content"><div>输入一行包含一个正整数N。</div>
<div>接下来N行，第i行为i号剧情点的信息；</div>
<div>第一个整数为，接下来个整数对，Bij和Tij，表示从剧情点i可以前往剧</div>
<div>情点，并且观看这段支线剧情需要花费的时间。</div>
<div></div></div>

# Output

<div class="content"><p> 输出一行包含一个整数，表示JYY看完所有支线剧情所需要的最少时间。</p>
<div></div>
<div></div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
2 2 1 3 2<br/>
2 4 3 5 4<br/>
2 5 5 6 6<br/>
0<br/>
0<br/>
0</span></div>

# Sample Output

<div class="content"><span class="sampledata">24</span></div>

# Hint

<div class="content"><p></p><p> JYY需要重新开始3次游戏，加上一开始的一次游戏，4次游戏的进程是</p><br/>
<div>1-&gt;2-&gt;4，1-&gt;2-&gt;5，1-&gt;3-&gt;5和1-&gt;3-&gt;6。</div><br/>
<div></div><br/>
<div>对于100%的数据满足N&lt;=300,0&lt;=Ki&lt;=50,1&lt;=Tij&lt;=300,Sigma(Ki)&lt;=5000</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round2 By 佚名上传">Round2 By 佚名上传</a></p></div>

