
# Description

<div class="content"><div>自动化学制造（Automatic Chemical Manufacturing，简称ACM）正在对一个叫自组装（self-assembly）的过程进行实验。在这个过程中，有着天然相互吸引力的分子被混合在溶液中，任由它们聚集组合成更大的结构。但是有一个问题随之出现：有时候，分子们会把自身组合成一个无限大的结构体，以至于把容器撑爆。</div>
<div></div>
<div>　　你需要写一个程序来判断一个给定的分子集合是否可能组合成一个无限大的结构体。为了使问题简化，你可以作以下两个假设：</div>
<div>　　1. 问题被限制在二维平面上。</div>
<div>　　2. 分子集合中的每个分子都被表示成一个正方形。其中正方形的四条边分别代表分子间相连接的四个表面。</div>
<div></div>
<div>　　你将从数据中得到每种分子的描述。每种分子有四个连接标识来分别表示每条边能与另外分子的哪种边相连。连接标识有两种：</div>
<div>　　● 一个大写字母(A,…,Z)加上一个 ‘＋’ 号或一个 ‘－’ 号。两条边能并在一起当且仅当两者的字母相等且符号相反。比方说，‘A＋’ 与 ‘A－’ 兼容，但与 ‘A＋’ 或 ‘B－’ 不兼容</div>
<div>　　● 两个零 ‘00’。这条边将不和任意一条边兼容（包括‘00’）。</div>
<div></div>
<div>　　假设每种分子都有无限个，并且每个分子都可以旋转和翻转。当分子将自身组成一个结构体时，相互贴合的边必须能够相互兼容，当然，无论边的连接标识是什么，它都可以不与另外边贴合。</div>
<div></div>
<div>　　图 1 是一个由三种分子组成的一个有限的结构体（它们也有可能组成另外的有限结构体）。</div>
<div><img src="source/bzoj/3953/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNC9SZXF1aXJlRmlsZV9kby5qcGc=.jpg" width="1681" height="961" alt=""/></div>
<div class="probtitle" id="ptit" style="margin: 0px; padding: 0px; font-size: 24pt; text-align: left; font-weight: bold; font-family: 微软雅黑, 黑体, &#39;Times New Roman&#39;;">
<div></div>
<div></div>
</div>
<div id="pcont1" style="margin: 20px 0px 0px; padding: 0px; font-family: 宋体, &#39;Times New Roman&#39;;">
<div class="pdcont" style="margin: 0px; padding: 0px; font-family: &#39;Times New Roman&#39;, 宋体; font-size: 14px; color: rgb(32, 0, 0);"></div>
</div>
<p></p></div>

# Input

<div class="content"><p>输入第一行一个数 n，表示分子的种类。</p>
<div>第二行包含 n 个由一个空格隔开的长度为 8 的字符串，每个串描述一种分子。</div></div>

# Output

<div class="content"><p> 输出一行一个英文单词，如果能组成无限大的结构体，输出 unbounded，否则输出 bounded。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
A+00A+A+ 00B+D+A- B-C+00C+</span></div>

# Sample Output

<div class="content"><span class="sampledata">bounded</span></div>

# Hint

<div class="content"><p></p><p> 100%的数据 n ≤ 40000。</p><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

