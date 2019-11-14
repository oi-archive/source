
# Description

<div class="content">包括小C在内有N个小朋友, 他们有一个共同的爱好就是收集一些印有NBA球星的卡片． 而可能出现类似这样的情况：小朋友A有&gt;= 2张Tmac的卡片, 而没有一张Yao的卡片; 而小朋友B有&gt;= 2张Yao的卡片, 而没有一张Tmac的卡片, 因此他们会选择交换卡片(1张换1张), 这样他们两个人都有了Yao和Tmac的卡片． 当然这只是一个例子, 而小朋友之间为了使自己的不同的卡片总数尽可能的多, 会相互之间进行交换．一个小朋友会和小C进行交换当且仅当通过一次交换后他的不同的卡片总数会+1, 当然小C不会在意这一点啦, 他可以任意与别人进行交换．小C想知道如何通过若干次交换可以使得自己得到的不同的卡片总数尽可能的多．</div>

# Input

<div class="content">输入文件第一行有两个正整数N, M, 分别表示小朋友的个数以及卡片的总数．为了方便, 本题中第一个小朋友为小C．
接下来有N行, 每行M个非负整数表示第i个小朋友第j种卡片的张数．</div>

# Output

<div class="content">输出文件只有一个整数表示小C最多可以得到多少种不同的卡片</div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
2 1 0 0<br/>
0 2 0 0<br/>
1 0 3 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
友情提示：小C有{1, 1, 2}, 第2个小朋友有{2, 2}, 第3个小朋友有{1, 3, 3, 3, 4}, 小C可以用一张1换第2个小朋友的一张2(第2个小朋友有2种不同的卡片了, 他会选择进行交换), 得到{1, 2, 2}, 再用1张2去换第3个小朋友的一张3, 得到{1, 2, 3}．他不可能得到4, 因此他最多的到3种不同的卡片．</span></div>

# Hint

<div class="content"><p>30%的测试数据中, N, M &lt;= 20．<br/>
100%的测试数据中, N, M &lt;= 200, Card[i][j] &lt;= 1000．</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

