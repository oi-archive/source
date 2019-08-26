
# Description

<div class="content"><div></div>
<div style="text-indent: 21.75pt">最近A、B两国发生了一场战争，dick，作为A国的军事总指挥，最近非常头痛于己方的情报问题。因为B国最近雇佣了Easy这一位密码专家来给他们的所有通讯加密。</div>
<div style="text-indent: 21.75pt">Easy是一个非常喜欢唱歌，于是他决定将所有的信号都变成旋律储存起来，比如说11556654433221就可能是一段加过密的音符，我们用一个等长度的序列来表示它，就变成了1,1,5,5,6,6……。为了增加密码的保密性，他把加密的乐谱又调整了一下，把某些音调改变了，将原序列A变成B，有|A| = |B|，且对于a[i] = a[j]有b[i] = b[j]、对a[i] &lt; a[j]有b[i] &lt; b[j]、对a[i] &gt; a[j]有b[i] &gt; b[j]。那么11221和55775就可能代表了同一段音符。</div>
<div style="text-indent: 21.75pt">最近，dick截获了一段信号，这段信号中可能包含了某些重要信息。根据以往的经验，dick已经知道了某些旋律所代表的意义，于是dick想知道，对于一段已知的旋律，能不能判断它是否在这段截获的旋律中出现？如果出现了，能否找出它出现的次数及位置呢？</div>
<div> </div>
<div>[任务]</div>
<div><span>    </span>判断给定旋律在截获旋律中出现的次数及位置。</div>
<div> </div></div>

# Input

<div class="content"><p><span>    </span>本题只有一组数据。</p>
<div style="text-indent: 21.75pt">第一行三个正整数n、m、s，n（n &lt;= 100000）是截获旋律的长度，m(m&lt;=25000是已知旋律的长度，所有的旋律都是[1..s](s&lt;=25)的正整数；</div>
<div style="text-indent: 21.75pt">然后n个整数描述截获旋律A；</div>
<div style="text-indent: 21.75pt">然后m个整数描述已知旋律B。</div>
<div> </div></div>

# Output

<div class="content"><div style="text-indent: 21.75pt">第一行一个整数tot，表示出现的次数。</div>
<div style="text-indent: 21.75pt">然后tot行，按照从小到大给出出现时的起始位置p（即有A[p..p + m – 1]等价于B）。</div>
<div> </div></div>

# Sample Input

<div class="content"><span class="sampledata">9 6 10<br/>
5 6 2 10 10 7 3 2 9<br/>
1 4 4 3 2 1<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

