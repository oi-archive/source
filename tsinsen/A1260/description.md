<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　一年一度的圣诞节快要来到了。每年的圣诞节小E都会收到许多礼物，当然他也会送出许多礼物。不同的人物在小E心目中的重要性不同，在小E心中分量越重的人，收到的礼物会越多。小E从商店中购买了n件礼物，打算送给m个人，其中送给第i个人礼物数量为w<sub>i</sub>。请你帮忙计算出送礼物的方案数（两个方案被认为是不同的，当且仅当存在某个人在这两种方案中收到的礼物不同）。由于方案数可能会很大，你只需要输出模P后的结果。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含一个正整数P，表示模；<br/>
　　第二行包含两个整整数n和m，分别表示小E从商店购买的礼物数和接受礼物的人数；<br/>
　　以下m行每行仅包含一个正整数w<sub>i</sub>，表示小E要送给第i个人的礼物数量。</div>
# 输出格式

<div class="pdcont">　　若不存在可行方案，则输出“Impossible”，否则输出一个整数，表示模P后的方案数。</div>
# 样例输入

<div class="pddata">100<br/>
4 2<br/>
1<br/>
2</div>
# 样例输出

<div class="pddata">12</div>
# 样例输入

<div class="pddata">100<br/>
2 2<br/>
1<br/>
2</div>
# 样例输出

<div class="pddata">Impossible</div>
# 样例说明

<div class="pdcont">　　下面是对样例1的说明。<br/>
　　以“/”分割，“/”前后分别表示送给第一个人和第二个人的礼物编号。12种方案详情如下：<br/>
　　1/23 1/24 1/34<br/>
　　2/13 2/14 2/34<br/>
　　3/12 3/14 3/24<br/>
　　4/12 4/13 4/23</div>
# 数据规模和约定

<div class="pdcont">　　设P=p<sub>1</sub>^c<sub>1</sub> * p<sub>2</sub>^c<sub>2</sub> * p<sub>3</sub>^c<sub>3</sub> * … *p<sub>t</sub> ^ c<sub>t</sub>，p<sub>i</sub>为质数。<br/>
　　对于15%的数据，n≤15，m≤5，p<sub>i</sub>^c<sub>i</sub>≤10<sup>5</sup>；<br/>
　　在剩下的85%数据中，约有60%的数据满足t≤2，c<sub>i</sub>=1，p<sub>i</sub>≤10<sup>5</sup>，约有30%的数据满足p<sub>i</sub>≤200。<br/>
　　对于100%的数据，1≤n≤10<sup>9</sup>，1≤m≤5，1≤p<sub>i</sub>^c<sub>i</sub>≤10<sup>5，1</sup>≤P≤10<sup>9</sup>。</div>

</div>