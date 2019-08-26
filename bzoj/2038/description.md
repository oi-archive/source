
# Description

<div class="content"><p><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 宋体; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">作为一个生活散漫的人，小<span lang="EN-US">Z</span>每天早上都要耗费很久从一堆五颜六色的袜子中找出一双来穿。终于有一天，小<span lang="EN-US">Z</span>再也无法忍受这恼人的找袜子过程，于是他决定听天由命<span lang="EN-US">……<br/>
</span>具体来说，小<span lang="EN-US">Z</span>把这<span lang="EN-US">N</span>只袜子从<span lang="EN-US">1</span>到<span lang="EN-US">N</span>编号，然后从编号<span lang="EN-US">L</span>到<span lang="EN-US">R(L </span>尽管小<span lang="EN-US">Z</span>并不在意两只袜子是不是完整的一双，甚至不在意两只袜子是否一左一右，他却很在意袜子的颜色，毕竟穿两只不同色的袜子会很尴尬。<span lang="EN-US"><br/>
</span>你的任务便是告诉小<span lang="EN-US">Z</span>，他有多大的概率抽到两只颜色相同的袜子。当然，小<span lang="EN-US">Z</span>希望这个概率尽量高，所以他可能会询问多个<span lang="EN-US">(L,R)</span>以方便自己选择。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">输入文件第一行包含两个正整数N和M。N为袜子的数量，M为小Z所提的询问的数量。接下来一行包含N个正整数Ci，其中Ci表示第i只袜子的颜色，相同的颜色用相同的数字表示。再接下来M行，每行两个正整数L，R表示一个询问。</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">包含M行，对于每个询问在一行中输出分数A/B表示从该询问的区间[L,R]中随机抽出两只袜子颜色相同的概率。若该概率为0则输出0/1，否则输出的A/B必须为最简分数。（详见样例）</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 4<br/>
1 2 3 3 3 2<br/>
2 6<br/>
1 3<br/>
3 5<br/>
1 6<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2/5<br/>
0/1<br/>
1/1<br/>
4/15<br/>
【样例解释】<br/>
询问1：共C(5,2)=10种可能，其中抽出两个2有1种可能，抽出两个3有3种可能，概率为(1+3)/10=4/10=2/5。<br/>
询问2：共C(3,2)=3种可能，无法抽到颜色相同的袜子，概率为0/3=0/1。<br/>
询问3：共C(3,2)=3种可能，均为抽出两个3，概率为3/3=1/1。<br/>
注：上述C(a, b)表示组合数，组合数C(a, b)等价于在a个不同的物品中选取b个的选取方案数。<br/>
【数据规模和约定】<br/>
30%的数据中 N,M ≤ 5000；<br/>
60%的数据中 N,M ≤ 25000；<br/>
100%的数据中 N,M ≤ 50000，1 ≤ L &lt; R ≤ N，Ci ≤ N。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=版权所有者：莫涛">版权所有者：莫涛</a></p></div>

