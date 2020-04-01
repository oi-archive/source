
# Description

<div class="content"><div>
<div>小Y是一个心灵手巧的女孩子，她喜欢手工制作一些小饰品。她有n颗小星星，用m条彩色的细线串了起来，每条细</div>
<div>线连着两颗小星星。有一天她发现，她的饰品被破坏了，很多细线都被拆掉了。这个饰品只剩下了n?1条细线，但</div>
<div>通过这些细线，这颗小星星还是被串在一起，也就是这些小星星通过这些细线形成了树。小Y找到了这个饰品的设</div>
<div>计图纸，她想知道现在饰品中的小星星对应着原来图纸上的哪些小星星。如果现在饰品中两颗小星星有细线相连，</div>
<div>那么要求对应的小星星原来的图纸上也有细线相连。小Y想知道有多少种可能的对应方式。只有你告诉了她正确的</div>
<div>答案，她才会把小饰品做为礼物送给你呢。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>
<div>
<div>第一行包含个2正整数n,m，表示原来的饰品中小星星的个数和细线的条数。</div>
<div>接下来m行，每行包含2个正整数u,v，表示原来的饰品中小星星u和v通过细线连了起来。</div>
<div>这里的小星星从1开始标号。保证u≠v，且每对小星星之间最多只有一条细线相连。</div>
<div>接下来n-1行，每行包含个2正整数u,v，表示现在的饰品中小星星u和v通过细线连了起来。</div>
<div>保证这些小星星通过细线可以串在一起。</div>
<div>n&lt;=17,m&lt;=n*(n-1)/2</div>
</div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>
<div>输出共1行，包含一个整数表示可能的对应方式的数量。</div>
<div>如果不存在可行的对应方式则输出0。</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
1 2<br/>
1 3<br/>
1 4<br/>
4 1<br/>
4 2<br/>
4 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">6</span></div>

# Hint

<div class="content"><p></p><p> 题解:<a href="/JudgeOnline/upload/201603/4455.txt">JudgeOnline/upload/201603/4455.tx</a>t</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

