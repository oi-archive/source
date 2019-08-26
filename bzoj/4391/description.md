
# Description

<div class="content"><p>Bessie the cow is a huge fan of card games, which is quite surprising, given her lack of opposable thumbs. Unfortunately, none of the other cows in the herd are good opponents. They are so bad, in fact, that they always play in a completely predictable fashion! Nonetheless, it can still be a challenge for Bessie to figure out how to win.<br/>
<br/>
Bessie and her friend Elsie are currently playing a simple card game where they take a deck of 2N cards, conveniently numbered 1…2N, and divide them into N cards for Bessie and N cards for Elsie. The two then play NN rounds, where in each round Bessie and Elsie both play a single card. Initially, the player who plays the highest card earns a point. However, at one point during the game, Bessie can decide to switch the rules so that for the rest of the game, the player who plays the lowest card wins a point. Bessie can choose not to use this option, leaving the entire game in &#34;high card wins&#34; mode, or she can even invoke the option right away, making the entire game follow the &#34;low card wins&#34; rule.<br/>
<br/>
Given that Bessie can predict the order in which Elsie will play her cards, please determine the maximum number of points Bessie can win.</p>
<p></p>
<p>奶牛Bessie和Elsie在玩一种卡牌游戏。一共有2N张卡牌，点数分别为1到2N，每头牛都会分到N张卡牌。</p>
<p>游戏一共分为N轮，因为Bessie太聪明了，她甚至可以预测出每回合Elsie会出什么牌。</p>
<p>每轮游戏里，两头牛分别出一张牌，点数大者获胜。</p>
<p>同时，Bessie有一次机会选择了某个时间点，从那个时候开始，每回合点数少者获胜。</p>
<p>Bessie现在想知道，自己最多能获胜多少轮？</p>
<p></p></div>

# Input

<div class="content"><p>The first line of input contains the value of N (2≤N≤50,000).<br/>
<br/>
The  next N lines contain the cards that Elsie will play in each of the  successive rounds of the game. Note that it is easy to determine  Bessie&#39;s cards from this information.</p></div>

# Output

<div class="content"><p>Output a single line giving the maximum number of points Bessie can score.</p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1<br/>
8<br/>
4<br/>
3</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p><p>Here, Bessie must have cards 2, 5, and 6, and 7 in her hand, and she can use these to win at most 3 points. For example, she can defeat the 1 card and then switch the rules to &#34;low card wins&#34;, after which she can win two more rounds.</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum鸣谢Claris提供译文">Platinum鸣谢Claris提供译文</a></p></div>

