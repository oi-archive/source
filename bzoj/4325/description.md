
# Description

<div class="content"><p> 牛牛最近迷上了一种叫斗地主的扑克游戏。斗地主是一种使用黑桃、红心、梅花、方片的A到K加上大小王的共54张牌来进行的扑克牌游戏。在斗地主中，牌的大小关系根据牌的数码表示如下：3&lt;4&lt;5&lt;6&lt;7&lt;8&lt;9&lt;10&lt;J&lt;Q&lt;K&lt;A&lt;2&lt;小王&lt;大王，而花色并不对牌的大小产生影响。每一局游戏中，一副手牌由n张牌组成。游戏者每次可以根据规定的牌型进行出牌，首先打光自己的手牌一方取得游戏的胜利。现在，牛牛只想知道，对于自己的若干组手牌，分别最少需要多少次出牌可以将它们打光。请你帮他解决这个问题。需要注意的是，本题中游戏者每次可以出手的牌型与一般的斗地主相似而略有不同。具体规则如下：</p>
<p><img src="/source/bzoj/4325/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUxMS8xMS5QTkc=.PNG" width="706" height="747" alt=""/></p></div>

# Input

<div class="content"><p>第一行包含用空格隔开的2个正整数T,N，表示手牌的组数以及每组手牌的张数。</p>
<div>接下来T组数据，每组数据N行，每行一个非负整数对Ai,Bi，表示一张牌，其中Ai表示牌的数码,Bi表示牌的花色，中间用空格隔开。特别的，我们用1来表示数码A，11表示数码J，12表示数码Q，13表示数码K；黑桃、红心、梅花、方片分别用1-4来表示；小王的表示方法为01，大王的表示方法为02。</div>
<div></div></div>

# Output

<div class="content"><p>共T行，每行一个整数，表示打光第T组手牌的最少次数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">1 8<br/>
7 4<br/>
8 4<br/>
9 1<br/>
10 4<br/>
11 1<br/>
5 1<br/>
1 4<br/>
1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p><p> 共有1组手牌，包含8张牌：方片7，方片8，黑桃9，方片10，黑桃J，黑桃5，方</p><br/>
<div>片A以及黑桃A。可以通过打单顺子（方片7，方片8，黑桃9，方片10，黑桃J），单张</div><br/>
<div>牌（黑桃5）以及对子牌（黑桃A以及方片A）在3次内打光。</div><br/>
<div></div><br/>
<div>T&lt;=10</div><br/>
<div>N&lt;=23</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

