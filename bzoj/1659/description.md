
# Description

<div class="content"><div><span style="font-size: medium">奶牛们喜欢在黑暗中睡觉。每天晚上，他们的牲口棚有L（3&lt;=L&lt;=50）盏灯，他们想让亮着的灯尽可能的少。他们知道按钮开关的位置，但喜闻乐见的是他们并没有手指。你得到了一个长度为T（1&lt;=T&lt;=7）的插槽用以帮助奶牛们改变灯的状态。</span></div>
<div></div></div>

# Input

<div class="content"><div>
<div><span style="font-size: medium">第一行，两个整数L和T。第二行给出一个长度为L的01串表示初始灯的状态，0表示灯是灭的，1表示灯是亮的。第三行给出一个长度为T的01串，表示你获得的插槽。</span></div>
</div></div>

# Output

<div class="content"><div><span style="font-size: medium">第一行输出一个整数K，表示在满足亮着的灯最少的情况下，你要用插槽操作的次数。第二行到第K+1行，每行一个整数表示你的插槽使用的位置。</span></div>
<div><span style="background-color: rgb(255, 0, 0);"><span style="font-size: medium;">&#34;</span><span style="font-size: medium;">K最小的解，并且满足解的字典序最大（即按钮开关的位置尽可能靠后）&#34;</span></span></div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 4<br/>
1111111111<br/>
1101<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
1<br/>
3<br/>
4<br/>
6<br/>
7<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>使用5次插槽<br/><br/>
1111111111  初始状态<br/><br/>
0010111111  对第一个位置使用插槽<br/><br/>
0001101111  对第三个位置使用插槽<br/><br/>
0000000111  对第四个位置使用插槽<br/><br/>
0000011101  对第六个位置使用插槽<br/><br/>
0000010000  对第七个位置使用插槽<br/><br/>
可以证明这是满足字典序最小的最优解。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

