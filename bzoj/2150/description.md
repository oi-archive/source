
# Description

<div class="content"><div>lanzerb的部落在A国的上部，他们不满天寒地冻的环境，于是准备向A国的下部征战来获得更大的领土。 A国是一</div>
<div>个M*N的矩阵，其中某些地方是城镇，某些地方是高山深涧无人居住。lanzerb把自己的部落分成若干支军队，他们</div>
<div>约定： </div>
<div>1. 每支军队可以从任意一个城镇出发，并只能从上往向下征战，不能回头。</div>
<div>途中只能经过城镇，不能经过高山深涧。 </div>
<div>2. 如果某个城镇被某支军队到过，则其他军队不能再去那个城镇了。 </div>
<div>3. 每支军队都可以在任意一个城镇停止征战。 </div>
<div>4. 所有军队都很奇怪，他们走的方法有点像国际象棋中的马。</div>
<div>不过马每次只能走1*2的路线，而他们只能走R*C的路线。 </div>
<div>lanzerb的野心使得他的目标是统一全国，但是兵力的限制使得他们在配备人手时力不从心。假设他们每支军队都</div>
<div>能顺利占领这支军队经过的所有城镇，请你帮lanzerb算算至少要多少支军队才能完成统一全国的大业。</div></div>

# Input

<div class="content"><div>第一行包含4个整数M、N、R、C，意义见问题描述。</div>
<div>接下来M行每行一个长度为N的字符串。</div>
<div>如果某个字符是&#39;.&#39;，表示这个地方是城镇；如果这个字符时&#39;x&#39;，表示这个地方是高山深涧。</div>
<div>1&lt;=M,N&lt;=50，1&lt;=R,C&lt;=10。</div></div>

# Output

<div class="content"><p>输出一个整数，表示最少的军队个数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入一】<br/>
3 3 1 2<br/>
...<br/>
.x.<br/>
... <br/>
【样例输入二】<br/>
5 4 1 1<br/>
....<br/>
..x.<br/>
...x<br/>
....<br/>
x...<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">【样例输出一】<br/>
4<br/>
<br/>
【样例输出二】<br/>
5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

