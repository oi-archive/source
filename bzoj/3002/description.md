
# Description

<div class="content"><div><span style="font-size: medium">       现在你手头有一张某个国家的地图，它是由N行M列的长方形的网格组成的。这个国家有很多城市，每个城市都占据地图中的某一格。你的任务是要建一些路来连接某几对城市。不过，可能会有一些讨厌的石头阻碍你，每个石头有可能会占据多个格，你可以摧毁它，只是要花些钱罢了。当然了，你肯定希望自己在这个事情上少花点钱。</span></div>
<div><span style="font-size: medium"> </span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">地图是以字符的形式给你的。第i行的第j个字符表示第i行第j个方格的情况。每个格子可能有如下的情况：</span></div>
<div><span style="font-size: medium">•     &#39;.&#39; 表示空地。</span></div>
<div><span style="font-size: medium">•     &#39;!&#39;, &#39;@&#39;, &#39;#&#39;, or &#39;$&#39; 表示一个城市。这4种字符中的每一种都会在地图上出现0或者2次。</span></div>
<div><span style="font-size: medium">•     &#39;a&#39;-&#39;z&#39;, &#39;A&#39;-&#39;Z&#39;, or &#39;0&#39;-&#39;9&#39; 表示这个方格里有石头。</span></div>
<div><span style="font-size: medium"> </span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">有些格子中的石头是用同一个字符来代表的，这表示它们是被同一块石头占据的。被同一块石头占据的格子之间将会是互相连接(四连通)的（当然要石头被摧毁后才能走）。这也就是说，如果你想从C1走到C2，那必须存在以下两种情况中的至少一种：</span></div>
<div><span style="font-size: medium">•     C1和C2直接相邻</span></div>
<div><span style="font-size: medium">•     存在一个格子C3，C3和C1相邻，而C3又和C2相连接。</span></div>
<div><span style="font-size: medium"> </span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">不同的石头用不同的字符标识，而摧毁它们所花的钱也是不一样的</span></div>
<div><span style="font-size: medium">•     &#39;a&#39; - &#39;z&#39;: 1 - 26 </span></div>
<div><span style="font-size: medium">•     &#39;A&#39; - &#39;Z&#39;: 100 - 2,600 </span></div>
<div><span style="font-size: medium">•     &#39;1&#39; - &#39;9&#39;: 10,000 - 90,000 </span></div>
<div><span style="font-size: medium">•     &#39;0&#39;: 100,000 </span></div>
<div><span style="font-size: medium"> </span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">你要在被相同字符表示的每对城市之间修路。每条路必须是连续的，从一个城市出发，到另一个城市结束。当然了，路不能修到地图的外面去，路也不能经过没有被摧毁的石头。最后你要输出在修好路的情况下，摧毁石头所需花费的最小钱数。</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">Notes</span></div>
<div><span style="font-size: medium">-      你可以假定道路非常的窄，可以随意互相交叉。</span></div>
<div><span style="font-size: medium">-      道路可以任意通过任意城市。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行包含两个整数<i>N</i><i>，</i><i>M</i>，表示地图的规模。接下来的N行包含<i>N</i>个字符串，每个字符串有M个字符，表示地图的信息。每个字符只能是 &#39;.&#39;, &#39;a&#39;-&#39;z&#39;, &#39;A&#39;-&#39;Z&#39;, &#39;0&#39;-&#39;9&#39;, &#39;!&#39;, &#39;@&#39;, &#39;#&#39;, 或 &#39;$&#39;。四种代表城市的符号在地图上会出现0或2次。整张地图至少会有2个城市。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">表示成功修建道路所需的最小花费。如果你的答案与标准输出一致，那么该测试点得满分，否则得零分。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">【输入样例1】<br/>
2 4<br/>
!1.!<br/>
aab2<br/>
【输出样例1】<br/>
3<br/>
【输入样例2】<br/>
4 2<br/>
#@<br/>
A.<br/>
A1<br/>
@#<br/>
【输出样例2】<br/>
100<br/>
 <br/>
【数据规模和约定】<br/>
100%的数据中N , M ≤ 50。<br/>
       被同一块石头占据的格子之间是互相连通的（前面好像已经说过了）。</span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

