
# Description

<div class="content"><div> 某国有2N个城市，这2N个城市构成了一个2行N列的方格网。现在该国政府有一个旅游发展计划，这个计划需要选定L、R两列(L&lt;=R)，修建若干条专用道路，使得这两列之间（包括这两列）的所有2(R-L+1)个城市中每个城市可以只通过专用道路就可以到达这2(R-L+1)个城市中的任何一个城市。这种专用道路只能在同一行相邻两列的城市或者同一列的两个城市之间修建，且修建需要花费一定的费用。由于该国政府决定尽量缩减开支，因此政府决定，选定L、R后，只修建2(R-L+1)-1条专用道路，使得这些专用道路构成一个树结构。现在你需要帮助该国政府写一个程序，完成这个任务。具体地，该任务包含M个操作，每个操作的格式如下：</div>
<div>1.        C x0 y0 x1 y1 w：由于重新对第x0行第y0列的城市和第x1行第y1列的城市之间的情况进行了考察，它们之间修建一条专用道路的花费变成了w；</div>
<div>2.        Q L R：若政府选定的两列分别为L、R，询问政府的最小开支。</div>
<div></div>
<p class="NOI0"></p></div>

# Input

<div class="content"><p> 第一行，两个整数N、M。</p>
<div>第二行，N-1个整数，其中第i个整数表示初始时第1行第i列的城市和第1行第i+1列的城市之间修建一条专用道路的费用。</div>
<div>第三行，N-1个整数，其中第i个整数表示初始时第2行第i列的城市和第2行第i+1列的城市之间修建一条专用道路的费用。</div>
<div>第四行，N个整数，其中第i个整数表示初始时第1行第i列的城市和第2行第i列的城市之间修建一条专用道路的费用。</div>
<div>接下来的M行，每行一个操作。</div>
<div></div></div>

# Output

<div class="content"><p>对于每个询问操作，输出一行，表示你计算出的政府的最小开支。</p>
<div>
<div></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
1 2<br/>
2 1<br/>
3 1 2<br/>
Q 1 3<br/>
C 1 2 2 2 3<br/>
Q 2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
5</span></div>

# Hint

<div class="content"><p></p><p> 对于全部的数据，1&lt;=N, M&lt;=60000，任何时刻任何一条专用道路的修建费用不超过10^4。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round 1 感谢yts1999上传">Round 1 感谢yts1999上传</a></p></div>

