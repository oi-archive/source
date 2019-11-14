
# Description

<div class="content"><p class="MsoPlainText">物理学家小<span lang="EN-US">C</span>的研究正遇到某个瓶颈。<span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoPlainText">他正在研究的是一个星系，这个星系中有<span lang="EN-US">n</span>个星球，其中有一个主星球<span lang="EN-US">(</span>方便起见我们默认其为<span lang="EN-US">1</span>号星球<span lang="EN-US">)</span>，其余的所有星球均有且仅有一个依赖星球。主星球没有依赖星球。<span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoPlainText">我们定义依赖关系如下：若星球<span lang="EN-US">a</span>的依赖星球是<span lang="EN-US">b,</span>则有星球<span lang="EN-US">a</span>依赖星球<span lang="EN-US">b.</span>此外，依赖关系具有传递性，即若星球<span lang="EN-US">a</span>依赖星球<span lang="EN-US">b,</span>星球<span lang="EN-US">b</span>依赖星球<span lang="EN-US">c,</span>则有星球<span lang="EN-US">a</span>依赖星球<span lang="EN-US">c.<o:p></o:p></span></p>
<p class="MsoPlainText">对于这个神秘的星系中，小<span lang="EN-US">C</span>初步探究了它的性质，发现星球之间的依赖关系是无环的。并且从星球<span lang="EN-US">a</span>出发只能直接到达它的依赖星球<span lang="EN-US">b.<o:p></o:p></span></p>
<p class="MsoPlainText">每个星球<span lang="EN-US">i</span>都有一个能量系数<span lang="EN-US">wi.</span>小<span lang="EN-US">C</span>想进行若干次实验，第<span lang="EN-US">i</span>次实验，他将从飞船上向星球<span lang="EN-US">di</span>发射一个初始能量为<span lang="EN-US">0</span>的能量收集器，能量收集器会从星球<span lang="EN-US">di</span>开始前往主星球，并收集沿途每个星球的部分能量，收集能量的多少等于这个星球的能量系数。<span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoPlainText">但是星系的构成并不是一成不变的，某些时刻，星系可能由于某些复杂的原因发生变化。<span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoPlainText">有些时刻，某个星球能量激发，将使得所有依赖于它的星球以及他自己的能量系数均增加一个定值。还有可能在某些时刻，某个星球的依赖星球会发生变化，但变化后依然满足依赖关系是无环的。<span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoPlainText">现在小<span lang="EN-US">C</span>已经测定了时刻<span lang="EN-US">0</span>时每个星球的能量系数<span lang="EN-US">,</span>以及每个星球<span lang="EN-US">(</span>除了主星球之外<span lang="EN-US">)</span>的依赖星球。接下来的<span lang="EN-US">m</span>个时刻，每个时刻都会发生一些事件。其中小<span lang="EN-US">C</span>可能会进行若干次实验，对于他的每一次实验，请你告诉他这一次实验能量收集器的最终能量是多少。<span lang="EN-US"><o:p></o:p></span></p></div>

# Input

<div class="content"><p class="MsoPlainText">第一行一个整数<span lang="EN-US">n,</span>表示星系的星球数。</p>
<p class="MsoPlainText">接下来<span lang="EN-US">n-1</span>行每行一个整数<span lang="EN-US">,</span>分别表示星球<span lang="EN-US">2-n</span>的依赖星球编号。<span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoPlainText">接下来一行<span lang="EN-US">n</span>个整数，表示每个星球在时刻<span lang="EN-US">0</span>时的初始能量系数<span lang="EN-US">wi.<o:p></o:p></span></p>
<p class="MsoPlainText">接下来一行一个整数<span lang="EN-US">m,</span>表示事件的总数。<span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoPlainText">事件分为以下三种类型。<span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoPlainText"><span lang="EN-US">(1)&#34;Q di&#34;</span>表示小<span lang="EN-US">C</span>要开始一次实验<span lang="EN-US">,</span>收集器的初始位置在星球<span lang="EN-US">di.<o:p></o:p></span></p>
<p class="MsoPlainText"><span lang="EN-US">(2)&#34;C xi yi&#34;</span>表示星球<span lang="EN-US">xi</span>的依赖星球变为了星球<span lang="EN-US">yi.<o:p></o:p></span></p>
<p class="MsoPlainText"><span lang="EN-US">(3)&#34;F pi qi&#34;</span>表示星球<span lang="EN-US">pi</span>能量激发，常数为<span lang="EN-US">qi.<o:p></o:p></span></p>
<p class="MsoPlainText"></p>
<p class="MsoPlainText"></p>
<p></p></div>

# Output

<div class="content"><div>
<p class="MsoPlainText">对于每一个事件类型为<span lang="EN-US">Q</span>的事件，输出一行一个整数，表示此次实验的收集器最终能量。<span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoPlainText"></p>
</div>
<div>
<p></p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1<br/>
1<br/>
4 5 7<br/>
5<br/>
Q 2<br/>
F 1 3<br/>
Q 2<br/>
C 2 3<br/>
Q 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">9<br/>
15<br/>
25</span></div>

# Hint

<div class="content"><p></p><p>n&lt;=100000,m&lt;=300000,1&lt;di,xi&lt;=n,wi,qi&lt;=100000.保证操作合法。<span style="color: rgb(255, 0, 0);">注意<span style="font-family: arial, verdana, helvetica, sans-serif;">w_i&gt;=0</span></span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

