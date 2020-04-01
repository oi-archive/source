
# Description

<div class="content"><div>不久之前，Mirko建立了一个旅行社，名叫“极地之梦”。这家旅行社在北极附近购买了N座冰岛，并且提供观光服</div>
<div>务。当地最受欢迎的当然是帝企鹅了，这些小家伙经常成群结队的游走在各个冰岛之间。Mirko的旅行社遭受一次</div>
<div>重大打击，以至于观光游轮已经不划算了。旅行社将在冰岛之间建造大桥，并用观光巴士来运载游客。Mirko希望</div>
<div>开发一个电脑程序来管理这些大桥的建造过程，以免有不可预料的错误发生。这些冰岛从1到N标号。一开始时这些</div>
<div>岛屿没有大桥连接，并且所有岛上的帝企鹅数量都是知道的。每座岛上的企鹅数量虽然会有所改变，但是始终在[0</div>
<div>, 1000]之间。你的程序需要处理以下三种命令：</div>
<div>1.&#34;bridge A B&#34;——在A与B之间建立一座大桥（A与B是不同的岛屿）。由于经费限制，这项命令被接受，当且仅当</div>
<div>A与B不联通。若这项命令被接受，你的程序需要输出&#34;yes&#34;，之</div>
<div>后会建造这座大桥。否则，你的程序需要输出&#34;no&#34;。</div>
<div>2.&#34;penguins A X&#34;——根据可靠消息，岛屿A此时的帝企鹅数量变为X。这项命令只是用来提供信息的，你的程序不</div>
<div>需要回应。</div>
<div>3.&#34;excursion A B&#34;——一个旅行团希望从A出发到B。若A与B连通，你的程序需要输出这个旅行团一路上所能看到的</div>
<div>帝企鹅数量（包括起点A与终点B），若不联通，你的程序需要输出&#34;impossible&#34;。</div></div>

# Input

<div class="content"><div>第一行一个正整数N，表示冰岛的数量。</div>
<div>第二行N个范围[0, 1000]的整数，为每座岛屿初始的帝企鹅数量。</div>
<div>第三行一个正整数M，表示命令的数量。接下来M行即命令，为题目描述所示。</div>
<div>1&lt;=N&lt;=30000,1&lt;=M&lt;=100000</div></div>

# Output

<div class="content"><p>对于每个bridge命令与excursion命令，输出一行，为题目描述所示。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
4 2 4 5 6<br/>
10<br/>
excursion 1 1<br/>
excursion 1 2<br/>
bridge 1 2<br/>
excursion 1 2<br/>
bridge 3 4<br/>
bridge 3 5<br/>
excursion 4 5<br/>
bridge 1 3<br/>
excursion 2 4<br/>
excursion 2 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
impossible<br/>
yes<br/>
6<br/>
yes<br/>
yes<br/>
15<br/>
yes<br/>
15<br/>
16<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

