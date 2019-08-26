
# Description

<div class="content"><p><span style="font-size: medium">某一天WJMZBMR在打osu~~~但是他太弱逼了，有些地方完全靠运气:(<br/>
我们来简化一下这个游戏的规则<br/>
有n次点击要做，成功了就是o，失败了就是x，分数是按comb计算的，连续a个comb就有a*a分，comb就是极大的连续o。<br/>
比如ooxxxxooooxxx，分数就是2*2+4*4=4+16=20。<br/>
Sevenkplus闲的慌就看他打了一盘，有些地方跟运气无关要么是o要么是x，有些地方o或者x各有50%的可能性，用?号来表示。<br/>
比如oo?xx就是一个可能的输入。<br/>
那么WJMZBMR这场osu的期望得分是多少呢？<br/>
比如oo?xx的话，?是o的话就是oooxx =&gt; 9，是x的话就是ooxxx =&gt; 4<br/>
期望自然就是(4+9)/2 =6.5了<br/>
</span></p></div>

# Input

<div class="content"><p><br/>
<font size="4">第一行一个整数n，表示点击的个数<br/>
接下来一个字符串，每个字符都是ox？中的一个<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">一行一个浮点数表示答案<br/>
四舍五入到小数点后4位<br/>
如果害怕精度跪建议用long double或者extended<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
????<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4.1250<br/>
<br/>
<br/>
n&lt;=300000<br/>
osu很好玩的哦<br/>
WJMZBMR技术还行(雾),x基本上很少呢<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=我们都爱GYZ杯">我们都爱GYZ杯</a></p></div>

