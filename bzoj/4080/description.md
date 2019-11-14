
# Description

<div class="content"><p> 魔法炮来到了帝都，除了吃特色菜之外，还准备去尝一尝著名的北京烤鸭。帝都一共有n(1&lt;=1&lt;=100)个烤鸭店，可以看成是二维平面内的点。不过由于魔法炮在吃烤鸭之前没有带钱，所以吃完烤鸭之后只能留下刷盘子。刷完盘子之后，魔法炮除了不用付饭费之外，老板还会奖励他d(1&lt;=d&lt;=10000)元钱。魔法炮是一个特么喜欢吃烤鸭的孩子，所以在去过一家烤鸭店之后，魔法炮还准备去其他的烤鸭店。但是由于帝都路费较贵，每单位长度需要花费1元钱，所以魔法炮可能去不了所有其他的烤鸭店。在到达下一家烤鸭店之前，魔法炮会花掉手里所有钱，以便于下一次接着吃霸王餐。另外，魔法炮对于自己刷过盘子的烤鸭店有着特殊的感情，所以他要求在某一家烤鸭店吃完烤鸭后，可以到达全部已经吃过去过的烤鸭店。那么问题来了，魔法炮想知道自己最多能去多少家烤鸭店，以及这些烤鸭店都是哪些。你能帮帮他吗？</p>
<div>题目大意：给定平面内的n个点，选出一个点集S，使得S里的所有点两两之间欧几里得距离不超过d，问|S|的最大值以及S里的点都有哪些。若答案有多种，输出任意一个。</div>
<div>第一行两个整数n和d，分别表示烤鸭店数和老板给魔法炮的路费。</div>
<div></div></div>

# Input

<div class="content"><p>接下来n行，每行两个整数x,y，表示n个烤鸭店的坐标。</p>
<div></div></div>

# Output

<div class="content"><p>第一行一个数m，表示魔法炮最多能去多少家烤鸭店。</p>
<div>第二行m个数，每个数表示魔法炮能去的烤鸭店标号。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 1<br/>
0 0<br/>
0 1<br/>
1 0<br/>
1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1 2<br/>
</span></div>

# Hint

<div class="content"><p></p><p> 数据范围：1&lt;=n&lt;=100  1&lt;=d&lt;=10000  -10000&lt;=x,y&lt;=10000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢ZidaneAndMessi">鸣谢ZidaneAndMessi</a></p></div>

