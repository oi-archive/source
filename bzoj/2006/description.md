
# Description

<div class="content"><div>小Z是一个小有名气的钢琴家，最近C博士送给了小Z一架超级钢琴，小Z希望能够用这架钢琴创作出世界上最美妙的</div>
<div>音乐。 这架超级钢琴可以弹奏出n个音符，编号为1至n。第i个音符的美妙度为Ai，其中Ai可正可负。 一个“超级</div>
<div>和弦”由若干个编号连续的音符组成，包含的音符个数不少于L且不多于R。我们定义超级和弦的美妙度为其包含的</div>
<div>所有音符的美妙度之和。两个超级和弦被认为是相同的，当且仅当这两个超级和弦所包含的音符集合是相同的。 </div>
<div>小Z决定创作一首由k个超级和弦组成的乐曲，为了使得乐曲更加动听，小Z要求该乐曲由k个不同的超级和弦组成。</div>
<div>我们定义一首乐曲的美妙度为其所包含的所有超级和弦的美妙度之和。小Z想知道他能够创作出来的乐曲美妙度最</div>
<div>大值是多少。</div></div>

# Input

<div class="content"><div>
<div>第一行包含四个正整数n, k, L, R。其中n为音符的个数，k为乐曲所包含的超级和弦个数，L和R分别是超级和弦所</div>
<div>包含音符个数的下限和上限。 接下来n行，每行包含一个整数Ai，表示按编号从小到大每个音符的美妙度。</div>
<div>N&lt;=500,000</div>
<div>k&lt;=500,000</div>
<div>-1000&lt;=Ai&lt;=1000,1&lt;=L&lt;=R&lt;=N且保证一定存在满足条件的乐曲</div>
</div></div>

# Output

<div class="content"><p>只有一个整数，表示乐曲美妙度的最大值。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3 2 3<br/>
3<br/>
2<br/>
-6<br/>
8</span></div>

# Sample Output

<div class="content"><span class="sampledata">11<br/>
<br/>
【样例说明】<br/>
共有5种不同的超级和弦：<br/>
音符1 ~ 2，美妙度为3 + 2 = 5 <br/>
音符2 ~ 3，美妙度为2 + (-6) = -4 <br/>
音符3 ~ 4，美妙度为(-6) + 8 = 2 <br/>
音符1 ~ 3，美妙度为3 + 2 + (-6) = -1 <br/>
音符2 ~ 4，美妙度为2 + (-6) + 8 = 4 <br/>
最优方案为：乐曲由和弦1，和弦3，和弦5组成，美妙度为5 + 2 + 4 = 11。</span></div>

# Hint

<div class="content"><p></p><div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

