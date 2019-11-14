
# Description

<div class="content"><p>在一个高度信息化的渔村，鱼网的制作和修补都是由电脑完成。众所周知，鱼网是由网组成的(废话)，网组成的东西叫网眼。如果网眼够小，就能捕到很多鱼；如果网眼太大，鱼就会全部漏走。每次捕鱼回来，鱼网都会烂得很厉害，小网眼会变成网眼，那鱼网就需要修补。他们希望有一个程序能够为他们判断鱼网是否需要修补。程序会把鱼网看作一个联通的图(不用进一步解释了吧)。他们的判断方法是：任何一个长度(组成其的边的数目)超过3的闭合的圈，都必须有一条交线将它分作两部分。(提示：递归下去，其实就是每个网眼都只能是三角形)如果合乎要求，程序就输出“Perfect&#34;,否则输出&#34;Imperfect&#34;. 注：这里的交线是指一个联结一封闭圈的不同结点而捕属于该圈的一条边。</p></div>

# Input

<div class="content"><p>数据以一行N M开始，表示鱼网有N个结点和M条边。(n&lt;=0&lt;=1000)以下M行是M条边的描述。每行两个整数A，B，表示结点A与结点B之间存在一条边。</p></div>

# Output

<div class="content"><p>输出每个鱼网的测试结果，Perfect或Imperfect</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 1<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Imperfect</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

