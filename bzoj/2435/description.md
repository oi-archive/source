
# Description

<div class="content"><p>在 W 星球上有 n 个国家。为了各自国家的经济发展，他们决定在各个国家<br/>
之间建设双向道路使得国家之间连通。但是每个国家的国王都很吝啬，他们只愿<br/>
意修建恰好 n – 1条双向道路。 每条道路的修建都要付出一定的费用， 这个费用等于道路长度乘以道路两端的国家个数之差的绝对值。例如，在下图中，虚线所示道路两端分别有 2 个、4个国家，如果该道路长度为 1，则费用为1×|2 – 4|=2。图中圆圈里的数字表示国家的编号。</p>
<p><img height="221" width="631" alt="" src="/source/bzoj/2435/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTEwOC8xKDIpLmpwZw==.jpg"/><br/>
由于国家的数量十分庞大，道路的建造方案有很多种，同时每种方案的修建<br/>
费用难以用人工计算，国王们决定找人设计一个软件，对于给定的建造方案，计<br/>
算出所需要的费用。请你帮助国王们设计一个这样的软件。</p></div>

# Input

<div class="content"><p><br/>
输入的第一行包含一个整数n，表示 W 星球上的国家的数量，国家从 1到n<br/>
编号。接下来 n – 1行描述道路建设情况，其中第 i 行包含三个整数ai、bi和ci，表<br/>
示第i 条双向道路修建在 ai与bi两个国家之间，长度为ci。</p>
<p><br/>
</p></div>

# Output

<div class="content"><p>输出一个整数，表示修建所有道路所需要的总费用。</p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
6 <br/>
1 2 1 <br/>
1 3 1 <br/>
1 4 2 <br/>
6 3 1 <br/>
5 2 1 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
20<br/>
</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
n = 1,000,000 1≤ai, bi≤n <br/><br/>
0 ≤ci≤ 10^6<br/><br/>
 <br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day2">Day2</a></p></div>

