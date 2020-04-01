
# Description

<div class="content"><div>省选临近，放飞自我的小Q无心刷题，于是怂恿小C和他一起颓废，玩起了一款战略游戏。</div>
<div>这款战略游戏的地图由n个城市以及m条连接这些城市的双向道路构成，并且从任意一个城市出发总能沿着道路走到</div>
<div>任意其他城市。现在小C已经占领了其中至少两个城市，小Q可以摧毁一个小C没占领的城市，同时摧毁所有连接这</div>
<div>个城市的道路。只要在摧毁这个城市之后能够找到某两个小C占领的城市u和v，使得从u出发沿着道路无论如何都不</div>
<div>能走到v，那么小Q就能赢下这一局游戏。</div>
<div>小Q和小C一共进行了q局游戏，每一局游戏会给出小C占领的城市集合S</div>
<div>你需要帮小Q数出有多少个城市在他摧毁之后能够让他赢下这一局游戏。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数T，表示测试数据的组数，</div>
<div>对于每组测试数据，</div>
<div>第一行是两个整数n和m，表示地图的城市数和道路数，</div>
<div>接下来m行，每行包含两个整数u和v~(1&lt;=u&lt;v&lt;=n)</div>
<div>表示第u个城市和第v个城市之间有一条道路，同一对城市之间可能有多条道路连接，</div>
<div>第m+1是一个整数q，表示游戏的局数，</div>
<div>接下来q行，每行先给出一个整数|S|(2&lt;=|S|&lt;=n)</div>
<div>表示小C占领的城市数量，然后给出|S|个整数s1,s2,...s|S|,(1&lt;=s1&lt;s2&lt;s|S|&lt;=n)，表示小C占领的城市。</div>
<div>1&lt;= T&lt;= 10，</div>
<div>2&lt;= n&lt;= 10^5 且 n-1&lt;= m&lt;= 2*10^5，</div>
<div>1&lt;= q&lt;= 10^5，</div>
<div>对于每组测试数据，有Sigma|S|&lt;= 2*10^5</div>
<p></p></div>

# Output

<div class="content"><div>对于每一局游戏，输出一行，包含一个整数，表示这一局游戏中有多少个城市在小Q摧毁之后能够让他赢下这一局游戏。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
7 6<br/>
1 2<br/>
1 3<br/>
2 4<br/>
2 5<br/>
3 6<br/>
3 7<br/>
3<br/>
2 1 2<br/>
3 2 3 4<br/>
4 4 5 6 7<br/>
6 6<br/>
1 2<br/>
1 3<br/>
2 3<br/>
1 4<br/>
2 5<br/>
3 6<br/>
4<br/>
3 1 2 3<br/>
3 1 2 6<br/>
3 1 5 6<br/>
3 4 5 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
1<br/>
3<br/>
0<br/>
1<br/>
2<br/>
3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

