
# Description

<div class="content"><div>众所周知，萌萌哒六花不擅长数学，所以勇太给了她一些数学问题做练习。但是今天六花酱不想做数学题，于是他</div>
<div>们开始打牌。现在他们手上有m张不同的牌，牌有两种：普通牌和功能牌。功能牌一共有n张，每张功能牌都有一个</div>
<div>属性值wi，保证Sigma(wi)=m,1&lt;=i&lt;=N现在勇太将这m张牌随机打乱（一共有m!种不同的顺序）。一开始，六花先从</div>
<div>牌堆顶端取一张牌。接着每回合六花可以选择手中的一张牌打出，如果这张牌是普通牌，那么什么都不会发生；如</div>
<div>果这种牌是功能牌，那么六花需要从牌堆顶端再取wi张牌。重复这个过程直到六花手中没有手牌或六花要摸牌的时</div>
<div>候牌堆已经空了，如果是前者，则勇太胜利，否则六花胜利。举例来说，如果牌堆是{3，0，2，0，0）（用0表示</div>
<div>普通牌，其他数字表示wi），那么六花打牌的过程可以为：</div>
<div>1)取一张牌，手中的牌为{3}。</div>
<div>2)打出{3}，再取三张牌，手中的牌为{0，2，0}。</div>
<div>3)打出这三张牌，还需要再取两张，取到第二张的时候牌堆中已没有牌，六花胜利。</div>
<div>而如果牌堆是{2，0，0，3,0}，不难发现是勇太大胜利。现在，六花想要知道，这M!种顺序中，有多少种是能让自</div>
<div>己取得胜利的呢。当然这个问题对萌萌哒六花来说实在是太雉了，所以她来向你寻求帮助，你能帮帮她吗。</div></div>

# Input

<div class="content"><div>第一行一个整数n。</div>
<div>第二行他个空格隔开的正整数wi。</div>
<div>通过输入你可以自己算出来m=Sigma(Wi),1&lt;=i&lt;=N</div>
<div>n≤40，1&lt;wi≤10^5</div></div>

# Output

<div class="content"><div>输出一个整数表示答案，答案可能很大，你只需要输出对998244353取模后的结果。</div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
样例解释一<br/>
m!种牌堆中，{3，0，0），{0，3，0）{0，0，3）各有两个，其中只有第一种满足条件。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

