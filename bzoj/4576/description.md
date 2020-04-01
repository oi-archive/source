
# Description

<div class="content"><div>262144 （262144）</div>
<div></div>
<div>Description</div>
<div>Bessie喜欢在她的手机上下载游戏玩，尽管她发现她的大蹄使用小触摸屏幕相当麻烦。她特别感兴趣的是她正在玩</div>
<div>的游戏。 游戏从一个有N个正整数的序列开始（2≤N≤262,144），每个数字在1...40的范围内。 在一个步骤中，</div>
<div>Bessie可以获取具有相等值的两个相邻数字，并且用比这两个数大一的值替换这两个数值（例如，她可以用8替换</div>
<div>两个相邻的7）。目标是在游戏结束时最大化在序列中存在的最大数字的值。 请帮助Bessie得分尽可能高！</div>
<div></div>
<div>题目大意：</div>
<div>给定一个长度为n（n&lt;=2^18）的序列，初始元素值为1到40之间的整数，每次操作可以将两个相邻的并且大小相同</div>
<div>的正整数替换成一个比原数大一的正整数。要求最大化最终数列中的最大值。</div>
<div></div></div>

# Input

<div class="content"><p>第一行输入包含N，接下来的N行在游戏开始时给出N个数字的序列。</p></div>

# Output

<div class="content"><p>请输出可以生成的最大整数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1<br/>
1<br/>
1<br/>
2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
//在所示的示例中，Bessie首先合并第二和第三个1以获得序列1 2 2，然后她将两个2合并成3. 注意，合并前两个1不是最佳的。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum 鸣谢g1n0st提供译文">Platinum 鸣谢g1n0st提供译文</a></p></div>

