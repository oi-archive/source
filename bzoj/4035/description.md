
# Description

<div class="content"><div>
<div>有一个长度为N的数组，甲乙两人在上面进行这样一个游戏：首先，数组上有一些格子是白的，有一些是黑的。然</div>
<div>后两人轮流进行操作。每次操作选择一个白色的格子，假设它的下标为x。接着，选择一个大小在1~n/x之间的整数</div>
<div>k，然后将下标为x、2x、...、kx的格子都进行颜色翻转。不能操作的人输。现在甲（先手）有一些询问。每次他</div>
<div>会给你一个数组的初始状态，你要求出对于这种初始状态他是否有必胜策略。</div>
</div>
<div></div></div>

# Input

<div class="content"><div>
<div>
<div>接下来2*K行，每两行表示一次询问。在这两行中，第一行一个正整数W，表示数组中有多少个格子是白色的，第二</div>
<div>行则有W个1~N之间的正整数，表示白色格子的对应下标。</div>
</div>
</div></div>

# Output

<div class="content"><p> 对于每个询问，若先手必胜输出&#34;Yes&#34;，否则输出&#34;No&#34;。答案之间用换行隔开</p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
2<br/>
2<br/>
1 2<br/>
2<br/>
2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">Yes<br/>
No<br/>
【样例解释】<br/>
在第一个询问中，甲选择点1，然后将格子1*1和2*1翻过来即可。<br/>
第二个询问中，无论甲选择哪个点，都只能翻掉一个格子。乙只需<br/>
翻掉另一个格子就行了。<br/>
N&lt;=1000000000 ， K,W&lt;=100 ， 不会有格子在同<br/>
一次询问中多次出现。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢bhiaibogf提供">鸣谢bhiaibogf提供</a></p></div>

