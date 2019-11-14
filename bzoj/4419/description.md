
# Description

<div class="content"><div>刚开通的SH微博共有n个用户（1..n标号），在短短一个月的时间内，用户们活动频繁，共有m条按时间顺序的记录：</div>
<div><span class="Apple-tab-span" style="white-space:pre">	</span>! x   表示用户x发了一条微博；</div>
<div><span class="Apple-tab-span" style="white-space:pre">	</span>+ x y 表示用户x和用户y成为了好友</div>
<div><span class="Apple-tab-span" style="white-space:pre">	</span>- x y 表示用户x和用户y解除了好友关系</div>
<div>当一个用户发微博的时候，所有他的好友（直接关系）都会看到他的消息。</div>
<div>假设最开始所有人之间都不是好友关系，记录也都是合法的（即+ x y时x和y一定不是好友，而- x y时x和y一定是好友）。</div>
<div>问这m条记录发生之后，每个用户分别看到了多少条消息。</div>
<p></p></div>

# Input

<div class="content"><div>第1行2个整数n,m。</div>
<div>接下来m行，按时间顺序读入m条记录，每条记录的格式如题目所述，用空格隔开。</div>
<p></p></div>

# Output

<div class="content"><div>输出一行n个用空格隔开的数（行末无空格），第i个数表示用户i最后看到了几条消息。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 8<br/>
! 1<br/>
! 2<br/>
+ 1 2<br/>
! 1<br/>
! 2<br/>
- 1 2<br/>
! 1<br/>
! 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 1<br/>
只有第4和第5条记录对应的消息被看到过。其他消息发送时，1和2不是好友。<br/>
<br/>
对100%的数据，N&lt;=200000，M&lt;=500000<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

