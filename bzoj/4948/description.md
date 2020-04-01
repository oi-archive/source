
# Description

<div class="content"><div>位于热带的 Piconesia 岛国以其秀丽的沙滩、繁茂的植被、可可与咖啡原料的产出以及全年宜人的天气而闻名海</div>
<div>外。天堂般美丽的这里将纳入未来举办 ACM-ICPC 世界总决赛的地点考虑名单中(至少也会是执行委员会度假地点</div>
<div>的选择之一) 。但是还有一个小问题:这个岛真的很难到达。就目前而言,最快的方式是从最近的机场出发,并借助</div>
<div>渔船、油轮、皮划艇和潜艇这些工具,花费三天时间才能到达小岛。为了让大家更轻松地参加 ICPC 世界总决赛,也</div>
<div>为了推动小岛的旅游业发展,Piconesia 正在计划修建它的第一个机场。考虑到越长的起降跑道越有助于对大型飞</div>
<div>机的支持, Piconesia 决定在其岛上修建一条最长的起降跑道带。不幸地是,他们无法确定这条跑道应该设置在哪</div>
<div>里。也许你可以帮个忙?对于本题,我们将 Piconesia 的边界抽象成一个多边形的模型。根据这个多边形,你需要计</div>
<div>算出最长的跑道长度(即最长的线段)使得跑道可以完全在小岛上修建。图 1 对应于第一个输入样例。</div>
<div><img src="/source/bzoj/4948/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwOC8xMS5wbmc=.png" width="322" height="310" alt=""/></div>
<div></div>
<div>图 1. 小岛的多边形模型。最长的跑道已用粗线标出。</div></div>

# Input

<div class="content"><div>第一行包含一个整数 n (3 ≤ n ≤ 200) ,表示多边形的点数。</div>
<div>接下来 n 行,每行包含两个整数 x 和 y (|x|, |y| ≤ 10^6 ) ,表示多边形上的顶点 (x, y) </div>
<div>顶点按照逆时针顺序给出。</div>
<div>给出的多边形是简单多边形,即它的顶点互不相同,并且除了相邻的两条边在公共点相交之外</div>
<div>它的任意两条边都不会相交。此外,相邻的两条边也不会共线。</div></div>

# Output

<div class="content"><p> 输出能放进给定多边形内部的最长线段长度,其绝对误差或相对误差不能超过 10^-6 。</p></div>

# Sample Input

<div class="content"><span class="sampledata">样例1<br/>
7<br/>
0 20<br/>
40 0<br/>
40 20<br/>
70 50<br/>
50 70<br/>
30 50<br/>
0 50<br/>
样例2<br/>
3<br/>
0 2017<br/>
-2017 -2017<br/>
2017 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例1<br/>
76.157731059<br/>
样例2<br/>
4510.149110617</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供翻译">鸣谢Tangjz提供翻译</a></p></div>

