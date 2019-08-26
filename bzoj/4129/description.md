
# Description

<div class="content"><p> Haruna每天都会给提督做早餐！ 这天她发现早饭的食材被调皮的 Shimakaze放到了一棵</p>
<div>树上，每个结点都有一样食材，Shimakaze要考验一下她。</div>
<div>每个食材都有一个美味度，Shimakaze会进行两种操作：</div>
<div>1、修改某个结点的食材的美味度。</div>
<div>2、对于某条链，询问这条链的美味度集合中，最小的未出现的自然数是多少。即mex值。</div>
<div>请你帮帮Haruna吧。</div>
<div></div></div>

# Input

<div class="content"><p>第一行包括两个整数n，m，代表树上的结点数(标号为1~n)和操作数。</p>
<div>第二行包括n个整数a1...an，代表每个结点的食材初始的美味度。</div>
<div>接下来n-1行，每行包括两个整数u，v，代表树上的一条边。</div>
<div>接下来m 行，每行包括三个整数</div>
<div>0 u x 代表将结点u的食材的美味度修改为 x。</div>
<div>1 u v 代表询问以u，v 为端点的链的mex值。</div>
<div></div></div>

# Output

<div class="content"><p>对于每次询问，输出该链的mex值。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">10 10<br/>
1 0 1 0 2 4 4 0 1 0<br/>
1 2<br/>
2 3<br/>
2 4<br/>
2 5<br/>
1 6<br/>
6 7<br/>
2 8<br/>
3 9<br/>
9 10<br/>
0 7 14<br/>
1 6 6<br/>
0 4 9<br/>
1 2 2<br/>
1 1 8<br/>
1 8 3<br/>
0 10 9<br/>
1 3 5<br/>
0 10 0<br/>
0 7 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
1<br/>
2<br/>
2<br/>
3</span></div>

# Hint

<div class="content"><p></p><p>1&lt;=n&lt;=5*10^4</p><br/>
<div>1&lt;=m&lt;=5*10^4</div><br/>
<div>0&lt;=ai&lt;=10^9</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

