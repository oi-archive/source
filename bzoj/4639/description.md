
# Description

<div class="content"><div>浏览到好图好句的时候，为了避免被删帖、封图、和谐，博士会掏出他的选取器，将</div>
<div>好图好句框住，然后Ctrl+C，Ctrl+V。博士从初一开始坚持到现在，已经有2GB了。在反复</div>
<div>地与吧主斗争之后,博士总结出了经验。</div>
<div>1).对于一篇帖子，可以从上至下分成N个片段，每个片段不可分割，且只有序号相邻的片</div>
<div>段才相邻。</div>
<div>2).每次框选只能框选连续一段片段[L,R]，而且这连续一段片段的总字符量不能超过LIMIT，</div>
<div>否则会出错。</div>
<div>3).对于每次框选与复制，耗时只与这连续一段片段中字符量最大的那一个片段有关，而且</div>
<div>满足正比例函数关系。为了让题目简单，规定耗时等于字符量。</div>
<div>4).两次框选之间的时间间隔可以视为0。</div>
<div>正在博士总结完经验的时候，他瞅到了一篇掺杂大量好图好句的帖子。于是，一场新</div>
<div>的战争爆发了…………战局紧张，博士想知道他的最小耗时是多少。</div>
<div></div></div>

# Input

<div class="content"><div>第一行两个整数N和Limit。N&lt;=300000</div>
<div>接下来的N行，每行一个整数，代表第I个片段的字符量</div>
<div></div></div>

# Output

<div class="content"><div>仅一行，为博士的最小耗时</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">8 17<br/>
2<br/>
2<br/>
2<br/>
8<br/>
1<br/>
8<br/>
2<br/>
1</span></div>

# Sample Output

<div class="content"><span class="sampledata">12<br/>
{解释：222/818/21，2+8+2=12}</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

