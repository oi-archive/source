
# Description

<div class="content"><div>一年一度的圣诞节快要来到了。每年的圣诞节小E都会收到许多礼物，当然他也会送出许多礼物。不同的人物在小E</div>
<div>心目中的重要性不同，在小E心中分量越重的人，收到的礼物会越多。小E从商店中购买了n件礼物，打算送给m个人</div>
<div>，其中送给第i个人礼物数量为wi。请你帮忙计算出送礼物的方案数（两个方案被认为是不同的，当且仅当存在某</div>
<div>个人在这两种方案中收到的礼物不同）。由于方案数可能会很大，你只需要输出模P后的结果。</div></div>

# Input

<div class="content"><div>输入的第一行包含一个正整数P，表示模；</div>
<div>第二行包含两个整整数n和m，分别表示小E从商店购买的礼物数和接受礼物的人数；</div>
<div>以下m行每行仅包含一个正整数wi，表示小E要送给第i个人的礼物数量。</div></div>

# Output

<div class="content"><p>若不存在可行方案，则输出“Impossible”，否则输出一个整数，表示模P后的方案数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">100 <br/>
4 2 <br/>
1 <br/>
2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">12<br/>
【样例说明】<br/>
下面是对样例1的说明。<br/>
以“/”分割，“/”前后分别表示送给第一个人和第二个人的礼物编号。12种方案详情如下：<br/>
1/23 1/24 1/34<br/>
2/13 2/14 2/34<br/>
3/12 3/14 3/24<br/>
4/12 4/13 4/23 <br/>
【数据规模和约定】<br/>
设P=p1^c1 * p2^c2 * p3^c3 * … *pt ^ ct，pi为质数。<br/>
对于100%的数据，1≤n≤109，1≤m≤5，1≤pi^ci≤10^5。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

