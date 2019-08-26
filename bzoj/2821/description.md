
# Description

<div class="content"><div>神犇SJY虐完HEOI之后给傻×LYD出了一题：SHY是T国的公主，平时的一大爱好是作诗。由于时间紧迫，SHY作完诗</div>
<div>之后还要虐OI，于是SHY找来一篇长度为N的文章，阅读M次，每次只阅读其中连续的一段[l,r]，从这一段中选出一</div>
<div>些汉字构成诗。因为SHY喜欢对偶，所以SHY规定最后选出的每个汉字都必须在[l,r]里出现了正偶数次。而且SHY认</div>
<div>为选出的汉字的种类数（两个一样的汉字称为同一种）越多越好（为了拿到更多的素材！）。于是SHY请LYD安排选</div>
<div>法。LYD这种傻×当然不会了，于是向你请教……问题简述：N个数，M组询问，每次问[l,r]中有多少个数出现正偶</div>
<div>数次。</div>
<p></p></div>

# Input

<div class="content"><div>输入第一行三个整数n、c以及m。表示文章字数、汉字的种类数、要选择M次。第二行有n个整数，每个数Ai在[1, c</div>
<div>]间，代表一个编码为Ai的汉字。接下来m行每行两个整数l和r，设上一个询问的答案为ans(第一个询问时ans=0)，</div>
<div>令L=(l+ans)mod n+1, R=(r+ans)mod n+1，若L&gt;R，交换L和R，则本次询问为[L,R]。</div>
<p></p></div>

# Output

<div class="content"><p>输出共m行，每行一个整数，第i个数表示SHY第i次能选出的汉字的最多种类数。</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3 5<br/>
1 2 2 3 1<br/>
0 4<br/>
1 2<br/>
2 2<br/>
2 3<br/>
3 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
0<br/>
0<br/>
0<br/>
1</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，1&lt;=n,c,m&lt;=10^5</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By lydrainbowcat">By lydrainbowcat</a></p></div>

