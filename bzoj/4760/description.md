
# Description

<div class="content"><div>You have probably heard of the game &#34;Rock, Paper, Scissors&#34;. The cows like to play a similar game th</div>
<div>ey call &#34;Hoof, Paper, Scissors&#34;</div>
<div>你可能玩过石头剪刀布这个游戏，奶牛们也喜欢玩类似的游戏，叫做“蹄子剪刀布”</div>
<div>The rules of &#34;Hoof, Paper, Scissors&#34; are simple. Two cows play against each-other. They both count t</div>
<div>o three and then each simultaneously makes a gesture that represents either a hoof, a piece of paper</div>
<div>, or a pair of scissors. Hoof beats scissors (since a hoof can smash a pair of scissors), scissors b</div>
<div>eats paper (since scissors can cut paper), and paper beats hoof (since the hoof can get a papercut).</div>
<div> For example, if the first cow makes a &#34;hoof&#34; gesture and the second a &#34;paper&#34; gesture, then the sec</div>
<div>ond cow wins. Of course, it is also possible to tie, if both cows make the same gesture.</div>
<div></div>
<div>蹄子剪刀布的规则和石头剪刀布的规则是一样的，蹄子踩碎剪刀，剪刀剪布，布包蹄子</div>
<div></div>
<div>Farmer John wants to play against his prize cow, Bessie, at N games of &#34;Hoof, Paper, Scissors&#34; (1≤N</div>
<div>≤100,000). Bessie, being an expert at the game, can predict each of FJ&#39;s gestures before he makes i</div>
<div>t. Unfortunately, Bessie, being a cow, is also very lazy. As a result, she tends to play the same ge</div>
<div>sture multiple times in a row. In fact, she is only willing to switch gestures at most KK times over</div>
<div> the entire set of games (0≤K≤20). For example, if K=2, she might play &#34;hoof&#34; for the first few ga</div>
<div>mes, then switch to &#34;paper&#34; for a while, then finish the remaining games playing &#34;hoof&#34;.</div>
<div></div>
<div>现在FJ想要和他的最机智的奶牛Bessie玩蹄子剪刀布（我也不知道FJ为什么有蹄子），一共进行了N轮(N&lt;=1e5)，B</div>
<div>essie，作为一个奶牛，非常的怠惰，无论她出什么，都喜欢连续的出，最多变化K次(K&lt;=20)，也就是说，对于她</div>
<div>所出的，记为序列f(i)，记sum=有多少个i满足f(i)!=f(i-1)(i&gt;1)，而她的sum一定不会超过k</div>
<div>Given the sequence of gestures FJ will be playing, please determine the maximum number of games that</div>
<div> Bessiecan win.</div>
<div></div>
<div>现在FJ已经给出了他出的东西，你要告诉Bessie，在不确定她出的东西的情况下，她最多能赢多少次</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of the input file contains N and K.</div>
<div>输入数据第一行为N,K</div>
<div>The remaining N lines contains FJ&#39;s gestures, each either H, P, or S</div>
<div>接下来N行表示FJ所出的东西，H表示hoof,P表示paper,S表示Scissors</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div></div>
<div>
<div>Print the maximum number of games Bessie can win, given that she can only change gestures at most KK times.</div>
<div>输出在变化不超过K次的前提下，最多能赢多少次</div>
</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 1<br/>
P<br/>
P<br/>
H<br/>
P<br/>
S</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

