
# Description

<div class="content"><div>幸福幼儿园 B29 班的粟粟是一个聪明机灵、乖巧可爱的小朋友，她的爱好是画画和读书，尤其喜欢 Thomas H. Co</div>
<div>rmen 的文章。粟粟家中有一个 R行C 列的巨型书架，书架的每一个位置都摆有一本书，上数第i 行、左数第j 列</div>
<div>摆放的书有Pi,j页厚。粟粟每天除了读书之外，还有一件必不可少的工作就是摘苹果，她每天必须摘取一个指定的</div>
<div>苹果。粟粟家果树上的苹果有的高、有的低，但无论如何凭粟粟自己的个头都难以摘到。不过她发现， 如果在脚</div>
<div>下放上几本书，就可以够着苹果；她同时注意到，对于第 i 天指定的那个苹果，只要她脚下放置书的总页数之和</div>
<div>不低于Hi，就一定能够摘到。由于书架内的书过多，父母担心粟粟一天内就把所有书看完而耽误了上幼儿园，于是</div>
<div>每天只允许粟粟在一个特定区域内拿书。这个区域是一个矩形，第 i 天给定区域的左上角是上数第 x1i行的左数</div>
<div>第 y1i本书，右下角是上数第 x2i行的左数第y2i本书。换句话说，粟粟在这一天，只能在这﹙x2i－x1i＋1﹚×﹙</div>
<div>y2i－y1i＋1﹚本书中挑选若干本垫在脚下，摘取苹果。粟粟每次取书时都能及时放回原位，并且她的书架不会再</div>
<div>撤下书目或换上新书，摘苹果的任务会一直持续 M天。给出每本书籍的页数和每天的区域限制及采摘要求，请你告</div>
<div>诉粟粟，她每天至少拿取多少本书，就可以摘到当天指定的苹果。</div></div>

# Input

<div class="content"><div>第一行是三个正整数R，C，M。</div>
<div>接下来是一个R行C列的矩阵，从上到下、从左向右依次给出了每本书的页数Pi，j。</div>
<div>接下来M行，第i行给出正整数x1i，y1i，x2i，y2i，Hi，表示第i天的指定区域是﹙x1i，y1i﹚与﹙x2i，y2i﹚间</div>
<div>的矩形，总页数之和要求不低于Hi。</div>
<div>保证1≤x1i≤x2i≤R，1≤y1i≤y2i≤C。</div></div>

# Output

<div class="content"><div>有M行，第i 行回答粟粟在第 i 天时为摘到苹果至少需要 拿取多少本书。如果即使取走所有书都无法摘到苹果，</div>
<div>则在该行输出“Poor QLW” （不含引号）。</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 5 7 <br/>
14 15 9 26 53 <br/>
58 9 7 9 32 <br/>
38 46 26 43 38<br/>
32 7 9 50 28 <br/>
8 41 9 7 17 <br/>
1 2 5 3 139 <br/>
3 1 5 5 399 <br/>
3 3 4 5 91 <br/>
4 1 4 1 33 <br/>
1 3 5 4 185 <br/>
3 3 4 3 23 <br/>
3 1 3 3 108 </span></div>

# Sample Output

<div class="content"><span class="sampledata">6 <br/>
15 <br/>
2 <br/>
Poor QLW <br/>
9 <br/>
1 <br/>
3 </span></div>

# Hint

<div class="content"><p></p><div>对于 10%的数据，满足 R, C≤10； </div><br/>
<div>对于 20%的数据，满足 R, C≤40； </div><br/>
<div>对于 50%的数据，满足 R, C≤200，M≤200,000； </div><br/>
<div>另有 50%的数据，满足 R＝1，C≤500,000，M≤20,000； </div><br/>
<div>对于 100%的数据，满足 1≤Pi,j≤1,000，1≤Hi≤2,000,000,000</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=第一轮Day2">第一轮Day2</a></p></div>

