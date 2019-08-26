
# Description

<div class="content"><div>上次毛明明请你帮他计算了在国内去某个城市旅游的最小路费，真是太感谢你了！但是毛明明的奖学金实在太多了</div>
<div>，他计划把国内的n个城市全都游历一遍，但是他不想中途再经过已经去过的城市。这个问题又要请你帮忙了！全</div>
<div>国共有n个城市，铁路系统的信息已经知道了。由于铁路公司严重亏损，目前关停了原先的一些线路，仅留下了n-1</div>
<div>条铁路保持运行，并保证了任意两个城市之间还是可以通过铁路连通。航空公司的航线也做了调整：在新的铁路系</div>
<div>统中，所有没有铁路直接相连、但是通过乘坐2次火车能够到达的城市之间，开设有双向的飞机航班。例如：共4个</div>
<div>城市、3条铁路，三条铁路分别为：城市1~城市2、城市2~城市3、城市3~城市4。这个情况下，共开设有2种双向航</div>
<div>班，一种为城市1到城市3，另一种为城市2到城市4。城市1到城市2间没有航班，因为它们有铁路直接相连；城市1</div>
<div>到城市4间也没有航班，因为它们不能通过乘2次火车互相到达，至少需乘3次火车。毛明明现在在1号城市，他想不</div>
<div>重不漏地游遍剩下n-1个城市，且要求最后能在n号城市结束旅行。请你帮毛明明设计一种周游全国的方案。火车、</div>
<div>飞机任你选择，这次就不要求你考虑路费了~</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行，包含一个整数n，表示城市个数。</div>
<div>接下来n-1行，每行两个整数u、v（1≤u,v≤n，u≠v），表示城市u和城市v之间有一条铁路。</div>
<div>2≤n≤500000</div>
<div></div>
<div></div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>若存在合法的方案，输出任意一组。共输出n行，</div>
<div>每行一个整数，依次给出你的方案中毛明明要去的城市，第一行为1，第n行为n。</div>
<div>若不存在合法的方案，输出“Nosolution.”（不包含括号）。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">12<br/>
1 7<br/>
7 8<br/>
7 11<br/>
7 2<br/>
2 4<br/>
4 10<br/>
2 5<br/>
5 9<br/>
2 6<br/>
3 6<br/>
3 12</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
11<br/>
8 <br/>
7 <br/>
4<br/>
10<br/>
2 <br/>
9 <br/>
5 <br/>
6 <br/>
3<br/>
12</span></div>

# Hint

<div class="content"><p></p><p><img src="source/bzoj/5175/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMi8xMSgxKS5wbmc=.png" width="445" height="416" alt=""/></p><br/>
<p>无SPJ，请不要提交！</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

