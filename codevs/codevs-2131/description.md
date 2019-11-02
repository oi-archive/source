<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在宽广的非洲荒漠中，生活着一群勤劳勇敢的羊驼家族。被族人恭称为“先<br>知”的Alpaca L. Sotomon 是这个家族的领袖，外人也称其为“所驼门王”。所<br>驼门王毕生致力于维护家族的安定与和谐，他曾亲自率军粉碎河蟹帝国主义的野<br>蛮侵略，为族人立下赫赫战功。所驼门王一生财宝无数，但因其生性节俭低调，<br>他将财宝埋藏在自己设计的地下宫殿里，这也是今天 Henry Curtis 故事的起点。<br>Henry是一个爱财如命的贪婪家伙，而又非常聪明，他费尽心机谋划了这次盗窃<br>行动，破解重重机关后来到这座地下宫殿前。 <br>整座宫殿呈矩阵状，由 R×C 间矩形宫室组成，其中有 N 间宫室里埋藏着宝<br>藏，称作藏宝宫室。宫殿里外、相邻宫室间都由坚硬的实体墙阻隔，由一间宫室<br>到达另一间只能通过所驼门王独创的移动方式——传送门。所驼门王为这N 间<br>藏宝宫室每间都架设了一扇传送门，没有宝藏的宫室不设传送门，所有的宫室传<br>送门分为三种： <br>1. “横天门”：由该门可以传送到同行的任一宫室； <br>2. “纵寰门”：由该门可以传送到同列的任一宫室； <br>3. “自由门”：由该门可以传送到以该门所在宫室为中心周围 8格中任<br>一宫室（如果目标宫室存在的话）。 <br>深谋远虑的 Henry当然事先就搞到了所驼门王当年的宫殿招标册， 书册上详<br>细记录了每扇传送门所属宫室及类型。而且，虽然宫殿内外相隔，但他自行准备<br>了一种便携式传送门，可将自己传送到殿内任意一间宫室开始寻宝，并在任意一<br>间宫室结束后传送出宫。整座宫殿只许进出一次，且便携门无法进行宫室之间的<br>传送。不过好在宫室内传送门的使用没有次数限制，每间宫室也可以多次出入。 <br>现在 Henry已经打开了便携门，即将选择一间宫室进入。为得到尽多宝藏，<br>他希望安排一条路线，使走过的不同藏宝宫室尽可能多。请你告诉Henry这条路<br>线最多行经不同藏宝宫室的数目。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行给出三个正整数 N, R, C。 <br>以下 N 行，每行给出一扇传送门的信息，包含三个正整数xi, yi, Ti，表示该<br>传送门设在位于第 xi行第yi列的藏宝宫室，类型为 Ti。Ti是一个1~3间的整数，<br>1表示可以传送到第 xi行任意一列的“横天门”，2表示可以传送到任意一行第<br>yi列的“纵寰门”，3表示可以传送到周围 8格宫室的“自由门”。 <br>保证 1≤xi≤R，1≤yi≤C，所有的传送门位置互不相同。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>只有一个正整数，表示你确定的路线所经过不同藏宝<br />宫室的最大数目。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 7 7 <br>2 2 1 <br>2 4 2 <br>1 7 2 <br>2 7 3 <br>4 2 2 <br>4 4 1 <br>6 7 3 <br>7 7 1 <br>7 5 2 <br>5 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>测试点编号 N R C <br>1 16 20 20 <br>2 300 1,000 1,000 <br>3 500 100,000 100,000 <br>4 2,500 5,000 5,000 <br>5 50,000 5,000 5,000 <br>6 50,000 1,000,000 1,000,000 <br>7 80,000 1,000,000 1,000,000 <br>8 100,000 1,000,000 1,000,000 <br>9 100,000 1,000,000 1,000,000 <br>10 100,000 1,000,000 1,000,000</p>
</div>
</div>