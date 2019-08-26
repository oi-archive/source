
# Description

<div class="content"><div style="margin: 8.7pt 0cm"><span style="font-size: medium">Sxyz里有一群sx。</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">在花老师的指导下，每周4都有一个集会活动，俗称“浇水”活动。</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">为了让花老师开花，这群sx都很努力地发言。</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">一次xbj对树很关心，总想有一道树的好题目</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">所以大家就开始讨论有什么树的好操作。</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">为了让题目变的简单，花老师开始就规定了是有根树。</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium"> </span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">何其蛙：子树修改，加一个数什么的，显然是可做的。</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">Dj：换根不是超开心？</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">Dd：什么子树min，max也不错啊。</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">Zzw：链上询问min也放进去吧。</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">Wyk: 链max当然的吧。</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">Xbj：如果不能换父亲就太无聊了吧。</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">Gy：链加。</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">Monkey：链上和。</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">Shjj：链上修改。</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">Wtd：子树加。</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">Sone: 在线就不说什么了吧...</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">.............</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium"> </span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">最后大家发现有这道题目有点麻烦..都懒得写，又由于sone最近被3083的遥远的国度中lct被树剖虐暴了..就担任了出题活动.......</span></div></div>

# Input

<div class="content"><div style="margin: 8.7pt 0cm"><span style="font-size: medium">第一行是N和M，表示有这棵树有N个点M个询问</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">然后是N-1行，每行x,y表示x-y有一条边</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">接下去是N行，每行是一个数字，表示每个点的权值</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">后面一行表示根</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">接下来是M行</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">第一个数字是K</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">K=0 表示子树修改，后面x,y，表示以x为根的子树的点权值改成y</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">K=1 表示换根，后面x，表示把这棵树的根变成x</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">K=2 表示链修改，后面x,y,z，表示把这棵树中x-y的路径上点权值改成z</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">K=3 表示子树询问min，后面x，表示以x为根的子树中点的权值min</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">K=4 表示子树询问max，后面x，表示以x为根的子树中点的权值max</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">K=5 表示子树加，后面x,y，表示x为根的子树中点的权值+y</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">K=6 表示链加，后面x,y,z，表示把这棵树中x-y的路径上点权值改成+z</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">K=7 表示链询问min，后面x,y，表示把这棵树中x-y的路径上点的min</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">K=8 表示链询问max，后面x,y，表示把这棵树中x-y的路径上点的max</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">K=9 表示换父亲，后面x,y，表示把x的父亲换成y，如果y在x子树里不操作。</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">K=10 表示链询问sum，后面x,y,z，表示表示把这棵树中x-y的路径上点的sum</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">K=11 表示子树询问sum，后面x，表示以x为根的子树的点权sum</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium"><b><span style="color: blue">Output</span></b></span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">对于每个询问输出一个答案。</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium"><b><span style="color: blue">Sample Input</span></b></span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">Input1: </span></div>
<div><span style="font-size: medium">5 5</span></div>
<div><span style="font-size: medium">2 1</span></div>
<div><span style="font-size: medium">3 1</span></div>
<div><span style="font-size: medium">4 1</span></div>
<div><span style="font-size: medium">5 2</span></div>
<div><span style="font-size: medium">4</span></div>
<div><span style="font-size: medium">1</span></div>
<div><span style="font-size: medium">4</span></div>
<div><span style="font-size: medium">1</span></div>
<div><span style="font-size: medium">2</span></div>
<div><span style="font-size: medium">1</span></div>
<div><span style="font-size: medium">10 2 3</span></div>
<div><span style="font-size: medium">3 1</span></div>
<div><span style="font-size: medium">7 3 4</span></div>
<div><span style="font-size: medium">6 3 3 2</span></div>
<div><span style="font-size: medium">9 5 1</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium"> </span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium">Input2: </span></div>
<div><span style="font-size: medium">10 12</span></div>
<div><span style="font-size: medium">2 1</span></div>
<div><span style="font-size: medium">3 2</span></div>
<div><span style="font-size: medium">4 2</span></div>
<div><span style="font-size: medium">5 3</span></div>
<div><span style="font-size: medium">6 4</span></div>
<div><span style="font-size: medium">7 5</span></div>
<div><span style="font-size: medium">8 2</span></div>
<div><span style="font-size: medium">9 4</span></div>
<div><span style="font-size: medium">10 9</span></div>
<div><span style="font-size: medium">791</span></div>
<div><span style="font-size: medium">868</span></div>
<div><span style="font-size: medium">505</span></div>
<div><span style="font-size: medium">658</span></div>
<div><span style="font-size: medium">860</span></div>
<div><span style="font-size: medium">623</span></div>
<div><span style="font-size: medium">393</span></div>
<div><span style="font-size: medium">717</span></div>
<div><span style="font-size: medium">410</span></div>
<div><span style="font-size: medium">173</span></div>
<div><span style="font-size: medium">4</span></div>
<div><span style="font-size: medium">0 8 800</span></div>
<div><span style="font-size: medium">1 4</span></div>
<div><span style="font-size: medium">2 8 2 103</span></div>
<div><span style="font-size: medium">3 9</span></div>
<div><span style="font-size: medium">4 4</span></div>
<div><span style="font-size: medium">5 7 304</span></div>
<div><span style="font-size: medium">6 8 8 410</span></div>
<div><span style="font-size: medium">7 10 8</span></div>
<div><span style="font-size: medium">8 1 8</span></div>
<div><span style="font-size: medium">9 6 9</span></div>
<div><span style="font-size: medium">10 2 3</span></div>
<div><span style="font-size: medium">11 5</span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium"><b> </b></span></div>
<div style="margin: 8.7pt 0cm"><span style="font-size: medium"><b><span style="color: blue">Sample Output</span></b></span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">Output1:</span></div>
<div><span style="font-size: medium">9</span></div>
<div><span style="font-size: medium">1</span></div>
<div><span style="font-size: medium">1</span></div>
<div><span style="font-size: medium">Output2:</span></div>
<div><span style="font-size: medium">173</span></div>
<div><span style="font-size: medium">860</span></div>
<div><span style="font-size: medium">103</span></div>
<div><span style="font-size: medium">791</span></div>
<div><span style="font-size: medium">608</span></div>
<div><span style="font-size: medium">1557</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">数据范围：</span></div>
<div><span style="font-size: medium">N,M&lt;=100000</span></div>
<div><span style="font-size: medium">中间所有的值计算在c++的int内</span></div></div>

# Output

<div class="content"></div>

# Sample Input

<div class="content"><span class="sampledata"></span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Sone提供">Sone提供</a></p></div>

