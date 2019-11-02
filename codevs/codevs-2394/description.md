<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>       Bill和Scott是商业对手。他们都计划在Javaville城市购买一幢房子，但是他们希望自己的住宅尽量远离对方的住宅。由于Javaville是一座新兴的城市，所以暂时还没有地图，于是，他们只能从当地人的口中搜集信息，这些信息包括建筑物的位置和建筑物之间的距离。尽管这些信息并不完整，但是它们都是正确的。</p>
<p>       Javaville的街道是一个矩形网格，包含m条东西走向的街道，依次用大写字母A,B,C,…标识，n条南北走向的街道，依次用数字0,1,2,…标识。我们把两条街道的交点称为交叉路口，两个交叉路口之间的一段街道称为街区。所有的建筑物都位于交叉路口处，每个交叉路口至多只有一座建筑物。建筑物之间的距离定义为从一座建筑物到另一座建筑物所需经过的最少的街区数。</p>
<p>       例如，Bill和Scott搜集了以下这些信息：</p>
<p>l  城市中有5条东西走向的街道和5条南北走向的街道；</p>
<p>l  住宅1位于交叉路口A0；</p>
<p>l  邮局位于交叉路口A4；</p>
<p>l  学校与住宅1距离4个街区；</p>
<p>l  住宅2与邮局距离6个街区；</p>
<p>l </p>
<p>学校与邮局距离6个街区；</p>
<p>l  <br> 住宅3与邮局距离6个街区；</p>
<p>根据以上信息，我们可以得到Javaville城市可能的两种布局。我们发现：住宅1，邮局和学校的位置都已经确定了，而住宅2可以位于C0或E2，住宅3可以位于C0或E2。于是，城市中总是存在两座住宅相距6个街区（地图1中的h1与h3，地图2中的h1与h2）。但是，对于确定的两座住宅，我们可以保证的最长距离只有4个街区 (h2与h3的距离总是4个街区)。于是，我们要告诉Bill和Scott，尽管总是存在两座相距6个街区的住宅，然而最安全的建议是：一人购买住宅2，另一人购买住宅3。</p>
<p>下面给出所求数值的严格定义：</p>
<p>l  一个可行的城市布局S的直径d(S)定义为该布局中距离最远的两座住宅之间的距离。</p>
<p>l  对于确定的两座住宅i, j，它们的安全系数e[i, j]定义为在所有可行的城市布局中，住宅i, j之间的距离的最小值。</p>
<p>Bill和Scott希望你编写一个程序，根据他们所搜集到的信息，计算出D和E。其中：D =min{d(S) }；E =max{e[i, j]}。同时你还要给出最安全的购房建议，即所有满足e[i, j]=E的住宅i, j。</p>
<p>对于上面的例子，第一种布局的d(S<sub>1</sub>)=6，第二种布局的d(S<sub>2</sub>)=6。每两座住宅之间的安全系数是：e[1,2]=2，e[1,3]=2，e[2,3]=4。于是：D= min{d(S<sub>1</sub>),d(S<sub>2</sub>)}=6，E= max{e[1,2],e[1,3],e[2,3]}=4，最安全的购房建议是：住宅2与住宅3。</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个正整数m, n（1&lt;=m, n&lt;=10），分别表示东西走向的街道数目和南北走向的街道数目。第二行包含一个整数，表示所搜集到的信息条数t(1&lt;=t&lt;=50)。文件从第三行开始每行描述一条所搜集到的信息，每条信息都是以下两种形式之一：</p>
<p>       name  LOCATION  r  c</p>
<p>或者</p>
<p>       name  DISTANCE  d  name2</p>
<p>       这两种形式分别描述建筑物的位置和建筑物之间的距离。</p>
<p>其中，name和name2是仅包含数字和小写字母的字符串，长度不超过20，表示建筑的名称。r是A到J之间的大写字母，c是一个数字，表示建筑物所位于的交叉路口。d是一个正整数，表示两座建筑物之间的距离。如果建筑物名称的前五个字符是小写字母“house”，那么表示这是一座可以购买的住宅，否则表示一座非民用的建筑物。如果信息是第二种形式，那么其中的name2一定在前面的信息中出现过。</p>
<p>这组信息中至少包含两座可以购买的住宅，至多包含25座不同的建筑物。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行包含两个整数，分别表示D和E，之间用一个空格隔开。输出文件从第二行开始给出所有的最安全的购房建议，每个购房建议占一行，购房建议可以以任意的顺序排列，但是不能重复。输出文件每行末尾不得有多余的空格。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5</p>
<p>6</p>
<p>house1 LOCATION A 0</p>
<p>postoffice LOCATION A 4</p>
<p>school DISTANCE 4 house1</p>
<p>house2 DISTANCE 6 postoffice</p>
<p>school DISTANCE 6 postoffice</p>
<p>house3 DISTANCE 6 postoffice</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div>6 4</div>
<div>house2 house3</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见题面</p>
</div>
</div>