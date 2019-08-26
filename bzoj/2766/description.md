
# Description

<div class="content"><div style="text-indent: 165pt; line-height: 23pt"><span style="font-size: medium">　<b>      </b><b>　     　   </b></span></div>
<div><span style="font-size: medium"><b> </b></span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">南非世界杯组委会指定了在此期间可提供的一些旅馆供球迷租赁，名为阿凡达的即是其中一所。因为阿凡达旅馆房子的数目不超过26，所以它们可以用26个大写字母表示。</span></div>
<div><span style="font-size: medium">       有一天，刘经理的电话响了，他接到了一个租赁房屋的请求，要求从6月12日晚起租到6月19日中午。于是他察看了预定表，但是并没有发现一间房屋能够直接满足要求。比如房主可能因为一些私人原因需要留在自己的房子中，所以这个游客不得不在其中的一间先住上几天再搬到另一间住上几天。他详细检查了预定表后，对旅客说：“我将你先在B安置3天，再将你安排到F去度过剩余的旅途。”</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">你的目标是使得游客从一间房屋搬到另一间房屋的次数最少。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">注意在旅馆的计费中，总是将某一天的晚上到第二天的中午视作一天。　　　</span></div>
<p></p></div>

# Input

<div class="content"><div><span style="font-size: medium">　　输入文件包括多组数据。</span></div>
<div><span style="font-size: medium">       每组数据输入文件第一行包括两个整数M和N。M表示日程表上的天数，N表示公寓的数目。天数不超过100天，从1开始计数，公寓不超过26个，从A开始计数。</span></div>
<div><span style="font-size: medium">       接下来M行，每行包括N个字母，表示从第i天晚到次日中午，该公寓是否已经被出租，X代表被出租，O代表未被出租。</span></div>
<div><span style="font-size: medium">       最后一行包括两个整数s,t，代表旅客从第s天晚入住到第(t+1)天中午结束旅行。1&lt;=s&lt;t&lt;=M+1。</span></div>
<div><span style="font-size: medium">       M=N=0标志着文件的结束。</span></div></div>

# Output

<div class="content"><div style="line-height: 22pt"> </div>
<div style="text-indent: 21pt"><span style="font-size: medium">对于每一组数据，首先打印测试数据的编号，冒号和一个空行。接下来输出换房次数最少的方案，每一行使用如下格式：</span></div>
<div><span style="font-size: medium">&lt;unit&gt;: &lt;start date&gt;-&lt;end date&gt;</span></div>
<div><span style="font-size: medium">其中unit为房屋编号，&lt;start data&gt;和&lt;end data&gt;分别为该旅客入住和离开该房屋时间。</span></div>
<div><span style="font-size: medium">       注意，如果存在多种方案满足换房次数最少，输出其中字典序最小的方案。</span></div>
<div><span style="font-size: medium">       如不存在这样的方案，输出一行”Not available”。</span></div>
<div><span style="font-size: medium">       每两组输出之间以一个空行隔开。输出文件的末尾不要加空行。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">10 7<br/>
XXXXXXX<br/>
XOXXXXO<br/>
XOXXXXO<br/>
XOXXXOX<br/>
OXXOXOX<br/>
XOXOXOX<br/>
OXXOXOX<br/>
OXXXXOX<br/>
XXXXXXX<br/>
XXXXXXX<br/>
2 9<br/>
0 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1:<br/>
<br/>
B: 2-5<br/>
F: 5-9<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

